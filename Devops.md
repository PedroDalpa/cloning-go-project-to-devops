Tecnologia: GO
Versão: 1.22.2
Porta: 8080
Postgres

DEV
  Preparação
  - go mod download && go mod verify
  Execução
  - go run cmd/journey/journey.go - execução

Prod 
 Preparação
  - go mod download && go mod verify
  - go build cmd/journey/journey.go
  Execução
  - ./journey