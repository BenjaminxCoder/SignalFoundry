# Architecture

This document explains the architecture of **SignalFoundry**.

## Overview
SignalFoundry is a **distributed, event-driven analytics platform**.

- **Go API:** Command & control layer for job creation and management.
- **RabbitMQ:** Message broker for distributing jobs and events.
- **Python Workers:** Compute features, signals, and analytics pipelines.
- **PostgreSQL:** Operational data store.

## System Diagram
![Architecture Diagram](architecture.png)

---

### Planned Scalability Features
- Horizontal scaling for API and workers
- Queue-based retry and DLQ setup
- Observability with Prometheus & Grafana