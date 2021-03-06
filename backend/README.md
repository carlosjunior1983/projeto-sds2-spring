# Bootcamp: Semana Spring React/Java SDS2

Projeto DSDelivery: Projeto desenvolvido em Spring Boot/Java.


## Tecnologia

`Java` `Spring Boot` `H2` `PostgreSQL` `Maven` `Heroku` 


## Checklist
    - Setup
        - Dependências
        - Arquivos .properties
        - Configuração de segurança

    - Modelo de domínio
        - Entidades e relacionamentos
        - Mapeamento objeto-relacional
        - Seed

    - Criar endpoints
        - [GET] /products
        - [GET] /orders
        - [POST] /orders
        - [PUT] /orders/{id}/delivered

    - Perfis
        - test: h2
        - dev: PostgreSQL local
        - prod: Heroku

    - Preparar projeto para implantação
        - Arquivo system.properties

    - Heroku
        - Criar app e provisionar PostgreSQL
        - Criar base de dados remota
        - Executar comandos no Heroku CLI

```
heroku login
heroku git:remote -a <nome-do-app>
git remote -v
git subtree push --prefix backend heroku main

```


Heroku App: https://sds2-dsdelivery-cjr.herokuapp.com/



## Modelo Visão Camadas


<h1 align="center">
    <img alt="SDS2" title="#Vision" src="https://github.com/carlosjunior1983/projeto-sds2-spring/blob/main/backend/img/camadas.png"  /><br>
</h1>




## Modelagem do Domínio

<h1 align="center">
    <img alt="SDS2" title="#Model" src="https://github.com/carlosjunior1983/projeto-sds2-spring/blob/main/backend/img/modelo-conceitual.png"  /><br>
</h1>



### Criação do Banco de dados PostgreSQL (Perfil DEV)

1. Crie o database: dsdelivery
2. Execute o script: [Create.SQL](https://github.com/carlosjunior1983/projeto-sds2-spring/blob/main/backend/create.sql)
3. Configure seu profile para Dev.


<br>
Créditos: DevSuperior/SDS2
