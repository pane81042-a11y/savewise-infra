# SaveWise Infra

SaveWise Infra contains infrastructure, deployment, environment, and automation support for the SaveWise platform.

It is intended to centralize deployment workflows, Docker configuration, CI/CD automation, and environment templates for the full modular architecture.

## Features

- Environment variable templates
- Docker and container setup
- CI/CD workflow configuration
- Deployment documentation
- Infrastructure support files
- Production readiness foundation

## Getting Started

### 1. Clone the repository
```bash
git clone <your-savewise-infra-repo-url>
cd savewise-infra
```
### 2. Install dependencies if needed
```bash
npm install
```
### 3. Review environment templates and deployment configuration
Update the provided templates for your local, staging, and production environments.
### Scripts
```bash
npm run lint
npm run validate
```

## Purpose
This repository helps manage infrastructure concerns separately from product code while supporting a clean and scalable engineering workflow.

## Related Repositories
- SaveWise Client
- SaveWise API
- SaveWise Auth Service
- SaveWise Shared
- SaveWise UI
