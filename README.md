# comunicacao-micro-servicos

Comandos Docker para criação do banco de dados postgress

docker run --name auth-db -p 5432:5432 -e POSTGRES_DB=auth-db -e POSTGRES_USER=admin -e POSTGRES_PASSWORD=123456 postgres:11
