\# Ping Monitor



A real-time network monitoring system built using Prometheus, Grafana, and Blackbox Exporter to monitor network availability and performance across internet and game endpoints.



\## 🚀 Features



\- Monitors latency, packet loss, and jitter across multiple endpoints

\- Monitors internet and game-related endpoints

\- Supports ICMP and HTTP probing

\- Interactive Grafana dashboard for network health visualization

\- Tracks endpoint availability and performance over time

\- Dashboard can be accessed remotely through Cloudflare Tunnel



\## 🛠️ Tech Stack



\- Prometheus

\- Grafana

\- Blackbox Exporter

\- Cloudflare Tunnel

\- GitHub Pages



\## 📊 Monitored Endpoints



\- Cloudflare

\- Google

\- Google HTTPS

\- YouTube

\- Genshin Impact – Representative Endpoint (JP)

\- Honkai: Star Rail – Gameplay Session (JP)



\## 🌐 Live Demo



\[Open Ping Monitor](https://luxbane.github.io/pingmonitor/)



> GitHub Pages provides the public landing page. The monitoring stack runs locally and is exposed through Cloudflare Tunnel when the monitoring environment is active.



\## 📁 Project Files



\- `prometheus.yml` — Prometheus configuration

\- `blackbox.yml` — Blackbox Exporter configuration

\- `Home ICMP Monitoring-1789914100579.json` — Grafana dashboard export

\- `index.html` — GitHub Pages landing page

\- `config.json` — project configuration

\- `.gitignore` — excludes local installations and runtime data



\## 📖 Overview



This project was developed as a practical network monitoring lab to analyze latency, packet loss, jitter, and endpoint availability in real-time.



The monitoring stack uses Prometheus to collect metrics, Blackbox Exporter to perform ICMP and HTTP probes, and Grafana to visualize the collected data through an interactive dashboard.

