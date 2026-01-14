# S2O-Platform
=======
# S2O-Platform (Smart Scan to Order Platform)

S2O-Platform is a multi-tenant SaaS system that enables restaurants to provide QR-based ordering, customer mobile experiences, and AI-powered recommendations.

## System Components

- **Backend API**: Flask Clean Architecture, Multi-Tenant SaaS
- **Web Application**: React (Admin, Restaurant, Guest/Customer QR)
- **Mobile Application**: React Native (Customer App)
- **AI Modules**: Chatbot QA (RAG) & Recommendation Engine
- **Infrastructure**: Docker, PostgreSQL, Redis

## Project Structure

```text
S2O-Platform/
├── backend/        # Flask Clean Architecture API
├── frontend-web/   # React Web (Admin, Restaurant, Guest/Customer)
├── mobile-app/     # React Native Mobile App (Customer App)
├── docs/           # System documents
├── .env.example    # Environment variables template
└── docker-compose.yml