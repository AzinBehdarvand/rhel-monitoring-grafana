# 🖥️ RHEL Monitoring with Prometheus + Grafana on Google Cloud

This project demonstrates how to deploy a monitoring stack on a RedHat Linux VM in GCP using:

- Prometheus for time-series monitoring
- Node Exporter to expose system metrics
- Grafana for visualizing metrics

## 🔧 Tools Used

- Google Cloud Platform (GCP)
- RedHat Enterprise Linux 9 VM
- Prometheus
- Node Exporter
- Grafana

---

## 🚀 How It Works

1. A RHEL 9 VM is created on GCP.
2. Node Exporter is installed to expose metrics at `:9100/metrics`.
3. Prometheus is configured to scrape metrics from `localhost:9100`.
4. Grafana is installed on the same VM and connected to Prometheus as a data source.
5. A ready-made dashboard (ID `1860`) is imported to visualize metrics like CPU, Memory, Disk I/O, and Network.

---

## 📊 Screenshots

![Grafana Dashboard](images/grafana-dashboard.png)
![Node Exporter](images/node-exporter.png)

---

## 💡 Observability Outcome

This stack enables real-time insights into VM performance and system health. It reflects an on-premises-like environment in a cloud context — replicating exactly what Platform Engineers and Infra teams deal with daily.

---

## 🛡️ Designed For

- Platform Engineering Interviews
- Infrastructure Monitoring Showcases
- GitHub Portfolio Projects
