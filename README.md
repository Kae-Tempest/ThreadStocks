# threadStocks - Cross-stitch Thread Inventory Manager

A full-stack application designed to help cross-stitch enthusiasts manage their thread inventory (DMC, Anchor, etc.). Track stock quantities, avoid duplicate purchases, and plan requirements for future projects.

## 📂 Project Structure

This repository is a monorepo containing both the backend and frontend:

- **[api/](./api)**: Backend API built with Go (Golang), PostgreSQL, and GORM.
- **[web/](./web)**: Frontend application built with Vue 3, Vite, and Tailwind CSS.
- **[docker/](./docker)**: Docker configuration for local development (PostgreSQL).
- **[haproxy/](./haproxy)**: HAProxy configuration for load balancing/routing.

## 🛠 Tech Stack

### Backend
- **Language**: [Go (Golang)](https://golang.org/)
- **Database**: [PostgreSQL](https://www.postgresql.org/)
- **ORM**: [GORM](https://gorm.io/)
- **Auth**: JWT (JSON Web Tokens) with Bcrypt hashing.
- **Observability**: OpenTelemetry.

### Frontend
- **Framework**: [Vue 3](https://vuejs.org/) (Composition API)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **State Management**: [Pinia](https://pinia.vuejs.org/)
- **Routing**: [Vue Router](https://router.vuejs.org/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)

## 🚀 Getting Started

### Prerequisites
- [Docker](https://www.docker.com/) and [Docker Compose](https://docs.docker.com/compose/)
- [Go](https://golang.org/dl/) (if running API locally without Docker)
- [Node.js](https://nodejs.org/) (if running Web locally without Docker)

### Local Development with Docker

1. Clone the repository:
   ```bash
   git clone https://github.com/Kae-Tempest/threadStocks.git
   cd threadStocks
   ```

2. Start the services:
   ```bash
   docker-compose up -d
   ```

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.