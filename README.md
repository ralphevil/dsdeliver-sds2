# DS Delivery 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/andrezasecon/dsdeliver-sds2/LICENSE) 

# Sobre o projeto

https://dsdelivery-raphael.netlify.app/

DS Delivery é uma aplicação full stack web e mobile construída durante a 2ª edição da **Semana DevSuperior** (#sds), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em um app de pedidos e envio de pedidos, onde um cardápio é listado ao usuário, que escolhe os produtos e adiciona o endereço de entrega, após enviar o pedido com sucesso, os pedidos são listados no app mobile do motoboy que escolhe os pedidos a serem entregues e através do próprio app é traçado a rota de entrega.

## Layout mobile
![Mobile 1](https://github.com/ralphevil/dsdeliver-sds2/blob/main/.github/mob1.png) ![Mobile 2](https://github.com/ralphevil/dsdeliver-sds2/blob/main/.github/mob2.png) ![Mobile 3](https://github.com/ralphevil/dsdeliver-sds2/blob/main/.github/mob3.png)

## Layout web
![Web 1](https://github.com/ralphevil/dsdelivery-sds2/blob/main/.github/web1.png)

![Web 2](https://github.com/ralphevil/dsdelivery-sds2/blob/main/.github/web2.png)

## Modelo conceitual
![Image](https://github.com/andrezasecon/dsdelivery-sds2/blob/main/assets/modelo-conceitual.png)

## Camadas
![camadas](https://github.com/andrezasecon/dsdelivery-sds2/blob/main/assets/camadas.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven

## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- React Native

## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
https://github.com/ralphevil/dsdeliver-sds2

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
https://github.com/ralphevil/dsdeliver-sds2

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
npm install

# executar o projeto
npm start
```

