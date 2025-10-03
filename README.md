9# 🚀 CRUD em Go (Golang)

Um projeto de **CRUD completo em Go**, construído com o framework **Gin** e o ORM **GORM**.  
A ideia é apresentar de forma simples e prática como desenvolver uma API REST para criar, listar, atualizar e remover usuários.

---
## 📂 Estrutura do Projeto

crud-golang/ │-- main.go │-- database/ │   └── database.go │-- models/ │   └── user.go │-- routes/ │   └── routes.go

---

## ⚙️ Como rodar o projeto

Clone o repositório e instale as dependências:
```bash
git clone https://github.com/seu-usuario/crud-golang.git
cd crud-golang
go mod tidy

Inicie a aplicação:

go run main.go

A API estará disponível em:
👉 http://localhost:8080


---

#🌐 Endpoints

POST /users → Criar usuário

GET /users → Listar usuários

GET /users/:id → Buscar por ID

PUT /users/:id → Atualizar usuário

DELETE /users/:id → Deletar usuário



---

#🛠 Tecnologias

Go (linguagem principal)

Gin (framework web)

GORM (ORM para banco de dados)

SQLite (banco simples para testes)



---
#✨ Sobre

Este projeto foi desenvolvido como uma forma prática de estudar Go e explorar na prática conceitos de CRUD, APIs REST e persistência de dados.
É um exercício de aprendizado aplicado, que pode servir de base para projetos maiores e mais completos.

 ##💡 Feito com dedicação e café ☕
