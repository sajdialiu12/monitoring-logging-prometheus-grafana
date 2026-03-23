# Monitoring & Logging Stack (Prometheus + Grafana)

## Overview
This project is a full monitoring stack using Docker Compose:
- **Prometheus** for metrics collection
- **Grafana** for dashboards
- **Node Exporter** for system metrics

## Services & URLs
- Prometheus → http://localhost:9090  
- Grafana → http://localhost:8080 (default login: `admin` / `admin`)  
- Node Exporter → http://localhost:9100/metrics

## Setup Instructions
1. Clone the repository:
```bash
git clone git@github.com:sajdialiu12/monitoring-logging-prometheus-grafana.git
cd monitoring-logging-prometheus-grafana
