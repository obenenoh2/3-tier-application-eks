# 3-Tier Application on Amazon EKS

## Overview
This project deploys a complete 3-tier .NET application on Amazon EKS.

## Architecture
- Frontend: Nginx (UI)
- Backend: .NET 7 API
- Database: PostgreSQL 15

## Deployment
See the Kubernetes manifests in the `k8s/` directory.

## Access
- URL: http://3tier.kingsly.eks.ironlabs.online
- API: http://3tier.kingsly.eks.ironlabs.online/api/user
