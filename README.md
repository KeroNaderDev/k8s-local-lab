# ☸️ K8s Local Lab — Demo

Local Kubernetes lab for learning deployments

> **DevOps Track — Demo Showcase** | **Real Problem, Synthetic Data**

## Overview
**Problem:** Learning K8s needs a safe local lab

**Solution:** Local Kubernetes lab for learning deployments This demo proves the engineering approach with synthetic data.

## Architecture
```
Code → Docker → Kind/k3d → K8s → Dashboard
```

## Tech Stack
- Kubernetes, Docker, Helm

## Features
- Kind cluster\n- Helm charts\n- Autoscaling demo

## Security
- Validation, JWT/RBAC, Rate limiting, No real secrets

## Screenshots
![Demo](./screenshots/demo.png)

## Demo
- **Demo Data:** `demo-data.json`
- **Live:** `https://kero.10001mb.com/demo/k8s-local-lab-demo` *(placeholder)*

## Installation
```bash
git clone https://github.com/KeroNaderDev/k8s-local-lab-demo.git
cd k8s-local-lab-demo
npm install
cp .env.example .env
npm run dev
```

## Usage
```bash
npm run dev
```

## What I Learned
- DevOps end-to-end design
- Demo vs real data separation
- Professional portfolio structure

---
*Track: DevOps • Portfolio: [KeroNaderDev](https://github.com/KeroNaderDev)*
