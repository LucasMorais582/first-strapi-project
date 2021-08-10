# first-strapi-project

Aplicação de estudo backend que contém os principais conceitos que constituem o framework Strapi

## Tecnologias

- NPM Package
- NodeJs
- Javacript
- Prettier
- Strapi
- MongoDB
- Docker

## Preparação do ambiente

Clonando o projeto
```
git clone https://github.com/LucasMorais582/account-management.git
```
Após acessar o diretório do projeto, rodar o comando no terminal para baixar a node_modules:
```
yarn init
```

## Banco de dados:
- O primeiro passo é instalar o [Docker](https://docs.docker.com/engine/install/) na sua máquina
- Em seguida, instalar a imagem do [Mongo DB](https://hub.docker.com/_/mongo).

## Strapi: 
- Para executar o código, é necessário instalar o framework [Strapi](https://strapi.io/documentation/developer-docs/latest/getting-started/quick-start.html)


## Passos para inicializar a aplicação:

Rodar o comando:
```
npm run start
```
Para consumir a aplicação, utilize uma API Client como Postman ou Insomnia e acesse a URL:
- http://localhost:1337

Para desenvolver a aplicação, basta acessar a URL:
- http://localhost:1337/admin

Esse exercício foi tirado de um artigo da [Medium](https://medium.com/manacespereira/construindo-uma-api-completa-com-nodejs-strapi-em-menos-tempo-do-que-voc%C3%AA-imagina-9b787d3a8cde).
