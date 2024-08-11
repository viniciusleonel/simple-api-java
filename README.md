# Simple API Java

Aplicação API para fins didáticos

## Pré-requisito

- Java 17

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