# Deno REST API

> This is a REST API using Deno, Oak and PostgreSQL
> Original code from instructor Brad Traversy

> What i learnt: Introduction to Deno, Typescript and PostgreSQL

Be sure to install https://www.postgresql.org/ and edit the "config.ts" file with your own credentials

### Run
´´´
# This project uses Denon
deno start
´´´

### Routes
´´´
GET      /api/v1/products
GET      /api/v1/products/:id
POST     /api/v1/products
PUT      /api/v1/products/:id
DELETE   /api/v1/products/:id
´´´