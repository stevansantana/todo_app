# 📋 Todo App

Aplicação web simples de lista de tarefas feita com **Ruby on Rails**.

---

## 🚀 Tecnologias utilizadas

- Ruby 3.x
- Rails 7.x
- SQLite3
- Node.js
- Yarn
- Turbo / Hotwire

---

## 📦 Requisitos para rodar o projeto

Antes de começar, instale:

- [Ruby](https://www.ruby-lang.org/)
- [Rails](https://rubyonrails.org/)
- [Bundler](https://bundler.io/)
- [Node.js](https://nodejs.org/)
- [Yarn](https://classic.yarnpkg.com/en/docs/install)

---

## ⚙️ Como rodar o projeto

Siga o passo a passo abaixo no terminal:

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/todo_app.git
cd todo_app

# Instale as dependências Ruby
bundle install

# Instale os pacotes JavaScript (caso use esbuild ou importmaps)
yarn install

# Configure o banco de dados
rails db:create
rails db:migrate

# Rode o servidor local
rails server
