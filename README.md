# Mission 6: The Cloud Deployment Engineer

## Mission Overview

This mission focuses on deploying a multi-tier private cloud storage application using Nextcloud, MariaDB, Docker, and Docker Compose.

## Objectives

- Understand multi-tier application architecture.
- Create a docker-compose.yml configuration.
- Deploy Nextcloud and MariaDB using Docker Compose.
- Practice Infrastructure as Code (IaC).
- Document the deployment process.

## Commands Executed

```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down
