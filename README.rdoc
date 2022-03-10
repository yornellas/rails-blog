# Blog

Projeto criado segundo o passo a passo do Ruby on Rails Guides (https://guides.rubyonrails.org/getting_started.html)

## Requisitos Necessários:
* Ruby 2.3.0 ou Superior
* SQLite3
* Rails 4.2.8

## Funcionalidades

- CRUD de artigos para o blog
- CRUD de comentários vinculados aos artigos

## Para executar o projeto:
### Clone em sua máquina

```shell
git clone git@github.com:yornellas/rails-blog.git```

### Instale as dependências
```shell
cd blog2
bundle install
```
### Configure o Banco de Dados
Copie o arquivo *config/database.exemple.yml* e cole na mesma pasta, renomeando para *database.yml*
e configure seu bando de dados.
Realize a criação do banco e execute as migrações
```shell
rake db:create
rake db:migrate
```

### Execute a aplicação
```shell
rails server
```
