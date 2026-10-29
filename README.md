# Desafio Beca Java 2026

Projeto desenvolvido para o desafio da Beca Java 2026.

A ideia é criar uma API de gestão financeira usando Java e Spring Boot. O sistema terá cadastro de usuários, transações e consultas de informações financeiras.

## Funcionalidades

- Cadastro, consulta, atualização e exclusão de usuários
- Importação de usuários por arquivo CSV
- Depósitos, retiradas, transferências e compras
- Consulta de saldo e limites por uma API simulada
- Conversão de moedas usando a BrasilAPI
- Resumo de despesas e exportação de relatório CSV

## Tecnologias

- Java e Spring Boot
- Spring Data JPA
- PostgreSQL
- Docker e Docker Compose
- JUnit e Mockito
- Swagger/OpenAPI
- Git e GitHub

## Organização do projeto

O projeto será dividido em duas APIs:

- **MS1 - Usuários:** responsável pelo cadastro e gerenciamento dos usuários.
- **MS2 - Transações:** responsável pelas operações financeiras, usando arquitetura hexagonal.

As APIs poderão ser testadas pelo Postman, Insomnia ou Swagger.

## Como executar

O projeto ainda está em desenvolvimento. Quando o Docker Compose estiver configurado, será possível iniciar a aplicação com:

```bash
docker compose up --build -d
```

## Status

Em desenvolvimento.
