# 💻 Sobre o desafio

Nesse desafio, criei uma aplicação para treinar o que aprendi até agora no Node.js!

É aplicação para gerenciar tarefas (em inglês *todos*). É permitida a criação de um usuário com `name` e `username`, bem como fazer o CRUD de *todos*:

- Criar um novo *todo*;
- Listar todos os *todos*;
- Alterar o `title` e `deadline` de um *todo* existente;
- Marcar um *todo* como feito;
- Excluir um *todo*;

Tudo isso para cada usuário em específico (o `username` é passado pelo header). A seguir segue uma lista completa dos requisitos e as regras de negócio 🚀

---

### Requisitos

[x] - Should be able to create a new user
[x] - Should be able to list all user's todos
[x] - Should be able to update a todo
[x] - Should be able to mark a todo as done
[x] - Should be able to delete a todo

---

### Regras de Negócio
[x] - Should not be able to delete a non existing todo
[x] - Should not be able to mark a non existing todo as done
[x] - Should not be able to update a non existing todo
[x] - Should not be able to create a new user when username already exists