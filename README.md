# WordPress on Kubernetes with Persistent MySQL Storage
# Project Overview

This project demonstrates a **production-ready WordPress deployment on Kubernetes** with a focus on **stateful workloads and data persistence**.

**Frontend**: WordPress

**Backend**: MySQL

**Storage**: Persistent Volumes (PV) + Persistent Volume Claims (PVC)

**Secrets**: Kubernetes Secrets for secure password management

**Networking**: Kubernetes Services for internal communication

**Goal**: Showcase hands-on Kubernetes expertise in deploying stateful applications, securing credentials, and ensuring data survives pod lifecycle events.

# Key Features

Deploy WordPress as a **frontend pod** connected to a **MySQL backend pod**

Use **PV & PVC** to persist MySQL database data

Secure credentials with **Kubernetes Secrets**

Enable internal pod-to-pod communication with **Services**

Validate **data persistence** even after MySQL pod deletion/recreation

Showcase **real-world Kubernetes architecture** for production apps

# Future Improvements

Convert MySQL to **StatefulSet**

Add **ConfigMaps** for WordPress configuration

Implement **Ingress** Controller

Add **Readiness & Liveness probes**

Add **GitHub Actions CI/CD pipeline**
