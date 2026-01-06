# WordPress on Kubernetes with Persistent MySQL Storage
# Project Overview

This project demonstrates deploying a production-style WordPress application on Kubernetes, focusing on data persistence using Persistent Volumes (PV) and Persistent Volume Claims (PVC).

The application architecture follows a real-world cloud-native pattern:

WordPress runs as the frontend application

MySQL runs as the backend database

Kubernetes Services enable secure internal communication

Kubernetes Secrets protect sensitive credentials

Persistent Storage (PV & PVC) ensures database data survives pod restarts

🎯 Primary Goal: To clearly showcase how stateful applications like MySQL achieve data persistence in Kubernetes using PV & PVC, which is a critical real-time production requirement.

# Future Improvements

Convert MySQL to StatefulSet

Add ConfigMaps for WordPress configuration

Implement Ingress Controller

Add Readiness & Liveness probes

