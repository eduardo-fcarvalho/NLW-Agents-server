# NLW Agents - Backend

Este é o repositório do backend do projeto **NLW Agents**, desenvolvido durante a Next Level Week promovida pela Rocketseat.

## 🔧 Tecnologias Utilizadas

- Node.js
- Express
- TypeScript
- PostgreSQL
- Prisma ORM
- JWT para autenticação
- CORS
- Dotenv

## 🚀 Funcionalidades

- Cadastro e autenticação de agentes
- Criação e listagem de mensagens
- Integração com banco de dados PostgreSQL via Prisma
- Middleware de autenticação JWT
- Validações com Zod

## 📦 Instalação e Uso

```bash
# Clone o repositório
git clone https://github.com/eduardo-fcarvalho/NLW-Agents-server

# Acesse a pasta do projeto
cd NLW-Agents-server

# Instale as dependências
npm install

# Configure as variáveis de ambiente
cp .env.example .env

# Execute as migrações (após configurar o banco)
npx prisma migrate dev

# Inicie o servidor
npm run dev
```

## 📁 Estrutura de Pastas

- `src/controllers` - Lógica de controle das rotas
- `src/routes` - Definições das rotas da API
- `src/services` - Serviços auxiliares
- `src/prisma` - Instância de conexão com o banco
