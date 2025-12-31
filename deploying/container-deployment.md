# Container Deployment

## Application Details
Application: [APP_NAME]
Type: [WEB_APP/API/MICROSERVICE]
Language/Framework: [TECH_STACK]

## Containerization Requirements
Base image: [BASE_IMAGE] or [AUTO_SUGGEST]
Exposed ports: [PORTS]
Environment variables: [ENV_VARS]
Dependencies: [DEPENDENCIES]

## Deployment Target
Platform: [KUBERNETES/DOCKER_SWARM/ECS/etc.]
Environment: [ENV_NAME]
Orchestration needs: [REQUIREMENTS]

## Resource Requirements
- CPU: [CPU_REQUIREMENTS]
- Memory: [MEMORY_REQUIREMENTS]
- Storage: [STORAGE_REQUIREMENTS]
- Replicas: [REPLICA_COUNT]

## Request
Help me create container deployment configuration including:
1. Dockerfile with multi-stage build
2. Docker Compose file for local development
3. Kubernetes manifests (Deployment, Service, ConfigMap, Secrets) OR equivalent for target platform
4. Health check configuration
5. Resource limits and requests
6. Volume mounts if needed
7. Networking configuration
8. Environment-specific configurations
9. Image build and push commands
10. Deployment commands

Best practices to include:
- Security (non-root user, minimal base image)
- Layer caching optimization
- Efficient image size
- Proper secret handling
- Logging configuration
