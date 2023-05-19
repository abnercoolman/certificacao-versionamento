# 1º Commit - certificacao-versionamento
Códigos das aulas de versionamento.

# 2º Commit - certificacao-versionamento

Adicionando configuração do _**git hub**_

## Comandos básicos para subir ou dar o _"push"_ no repositório

- Para adicionar o arquivo
``` > git add .  ```
- Para adicionar um comentário
``` > git commit -m "Adicionando alteração do arquivo readme" ``` 
- Para subir as alterações no repositório, na brach "main", basta executar
``` > git push origin main ```

# 3º Commit - certificacao-versionamento
### Criando um novo repositório no site do GitHub

- No site do GitHub, com o seu usário pessoal logado, acesse a aba _"Repositories"_;
- Em seguida clique no botão _"New"_ para criar um novo repositório;
- Para esta exemplificação daremos para este repositório o nome _"new-repositorio"_.

### Criando um link deste novo repositório com uma pasta local

- Para criar a pasta do repositório, criaremos uma pasta chamada _"new-repositorio"_:
``` > mkdir new-repositorio ```
- Acessamos esta pasta com o comando:
``` > cd new-repositorio ```
- Adicionamos o arquivo _"readme.md"_ diretamente na pasta _"new-repositorio"_, ou podemos criar este arquivo por linha de comando usando:
``` > echo "# new-repositorio" >> README.md ```
- Em seguida, precisamos incializar esta pasta para o git reconhecer que este repositório realmente existe:
``` > git init ```
- Utilizamos então o comando ```add``` para adicionar o arquivo que acabou de ser criado, para que este seja preparado para as alterações:
``` > git add .  ```
- Fazemos então o primeiro _"commit"_:
``` > git commit -m "First Commit - Readme File Add" ``` 

### Verificando a existência de _"branches"_

- Inicalmente precisamos verificar se existe alguma branch relacionada ao repositório:
``` > git status ```
- Para subir as alterações no repositório, na brach "main", basta executar
``` > git push origin main ```