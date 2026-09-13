# Backend - AI Warehouse Assistant

## Setup

```bash
cd backend
npm install
cp .env.example .env
npm run dev
```

## API Endpoints

- `POST /api/auth/register` - Registar utilizador
- `POST /api/auth/login` - Login
- `GET /api/products` - Listar produtos
- `POST /api/products` - Criar produto
- `GET /api/stock/movements` - Listar movimentos
- `POST /api/stock/movements` - Registar movimento
- `POST /api/ai/ask` - Perguntar ao Warehouse Assistant
- `GET /api/reports/inventory` - Relatório de inventário
