# .net-auth-server

> .NET Auth Server: Identity server with ASP.NET Core Identity, JWT, and OAuth2

## ✨ Features
- JWT authentication with access + refresh tokens
- Role-based access control (admin/user)
- Full CRUD with pagination, search, and filtering
- Premium responsive UI with dark/light mode
- Real-time validation and error handling
- Docker Compose for one-command startup
- Comprehensive README with API documentation
- Database migrations with Alembic/Flyway

## 🧰 Tech Stack
.NET, C#, Blazor, SQL Server, EF Core

## 🏗️ Architecture
Three-tier architecture: .NET, C# backend, native frontend, PostgreSQL database. Containerized with Docker.

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/.net-auth-server
cd .net-auth-server

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
