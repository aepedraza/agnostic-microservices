# agnostic-microservices [WIP]
POC about how to communicate MS written in different languages

This repository contains sample microservices communicating through REST API's. Services are:

- `gateway`: Entry point to the MS architecture. Written in Java using [Spring Cloud Netflix](https://spring.io/projects/spring-cloud-netflix)
- `book`: Book MS written in Node.js. Accessible through the gateway using the URL `/books/*`
- `author`: Author MS written in Python. Accesible through the gateway using the URL `/authors/*`
- `category`: Category MS written in Ruby. Accesible through the gateway using the URL `/categories/*`

**Note:** This is a work in progress, additional libraries/frameworks for `book`, `author` and `category` will be added when coded