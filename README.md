# cloud-platform-project
# Cloud Monitoring & Alerting System (Azure VM + Prometheus + Grafana)

## Overview
This project implements a cloud-based infrastructure monitoring and alerting system deployed on an Azure Linux Virtual Machine. It provides real-time observability of system performance and automated alerting for infrastructure health.

## Architecture
Azure VM → Node Exporter → Prometheus → Grafana → Alert Manager → Email Notifications

## Key Features
- Real-time system metrics collection using Node Exporter
- Metric scraping and storage using Prometheus
- Visualization dashboards built with Grafana
- Automated alerting based on system load thresholds
- Email notification integration via Grafana contact points
- Custom evaluation groups for alert routing

## Alerting Logic
- Monitors system load (node_load1 metric)
- Triggers alert when load exceeds threshold (value > 2)
- Sends notification via configured email contact point
- Supports alert state transitions (Normal → Alert → Resolved)

## Tech Stack
- Azure Virtual Machine (Ubuntu 22.04 LTS)
- Prometheus
- Grafana
- Node Exporter
- Git & GitHub

## Outcome
This system demonstrates how production-grade monitoring pipelines are built for cloud infrastructure, enabling proactive detection of system stress and performance issues.

## Author
Muhammed Olalekan Umar
Cloud / DevOps Engineering Project

