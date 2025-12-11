System Architecture Overview

Frontend: React + Vite

Backend API: Spring Boot (REST + WebFlux optional)

Database: PostgreSQL

Cache Layer: Redis (content cache + user-session + trending)

Message Broker: Kafka (event-driven architecture)

Storage: Local FS / S3-compatible (media uploads)

Deployment: Docker + Kubernetes

CI/CD: GitHub Actions

User → Frontend → Backend API → PostgreSQL
                        ↓
                      Redis
                        ↓
                      Kafka → Consumers (Recommendation Engine)