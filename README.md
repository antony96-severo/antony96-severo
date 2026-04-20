<h1 align="center">👨‍💻 Antony Severo</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?color=00F7FF&size=24&center=true&vCenter=true&width=600&lines=Backend+Developer;Python+%7C+APIs+%7C+SQL;Construindo+sistemas+reais;Foco+em+arquitetura+e+regras+de+negócio" />
</p>

<p align="center">
Backend Developer | Python • APIs • SQL
</p>

---

## 🧠 Sobre

Desenvolvedor focado em **backend**, com experiência prática na construção de **APIs REST**, modelagem de dados e implementação de regras de negócio.

Atuo principalmente com **Python**, criando aplicações com foco em:
- organização de código
- segurança
- funcionamento real de sistemas

---

## ⚙️ Stack Principal

### 🔹 Backend
![Python](https://img.shields.io/badge/Python-333?style=for-the-badge&logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi)
![Flask](https://img.shields.io/badge/Flask-000?style=for-the-badge&logo=flask)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-red?style=for-the-badge)

### 🗄️ Banco de Dados
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql)

### 🧩 Arquitetura & Conceitos
- REST APIs  
- CRUD completo  
- Relacionamentos entre tabelas  
- Regras de negócio  
- Autenticação com token  
- Estrutura de rotas  
- Validação de dados  

### 🛠️ Ferramentas
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github)

---

## 🚀 Projetos em Destaque

---

### 🏦 API Bancária (FastAPI)

API REST completa simulando operações bancárias reais, com foco em **regras de negócio**, **segurança** e **controle de acesso**.

🔗 Repositório:  
https://github.com/antony96-severo/api-bancaria-fastapi

💡 Funcionalidades:
- Criação de contas de usuário  
- Autenticação com JWT  
- Criação de conta bancária vinculada ao usuário  
- Depósito, saque e transferência  
- Consulta de saldo  
- Histórico de transações  
- Validações de regras de negócio:
  - Não permite saldo negativo  
  - Não permite operações sem autenticação  
  - Usuário acessa apenas a própria conta  
  - Controle de permissões por usuário  

📌 Exemplo de endpoint:

    POST /transaction
    Authorization: Bearer <token>

📌 Exemplo de requisição:

    {
      "tipo": "transferencia",
      "valor": 100,
      "conta_destino_id": 2
    }

📌 Regras aplicadas:
- Validação de saldo antes de saque/transferência  
- Controle de propriedade da conta  
- Proteção de rotas com autenticação

---

### 🍕 API Pizzaria (FastAPI)

API REST com foco em regras de negócio e controle de pedidos.

🔗 Repositório:  
https://github.com/antony96-severo/fastapi-pizzaria

💡 Funcionalidades:
- Autenticação com token  
- Controle de usuários (admin e comum)  
- CRUD de pedidos  
- Relacionamento entre entidades  
- Cálculo automático de preço  
- Controle de acesso por usuário  

📌 Exemplo de endpoint:

    GET /pedido/{id_pedido}
    Authorization: Bearer <token>

📌 Exemplo de resposta:

    {
      "quantidade_itens_pedido": 3,
      "pedido": {
        "id": 1,
        "status": "PENDENTE",
        "preco": 75.50
      }
    }

---

### 🛍️ Urbanna (Flask)

Sistema de vitrine com painel administrativo.

🔗 Repositório:  
https://github.com/antony96-severo/urbanna

💡 Funcionalidades:
- CRUD de produtos  
- Upload de imagens  
- Sistema de busca  
- Controle de sessão admin  
- Integração com WhatsApp  

---

### 🖼️ MyGallery (Flask)

Sistema web com lógica completa de backend.

🔗 Repositório:  
https://github.com/antony96-severo/my-gallery

💡 Funcionalidades:
- Cadastro e autenticação  
- Upload de imagens  
- Feed dinâmico  
- Rotas dinâmicas  

---

### 📚 CRUD Livros (SQLite + Tkinter)

Aplicação desktop com persistência de dados.

🔗 Repositório:  
https://github.com/antony96-severo/crud-book

💡 Funcionalidades:
- CRUD completo  
- Integração com SQLite  
- Interface gráfica  

---

## 📊 Estatísticas

<p align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=antony96-severo&show_icons=true&theme=tokyonight"/>
</p>

---

## 🎯 Objetivo

Evoluir como desenvolvedor backend, aprofundando em:

- Arquitetura de sistemas  
- APIs mais complexas  
- Banco de dados relacional  
- Boas práticas de código  
- Segurança  

---

## 📫 Contato

- GitHub: https://github.com/antony96-severo  

---

<p align="center">
  💡 Construindo sistemas reais para me tornar um backend profissional.
</p>
