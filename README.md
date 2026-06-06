# Integrated Data Management System (IDMS)

**For India's Chemical & Petrochemical Sector**

A comprehensive web-based system commissioned by the Department of Chemicals and Petrochemicals and Ministry of Chemicals and Fertilizers, Government of India.

## Project Overview

IDMS is designed to gather, store, share, and automate data across the chemical and petrochemical industry for monitoring, policy-making, and international collaboration with UNSC member countries.

## Key Features

- **Chemical & Product Catalog** — Comprehensive database of chemicals, products, and specifications
- **Market Data Analytics** — Production volumes, import/export trends, pricing data
- **Inventory Management** — Real-time stock tracking with alerts
- **Technical Data Sheets** — Auto-generated PDF TDS with templates
- **Country Collaboration** — Data sharing and approval workflow with UNSC members
- **Government Dashboards** — Policy reports and sector-wise analytics
- **Role-Based Access** — Government, Industry, International, Admin, Researcher roles
- **Audit & Compliance** — Complete audit trail and security compliance

## Architecture

### Stack

**Backend:** Node.js/Express, PostgreSQL, Elasticsearch, Redis
**Frontend:** React.js, TypeScript, Tailwind CSS
**DevOps:** Docker, Kubernetes, CI/CD
**Security:** OAuth 2.0, JWT, AES-256 encryption, TLS 1.3

### Project Structure

```
IDMS/
├── backend/                 # Node.js/Express API
├── frontend/                # React.js web application
├── database/                # PostgreSQL schemas and migrations
├── docker-compose.yml       # Local development setup
├── .github/                 # CI/CD workflows
└── docs/                    # Documentation
```

## Quick Start

### Prerequisites

- Node.js >= 16
- PostgreSQL >= 12
- Docker & Docker Compose
- npm or yarn

### Local Development

```bash
# Clone repository
git clone https://github.com/PRADEEP007-IDMS/IDMS.git
cd IDMS

# Setup with Docker Compose
docker-compose up -d

# Or manual setup

# Backend
cd backend
npm install
npm run dev

# Frontend (new terminal)
cd frontend
npm install
npm start
```

## Phases & Timeline

- **Phase 1** — Requirements & Architecture (Weeks 1–3)
- **Phase 2** — Database & Data Model Design (Weeks 4–6)
- **Phase 3** — Backend Development (Weeks 7–14)
- **Phase 4** — Frontend Development (Weeks 10–18)
- **Phase 5** — Integration Layer (Weeks 15–18)
- **Phase 6** — Security & Compliance (Throughout)
- **Phase 7** — DevOps & Infrastructure (Weeks 12–20)
- **Phase 8** — Testing (Weeks 18–21)
- **Phase 9** — Rollout & Training (Weeks 22–24)

## Documentation

See `/docs` folder for detailed documentation:
- API Specifications (Swagger)
- Database Schema
- Architecture Diagrams
- User Manuals
- Deployment Guide

## Contributing

Please follow the contribution guidelines in `CONTRIBUTING.md`

## License

Government of India | Ministry of Chemicals and Fertilizers

## Support

For issues or questions, please contact the development team or file an issue on GitHub.
