# Forum Hub 🗣️

Um fórum centralizado para criação, leitura, atualização e exclusão de tópicos (CRUD), com autenticação JWT para proteger ações sensíveis como criar, editar ou deletar posts.

---

## 📋 Descrição

O **Forum Hub** é uma API (ou aplicação) voltada à criação e gerenciamento de tópicos de discussão. Usuários autenticados podem criar, editar ou remover tópicos, enquanto qualquer pessoa pode visualizar os tópicos disponíveis.

---

## 🚀 Funcionalidades

- ✅ Cadastro e login de usuários com autenticação JWT
- ✅ Criação de novos tópicos (autenticado)
- ✅ Listagem de tópicos públicos
- ✅ Atualização e exclusão de tópicos (autenticado e autorizado)
- ✅ Middleware de proteção para rotas privadas
- ✅ (Opcional) Respostas/comentários nos tópicos

---

## 🛠️ Tecnologias utilizadas

Preencha com o que você usou:

- Node.js / Express / NestJS / etc.
- MongoDB / PostgreSQL / Prisma / Sequelize
- JWT para autenticação
- TypeScript / JavaScript
- (Outros)

---

## 🔐 Autenticação

A autenticação é baseada em JWT:

- Após o login, um **token JWT** é retornado.
- Esse token deve ser enviado no header `Authorization: Bearer <token>` nas rotas protegidas.
- Usuários não autenticados **não podem criar, editar ou deletar** tópicos.

---

# Obrigado por visualizar este projeto. 😁