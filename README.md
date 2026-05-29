# Counter Microservice

This project is a simple REST API that manages a counter.

## Features
- Increment counter
- Basic health endpoint
- CI using GitHub Actions
- CD using OpenShift Tekton Pipelines

## Endpoints
- GET / → service status
- GET /counter → increments counter

## CI/CD
- GitHub Actions runs lint + tests
- OpenShift Tekton runs pipeline with lint, test, cleanup
