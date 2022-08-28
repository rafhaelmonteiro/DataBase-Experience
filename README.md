# DataBase-Experience

Desafio git: criar um repositório no github ✅

## Anotações:

- Configurar o git com o controlador de versão que está utilizando: Github/BitBucket/GitLab etc...

Comando:

git config --list => Lista todas as configurações do git

verificar user email e user nickname, se eles são os mesmo do controle de versão utilizado.

Para remover o usuário ou nickname usar o comando:

git config --global --unset user.email ou git config --global --unset user.nickname

para adicionar o usuário ou nickname usar o comando:

git config --global user.email "rafhaelmonteiro@gmail.com" ou git config --global user.nickname "rafhaelmonteiro"

adicionar o remote origin do repositório:

git remote add origin https://github.com/rafhaelmonteiro/DataBase-Experience.git

git push origin main
