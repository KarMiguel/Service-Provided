# Projeto de Cadastro de Clientes e Serviços Prestados

Este projeto Spring Boot oferece uma API para gerenciar clientes, serviços prestados aos clientes e autenticação de usuários.

## Instalação

1. Clone na brach back-end do repository:

```bash
https://github.com/KarMiguel/Spring-Angular-Service-Provided.git
```

2. Instale dependências com Maven

3. Instale [PostgreSQL](https://www.postgresql.org/)

## Uso

1. Inicie o aplicativo com Maven
2. A API estará acessível em http://localhost:8090

## Gerenciamento de Clientes

- **Cadastrar Cliente**: `POST /api/client/`
- **Buscar Cliente por ID**: `GET /api/client/{id}`
- **Atualizar Cliente**: `PUT /api/client/{id}`
- **Excluir Cliente**: `DELETE /api/client/{id}`
- **Listar Todos os Clientes**: `GET /api/client/`

## Gerenciamento de Serviços Prestados

- **Cadastrar Serviço Prestado**: `POST /api/service-provided`
- **Listar Todos os Serviços Prestados**: `GET /api/service-provided/list`
- **Pesquisar Serviços Prestados**: `GET /api/service-provided`

## Autenticação de Usuários

- **Registrar Novo Usuário**: `POST /api/auth/register`
- **Login de Usuário**: `POST /api/auth/login`

## Contribuição
Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões de melhorias, abra um problema ou envie uma solicitação pull ao repositório.
Ao contribuir para este projeto, siga o estilo de código existente, [convenções de commit](https://www.conventionalcommits.org/en/v1.0.0/), e envie suas alterações em um branch separado
