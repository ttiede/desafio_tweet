 
***Projeto completo com container***
------------------------------
----------

**Dependências**

 - Docker
 - Docker-compose
Gerando o container e executando utilizando o docker, execute o comando abaixo na pasta do projeto:


> docker-compose up

Iniciando assim os aplicativos responsáveis pelo backend e frontend.

**Backend**
-----------

Acesso ao callpointers disponibilizado pelo backend:

Lista dos tweets por relevância.
http://localhost:3000/most_relevants

Lista os usuários que mais mencionam a empresa.
http://localhost:3000/most_mentions

**Testes**
Executar os testes do container, execute o comando:

   

> docker-compose run -e "RAILS_ENV=test" api rspec spec

**Frontend**
------------

O acesso da aplicação frontend é feito na url:
http://localhost:4200


----------

Aplicação Backend - Listagem de Tweets
=================


----------



----------
**Dependências**

----------


 - Ruby 2.4.0p0
 - Rails 5.1.2
 - Bundler 1.15.1


----------
***Orientações***

----------

Antes de executar o backend é necessário instalar as dependências:

 >   bundle install

Para iniciar o  servidor execute o comando:

   >  rails server

Acesso ao callpointers disponibilizado pelo backend:

 - Lista dos tweets por relevância.

`http://localhost:3000/most_relevants`  

 

- Lista os usuários que mais mencionam a empresa.

`http://localhost:3000/most_mentions`

Testes
 O comando abaixo executa os testes desenvolvidos:

  >  bundle exec rspec spec


----------


 

Lista de Tweets para Suporte
--------------------------


----------


Aplicação frontend que consome a API do projeto :
[https://github.com/ttiede/back_api_tweet](https://github.com/ttiede/back_api_tweet)


----------

**Dependências**


----------

 - Node.js
 - Angularjs

Aplicação necessita do código do backend em execução na porta 3000

[https://github.com/ttiede/back_api_tweet](https://github.com/ttiede/back_api_tweet)

**Descrição**


----------


A instalação do  Angularjs com o comando:

>    npm install -g angular-cli

Acesse a pasta do projeto e instale as dependências
O comando para instalar a dependências é:

 >   npm install

Para iniciar o projeto execute o comando:

>    npm start

A url para acessar a aplicação frontend  é
    
> http://localhost:4200


