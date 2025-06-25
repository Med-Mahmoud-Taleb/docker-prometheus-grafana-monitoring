# 📊 Linux Server Monitoring with Prometheus & Grafana (Docker-Based)

This mini-project demonstrates a complete containerized monitoring stack using **Prometheus**, **Node Exporter**, and **Grafana** via Docker Compose.

It’s designed for Linux system administrators, DevOps engineers, and anyone who wants to monitor server metrics (CPU, memory, disk, network) in real time with minimal setup effort.

---

## 🚀 What’s Included

✅ Docker Compose setup for Prometheus, Node Exporter, and Grafana  
✅ Pre-configured Prometheus to scrape metrics from Node Exporter  
✅ Grafana auto-configured with Prometheus as data source  
✅ Ready-to-import dashboards (e.g. Node Exporter Full - ID: `1860`)  
✅ Clean, production-ready project structure

---

## 🧰 Technologies Used

- [Prometheus](https://prometheus.io) – Time-series monitoring system  
- [Node Exporter](https://github.com/prometheus/node_exporter) – OS-level metrics exporter  
- [Grafana](https://grafana.com) – Visualization and alerting platform  
- [Docker Compose](https://docs.docker.com/compose/) – Container orchestration

---

## 📦 Project Structure

```bash
docker-prometheus-grafana-monitoring/
├── docker-compose.yml
├── prometheus/
│   └── prometheus.yml
├── grafana/
│   └── provisioning/
│       └── datasources/
│           └── prometheus.yml
└── README.md```

## 🌐 Access URLs

| Service       | URL                                                            | Login (default)   |
| ------------- | -------------------------------------------------------------- | ----------------- |
| Prometheus    | [http://localhost:9090](http://localhost:9090)                 | N/A               |
| Node Exporter | [http://localhost:9100/metrics](http://localhost:9100/metrics) | N/A               |
| Grafana       | [http://localhost:3000](http://localhost:3000)                 | admin / admin     |


