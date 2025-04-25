# 📊 Analytics API

An Analytics API built with **FastAPI** and **TimescaleDB** (PostgreSQL for time-series data).  
This project is containerized with Docker for easy local development and deployment.

---

## 🚀 Getting Started

### Prerequisites

- Docker
- Docker Compose

### 📦 Build & Run with Docker (single container)

> For one-off builds and tests without `docker-compose`

```bash
docker build -t analytics-api -f Dockerfile.web .
docker run analytics-api
