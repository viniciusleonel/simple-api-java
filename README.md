# Simple API Java

Aplicação API para fins didáticos

## Pré-requisito

- Java 21
- Git

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

```
docker run -d -p 8080:8080 --net=host -e PROFILE=prd api

```










