# Livraria MERN — versão inicial

Mesmo projeto de cadastro de livros do [book-store-mern](https://github.com/Brandon-Magalhaes/book-store-mern), na primeira versão do código.

> **Use o [book-store-mern](https://github.com/Brandon-Magalhaes/book-store-mern)**: é a versão mantida, com README, licença, ícones, notificações e tratamento de carregamento. Este repositório está aqui apenas como histórico.

## Stack

MongoDB · Express · React (Vite) · Node.js

## Como rodar

```bash
# backend
cd backend
npm install
cp .env.example .env      # preencha MONGODB_URI
npm run dev               # http://localhost:5555

# frontend
cd frontend
npm install
npm run dev               # http://localhost:5173
```

## Variáveis de ambiente

| Variável | Uso |
|---|---|
| `MONGODB_URI` | string de conexão do MongoDB |
| `PORT` | porta do backend (padrão 5555) |
