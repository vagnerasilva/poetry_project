## Utilizando poetry para o projeto


## Ferramenta para gerenciamento de dependencias no python

# Step1 inciar o projeto
poetry new flask_app_delivery

# Step2 iniciar o virtual env 
poetry shell

# Step3 
poetry config virtualenvs.in-project true

# Step4 adicionando libs
poetry add flask

# Step5 criando requirements.txt
poetry export -f requirements.txt --output requirements.txt --without-hashes

# Dicas

## verificar
poetry config --list

## listando envs que existem 
poetry env list --full-path

