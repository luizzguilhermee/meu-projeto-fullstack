<h1 align="center">🚀 Projetinho Básico do Gui Fullstack – React + Node.js</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Online-success?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Frontend-React-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Backend-Node.js-green?style=for-the-badge"/>
  <img src="https://img.shields.io/github/license/SEU_USUARIO/meu-projeto?style=for-the-badge"/>
</p>

<p align="center">
  Sistema de cadastro de usuários com <b>frontend em React (Vite)</b> e <b>backend em Node.js (Express)</b>.  
  Treino de integração fullstack, API REST e boas práticas 🔥
</p>

---

## 📂 Estrutura do Projeto

```
meu-projeto/
 ├── backend/    # API Node.js (Express)
 │   ├── server.js
 │   ├── package.json
 │   └── .env (não vai pro Git)
 │
 └── frontend/   # App React (Vite)
     ├── index.html
     ├── package.json
     └── src/
```

---

## ⚙️ Tecnologias Usadas

<div align="center">

| Frontend | Backend | Ferramentas |
|---------|---------|------------|
| React   | Node.js | Git / GitHub |
| Vite    | Express | .env para variáveis |
| Axios   | Nodemon | NPM |

</div>

---

## 📦 Como Rodar Localmente

### 1️⃣ Clonar o projeto

```bash
git clone https://github.com/luizzguilhermee/meu-projeto-fullstack.git
cd meu-projeto
```

---

### 2️⃣ Instalar e rodar o **backend**

```bash
cd backend
npm install
npm start
```

Servidor sobe em: **http://localhost:3000**

---

### 3️⃣ Instalar e rodar o **frontend**

Em outro terminal:

```bash
cd frontend
npm install
npm run dev
```

Aplicação sobe em: **http://localhost:5173**

---

## 📑 Endpoints da API

| Método | Rota        | Descrição                |
|-------|-------------|------------------------|
| GET   | /usuarios   | Lista todos os usuários |
| POST  | /usuarios   | Cria novo usuário       |
| DELETE| /usuarios/:id | Remove usuário pelo ID |

---

## 📸 Demonstração

<p align="center">
  <img src="./assets/demo.png" width="600px"/>
</p>

---

## 👨‍💻 Autor

Luis Guilherme
[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github)](https://github.com/luizzguilhermee)
