# End-to-End Monitoring & Observability Platform (Prometheus + Grafana)

This project is a simple but complete observability setup built around Prometheus and Grafana. It is designed to monitor Linux-based systems and collect basic infrastructure metrics in a containerized environment.

The goal of this setup is to simulate a real-world monitoring stack that can be used for small to medium Linux infrastructures.

---

## What this project includes

- Prometheus for metrics collection and storage  
- Grafana for visualization and dashboards  
- Node Exporter for system-level metrics  
- Docker Compose for easy deployment  

---

## Why this setup

In most environments, having visibility over system health is critical. This setup focuses on:

- Basic infrastructure monitoring
- CPU, memory, disk, and system load metrics
- Simple alerting rules (expandable later)
- Easy local deployment using Docker

---

## Architecture

The setup is straightforward:

- Node Exporter exposes system metrics
- Prometheus scrapes and stores metrics
- Grafana visualizes the data

Everything runs as Docker containers.

---

## How to run it

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/observability-platform-prometheus-grafana.git
cd observability-platform-prometheus-grafana
