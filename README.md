# 🌦️ Climate Monitoring

Aplicação **full stack** para monitoramento de condições climáticas. O projeto possui cadastro e login de usuários, pesquisa de cidades, histórico de informações meteorológicas e armazenamento de cidades salvas.

## 🚀 Tecnologias utilizadas

### Front-end
- React
- TypeScript
- Vite
- Axios
- React Router

### Back-end
- Node.js
- Express
- Mongoose
- JSON Web Token (JWT)
- bcryptjs

### Banco de dados
- MongoDB

## 🔧 Funcionalidades

- Cadastro de usuários
- Login e autenticação
- Consulta de clima por cidade
- Salvamento de cidades
- Histórico de informações meteorológicas
- Rotas de usuários, localidades e alertas
- Interface responsiva

## 🏗️ Estrutura

```text
Frontend (React + TypeScript)
        ↓
Backend (Node.js + Express)
        ↓
MongoDB / Mongoose
```

O back-end roda por padrão na porta `5000`, enquanto o front-end utiliza o Vite na porta `5173`.

## ▶️ Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/VitorHens/Climate-Monitoring.git
cd Climate-Monitoring
```

### 2. Configure o back-end

```bash
cd backend
npm install
```

Crie um arquivo `.env` dentro da pasta `backend` e configure a conexão com o MongoDB:

```env
MONGODB_URI=sua_uri_do_mongodb
PORT=5000
```

Depois inicie o servidor:

```bash
npm start
```

### 3. Inicie o front-end

Em outro terminal:

```bash
cd frontend
npm install
npm run dev
```

A aplicação ficará disponível em:

```text
http://localhost:5173
```

## 📸 Screenshots

### Página inicial
![Página inicial](images/HomeInit.png)

### Dashboard
![Dashboard](images/Home.png)

### Login
![Login](images/SignIn.png)

### Cadastro
![Cadastro](images/SignUp.png)

### Conta
![Conta](images/Account.png)

## 🔒 Boas práticas

Arquivos `.env`, `node_modules`, builds e arquivos locais de IDE são ignorados pelo Git. Use `.env.example` como referência e nunca publique credenciais reais.

## 🎯 Objetivo do projeto

Praticar o desenvolvimento de uma aplicação full stack integrando **front-end, back-end, autenticação e banco de dados NoSQL**.

---

Desenvolvido por **Vitor Hens**.
