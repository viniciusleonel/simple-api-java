# Simple API Java

Aplicação API 

## Pré-requisito

- Java 21
- Git
- Docker

#### Docker

* Criar imagem

```
docker build -t api .
```

* Executar container

```
docker run -p 8080:8080 --net=host \
-e PROFILE=prd \
-e DATABASE_URL=jdbc:mysql://localhost:3306/api?createDatabaseIfNotExist=true \
-e DATABASE_USER=root \
-e DATABASE_PWD=1234 \
api
```








