# Simple API Java

Aplicação API para fins didáticos

## Pré-requisito

- Java 21
- Git
- Conta no GitHub.com

## Setup e Uso

### Execução / Local dev

#### Terminal

```sh
./mvnw spring-boot:run -Dspring-boot.run.profiles=prd
```

## Execução


#### Docker

* Criar imagem

```
docker build -t api .
```

* Executar container

spring.profiles.active=dev

```
docker run -d -p 8080:8080 --net=host -e PROFILE=prd api

```

## Java

> [Spring Initializr](https://start.spring.io/) - Criar aplicação conforme a configuração 

## Referencias

 - https://spring.io/projects/spring-framework
 - https://plantuml.com/



# Aulas

###  Fork

https://github.com/acnaweb/simple-api-java

### GitFlow

https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow

### Configuração de branchs

- Criar branch develop
- Criar branch release
- Tornar develop default branch

### Clone do projeto

git clone https://github.com/acnaweb/simple-api-java.git

git status 
    - branch "develop"
  
git branch -r
    - branchs remotas
  
### Setup do git 

git config user.email "prof.antoniojunior@fiap.com.br"
git config user.name "Antonio Carlos"

## Features










