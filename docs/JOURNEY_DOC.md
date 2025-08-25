# SignalFoundry Journey Document

Welcome to the **SignalFoundry Journey Doc** — a detailed log of the project’s development, design decisions, sprints, technical learnings, and roadmap.  
This file demonstrates our **engineering rigor** and serves as a showcase for recruiters, teammates, and collaborators.

---

## 📚 Table of Contents
1. [Introduction](#introduction)
2. [Sprint Log](#sprint-log)
3. [Roadmap & Features](#roadmap--features)
4. [Architecture & Diagrams](#architecture--diagrams)
5. [Lessons Learned & Technical Insights](#lessons-learned--technical-insights)
6. [References & Resources](#references--resources)

---

## 📂 Related Docs
- [architecture.md](architecture.md)
- [features.md](features.md)
- [sprints/sprint-1.md](sprints/sprint-1.md)
- [sprints/sprint-2.md](sprints/sprint-2.md)
- [resources.md](resources.md)

---

## Introduction
SignalFoundry is an event-driven analytics platform built to showcase **real-world engineering skills**:  
- Scalable distributed system design  
- Job orchestration with RabbitMQ  
- Analytics computation pipelines (Python)  
- High-performance APIs (Go)  
- Observability, documentation, and CI/CD best practices

This document captures **our entire engineering journey** — sprints, experiments, design trade-offs, and technical mastery.

---

## Sprint Log

### Sprint 1: Foundation (Aug 23 – Aug 29, 2025)
**Goal:** Deliver a minimal working pipeline: API publishes a job → RabbitMQ routes → Python worker consumes → PostgreSQL stores data.

**Key Tasks:**
- ✅ Repo scaffold (.gitignore, .env.example, README)
- 🔄 Docker Compose setup (Postgres, RabbitMQ)
- 🔄 Initial DB migrations
- 🔄 API `/health` endpoint

---

## Roadmap & Features

- [x] Repo scaffold & documentation structure  
- [ ] Docker Compose infrastructure  
- [ ] RabbitMQ queue setup  
- [ ] Python worker with feature computation  
- [ ] API endpoints for job creation & retrieval  
- [ ] Observability (Prometheus + Grafana)  
- [ ] Authentication and security features  
- [ ] Backtesting and analytics reporting  
- [ ] CI/CD pipelines for Go and Python services  

---

## Architecture & Diagrams
*(Will include system diagrams here)*

- Go API (command & control)
- RabbitMQ message broker
- Python analytics workers
- PostgreSQL database

---

## Lessons Learned & Technical Insights
This section will grow as we reflect on:
- Design trade-offs and architecture decisions
- Scaling strategies
- Testing approaches
- Observability practices

---

## References & Resources
- Go standard library, chi router
- RabbitMQ official docs
- PostgreSQL best practices
- Python (pandas, NumPy)