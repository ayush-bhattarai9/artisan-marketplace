# Artisan Marketplace

**Artisan Marketplace** is a community-driven platform that connects local artisans and producers directly with buyers. It facilitates the discovery and sale of unique local crafts, agricultural products, and services, empowering local communities by fostering direct economic engagement.

## 🔧 Tech Stack

| Layer    | Technology               |
|----------|--------------------------|
| Backend  | Python (FastAPI or Django) |
| Frontend | Next.js (React)          |
| Database | PostgreSQL              |

## 🗂️ Repository Structure
```
artisan-marketplace/
├── backend/       # Python (FastAPI or Django) backend
├── frontend/      # Next.js frontend
├── docs/          # Modular documentation
└── README.md      # Project overview
```

## 💡 Development Principles

- Clean Architecture (for maintainability and modularity)
- TDD-first (test-driven development with pytest for backend, Jest for frontend)
- Minimal dependencies and frameworks unless necessary
- Raw SQL via SQLAlchemy (or Django ORM) for precision control
- Git discipline via Conventional Commits

## 📚 Documentation

See [docs/](./docs) for full module-wise documentation.

## 🛠️ Tool Versions
- Python 3.10+
- PostgreSQL 17.5