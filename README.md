# Grafana and Prometheus Monitoring Setup

## Overview

This repository contains the setup for a monitoring system using Grafana and Prometheus for a Node.js project. The system is containerized using Docker and Docker-Compose to simplify deployment and management.

## Objective

To investigate, install, and configure Grafana and Prometheus to establish a monitoring system for a Node.js software project.

## Prerequisites

- Docker
- Docker-Compose
- Node.js

## Installation and Configuration

### 1. Preliminary Investigation

- **Grafana**: An open-source platform for monitoring and observability that provides visualizations, alerts, and queries.
- **Prometheus**: An open-source monitoring system that collects metrics from configured targets at intervals, evaluates rule expressions, displays results, and can trigger alerts.

### 2. Installing Docker and Docker-Compose

1. **Install Docker**:
   Follow the [official Docker installation guide](https://docs.docker.com/get-docker/).

2. **Install Docker-Compose**:
   Follow the [official Docker-Compose installation guide](https://docs.docker.com/compose/install/).

3. **Verify Installation**:
   ```bash
   docker --version
   docker-compose --version
