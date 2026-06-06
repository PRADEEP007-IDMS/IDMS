# IDMS Backend API

Node.js/Express REST API for the Integrated Data Management System.

## Quick Start

```bash
npm install
cp .env.example .env
npm run dev
```

The server will run on `http://localhost:3001`

## Available Endpoints

- `GET /health` - Health check
- `GET /api/health` - API health check
- `POST /api/auth/register` - Register user
- `POST /api/auth/login` - Login user
- `GET /api/chemicals` - List chemicals
- `GET /api/products` - List products
- `GET /api/market-data` - Get market data
- `POST /api/reports/generate` - Generate report

See full API documentation in `/docs`
