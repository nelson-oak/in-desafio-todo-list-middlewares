# Todo List - Desafio Complementar 1A

Desafio com o intuito de fixar os conceitos de middlewares de API Rest com Node.js e Express

## Entidades

| Entidades | Atributos |
| - | - |
| user | id, name, username, pro, todos |
| todo | id, title, done, deadline, created_at |

## Requisitos

- [x] Deve ser possível cadastrar um usuário
- [x] Deve ser possível um usuário virar Pro
- [x] Deve ser possível listar as tarefas de um usuário
- [x] Deve ser possível cadastrar uma tarefa de um usuário
- [x] Deve ser possível editar o título e a deadline de uma tarefa
- [x] Deve ser possível marcar uma tarefa como realizada
- [x] Deve ser possível deletar uma tarefa

## Regras de negócio

- [x] Não deve ser possível criar um usuário com um username já cadastrado
- [x] Não deve ser possível listar tarefas de um usuário que não existe
- [x] Não deve ser possível cadastrar tarefas para um usuário que não existe
- [x] Não deve ser possível cadastrar mais de 10 tarefas se o usuário não for pro
- [x] Não deve ser possível editar tarefas de um usuário que não existe
- [x] Não deve ser possível editar tarefas que não exitem
- [x] Não deve ser possível marcar uma tarefa como realizada de um usuário que não existe
- [x] Não deve ser possível marcar uma tarefa que não existe como realizada
- [x] Não deve ser possível deletar tarefas de um usuário que não existe
- [x] Não deve ser possível deletar tarefas que não exitem

## Recursos

- Express
- Dados armazenados em memória

## Iniciando o projeto

Após clonar o projeto, é necessário atualizar as dependências.

### Comandos para baixar dependências e iniciar a aplicação

```bash
yarn
yarn dev
```

### Testar a aplicação

```bash
yarn test
```