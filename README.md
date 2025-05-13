**Note:** This project is a fork of the excellent `opentelemetry-demo` with additional DevOps implementations. Special thanks to the OpenTelemetry team and all contributors for creating this comprehensive demo.

<!-- markdownlint-disable-next-line -->
# 🌌 Astronomy Shop DevOps Demo

[![Version](https://img.shields.io/github/v/release/open-telemetry/opentelemetry-demo?color=blueviolet)](https://github.com/open-telemetry/opentelemetry-demo/releases)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg?color=red)](https://github.com/open-telemetry/opentelemetry-demo/blob/main/LICENSE)

## About This Implementation

This repository contains my DevOps implementation of the OpenTelemetry Astronomy Shop, enhanced with:

- **Full CI/CD Pipeline** (GitHub Actions + ArgoCD)
- **Infrastructure as Code** (Terraform)
- **Kubernetes Deployment** (EKS with Helm)
- **Containerization** (Docker)
- **Monitoring** (Prometheus + Grafana)

The original microservice-based distributed system demonstrates OpenTelemetry instrumentation in a near real-world e-commerce environment.

## Key Features

- 12+ microservices including:
  - Shopping frontend
  - Product catalog
  - Cart service
  - Payment processing
  - Fraud detection
  - Recommendation engine
- Mobile-ready (React Native)
- Feature flagging (FlagD)
- Load testing capabilities
- Envoy reverse proxy

## Deployment Options

### Quick Start

1. **Local Development**:
   ```bash
   docker-compose up
   ```

2. Kubernetes Deployment:
   helm install astronomy-shop ./charts
3.AWS Infrastructure:
  terraform apply
Technologies Used
Containerization: Docker

Orchestration: Kubernetes (EKS)

Infrastructure: Terraform

CI/CD: GitHub Actions, ArgoCD

