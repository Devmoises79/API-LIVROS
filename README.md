# 📚 API Básica — Flask (CRUD de Livros)

📖 Sobre o Projeto

Este projeto consiste em uma API REST simples desenvolvida com Flask, com foco no aprendizado e prática de criação de serviços backend em Python.

A aplicação simula um sistema de gerenciamento de livros, permitindo operações completas de CRUD (Create, Read, Update e Delete), utilizando dados armazenados em memória.

# 🎯 Objetivos

- Praticar desenvolvimento de APIs REST com Flask
- Implementar operações CRUD completas
- Trabalhar com rotas dinâmicas (/livros/<id>)
- Manipular dados em formato JSON
- Utilizar ferramentas como Postman para testes

# ⚙️ Tecnologias Utilizadas

- Python 3
- Flask
- JSON
- Request (manipulação de dados HTTP)
- Postman (testes de API)

# 🧩 Funcionalidades

📖 GET /livros:

* Retorna todos os livros cadastrados.

🔎 GET /livros/{id}: 

* Retorna um livro específico pelo ID.

➕ POST /livros: 

* Adiciona um novo livro ao sistema.

✏️ PUT /livros/{id}:

* Atualiza os dados de um livro existente.

❌ DELETE /livros/{id}: 

* Remove um livro da lista.

# 📌 Estrutura de Dados

Cada livro segue o padrão:

```bash

{
  "id": 1,
  "Título": "Pai Rico, Pai Pobre",
  "Autor": "Robert Kiyosaki"
}
```

# 🧠 Aprendizados

Este projeto reforça conceitos essenciais de backend:

- Criação de APIs REST com Flask
- Manipulação de rotas HTTP
- Estruturação de CRUD
- Uso de JSON como padrão de comunicação
- Organização de lógica de backend
- Testes de endpoints

# 🚀 Execução

```bash
pip install flask
python app.py
```

A API será executada em:

```bash
http://localhost:5000
```

# 👨‍💻 Autor

Projeto desenvolvido por Moisés Aniceto como parte de estudos em desenvolvimento backend com Python e construção de APIs REST.
