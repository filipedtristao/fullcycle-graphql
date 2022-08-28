# Exemplo de implementação de GraphQL

1. Suba o container rodando:
```
docker-compose up -d
```

2. Acesse o container:
```
docker-compose exec app sh
```

4. Iniciar server
```
go run cmd/server/server.go
```

# Comandos úteis
Para iniciar um novo projeto com graphql:
```
go run github.com/99designs/gqlgen init
```

Gerar models
```
gqlgen generate
```
