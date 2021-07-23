# Sobre o desafio 🚀

## 💻 Descrição
Desenvolver middlewares para validação das rotas, com a aplicação de todo já criada. Dessa vez o usuário terá um plano, onde o ele só pode criar até dez todos e um plano Pro que irá permitir criar todos ilimitados.

## 🛠️ Funcionalidades

- Criar um usuário com `name` e `username`
- Criar um novo todo
- Listar todos os _todos_;
- Alterar o `title` e `deadline` de um _todo_ existente;
- Marcar um _todo_ como feito;
- Excluir um _todo_;

## 🔗 Rotas

- POST `/users` → criar um usuário.
- GET `/users/:id` → pesquisa um usuário pelo id
- PATCH `/users/:id/pro` → atualiza o plano do usuário para PRO caso não seja
- GET `/todos` → lista com todas as tarefas do usuário.
- POST `/todos` → criar um todo.
- PUT `/todos/:id` → atualiza um todo.
- PATCH `/todos/:id/done` → atualiza a propriedade `done` do todo para `true`.
- DELETE `/todos/:id` → deleta um todo pela `id`

##### Uso

Com as dependências instaladas rode yarn dev para subir o servidor.