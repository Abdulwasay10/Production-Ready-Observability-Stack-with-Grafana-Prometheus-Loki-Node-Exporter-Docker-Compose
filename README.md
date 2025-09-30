### 🚀 Centralized Observability Stack with Grafana, Loki, Promtail, Prometheus & Node Exporter

This project demonstrates a full logging and monitoring pipeline using modern open-source observability tools. It collects application logs, system metrics, and container metadata and visualizes them through Grafana dashboards.

## 📌 Features

- Grafana (v11.6.0) – Dashboarding and visualization

- Prometheus – Metrics scraping and time-series database

- Node Exporter – System-level metrics collection

- Loki – Centralized log storage with retention policy (72h)

- Promtail – Log shipping from Docker containers & Nginx logs, enriched with metadata (container name, ID, image, project, service)

- OpenTelemetry – Application metrics exposed via /metrics endpoint

- Docker Compose – Easy one-command setup


## 🚀 Getting Started

1. Clone the repo:

   ```bash
   git clone https://github.com/Abdulwasay10/Production-Ready-Centralized-Observability-Socker-Stack.git
   cd Production-Ready-Centralized-Observability-Socker-Stack
   ```

2. Start the stack:

   ```bash
   docker-compose up -d
   ```

3. Access services:

- Grafana → http://localhost:3101

- Prometheus → http://localhost:9090

- Loki → http://localhost:3100

- Node Exporter → http://localhost:9100

4. 📊 Grafana Dashboards

Logs filtered by container names / services / projects

System metrics (CPU, memory, disk, network)

Application telemetry via /metrics

5. Why This Project?

1. This setup simulates a production-ready observability stack:

2. Logs + Metrics in one place (Loki + Prometheus)

3. Enriched logs with container metadata

Dashboards that help debug across apps, infra, and logs

Easy to replicate for any environment using Docker Compose
