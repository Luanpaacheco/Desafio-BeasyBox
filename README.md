# 💼 Desafio

Este repositório contém a aplicação, composta por um Back-End em Node.js com MongoDB e um Front-End em React. A aplicação simula um ambiente interno com controle de acesso e funcionalidades de chatbot e histórico de mensagens.

---

## ⚙️ Pré-requisitos

Antes de iniciar, certifique-se de ter instalado:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/)
- npm (vem junto com o Node.js)

---

## 📥 Clonando o repositório

```bash
git clone https://github.com/Luanpaacheco/Desafio.git
cd Desafio
```

---

## 🖥️ Back-End

### 📂 Acessando a pasta

```bash
cd BackEnd
```

### 📦 Instalando dependências

```bash
npm install
```

### ⚙️ Configuração do ambiente

Crie um arquivo `.env` dentro da pasta `BackEnd` com o seguinte conteúdo (substitua pelos seus dados válidos):

```
DATABASE_URL="sua_url_valida_do_mongodb"
JWT_SECRET="seu_segredo_jwt"
```

### 🔧 Gerando client do Prisma

```bash
npx prisma generate
```

### ▶️ Executando o servidor

```bash
npm run dev
```

📡 Servidor disponível em: [http://localhost:5000](http://localhost:5000)

---

## 💻 Front-End

### 📂 Acessando a pasta

```bash
cd FrontEnd/desafioFrontEnd
```

### 📦 Instalando dependências

```bash
npm install
```

### ▶️ Executando o front-end

```bash
npm run dev
```

🌐 Aplicação disponível em: [http://localhost:5173](http://localhost:5173) (ou outra porta)

---

## 🔗 Rotas principais

- `/home` → Tela de login
- `/chat` → Chatbot com IA
- `/history` → Histórico de mensagens

---

## 🔐 Acesso

Como se trata de uma aplicação para uso interno da empresa, os usuários devem receber suas credenciais da equipe de TI. A funcionalidade de cadastro não está disponível.

### 👤 Usuário de exemplo

- **E-mail:** cleiton@taurus.com
- **Senha:** password1

### 👤 Outro usuário de teste

- **E-mail:** teste@taurus.com
- **Senha:** password1

---

## 📁 Estrutura do projeto

```
Desafio/
│
├── BackEnd/              # API com Node.js, Express e Prisma
│
└── FrontEnd/
    └── desafioFrontEnd/  # Interface com React e Vite
```

---

