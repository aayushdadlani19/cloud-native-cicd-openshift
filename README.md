# Cloud-Native CI/CD Pipeline Automation on OpenShift

## Overview
Designed and implemented an enterprise-grade CI/CD pipeline on OpenShift using GitHub Actions, Tekton Pipelines, Kubernetes, and Buildah to automate application build, testing, containerization, and deployment workflows.

## Key Features

- Automated CI/CD pipeline using GitHub Actions and Tekton
- Container image builds with Buildah
- Kubernetes/OpenShift deployment automation
- Automated testing and validation stages
- Secure image management
- Infrastructure-as-Code workflow
- Reduced manual deployment effort by 80%
- Faster and reliable release cycles

## Architecture

GitHub Repository
      │
      ▼
GitHub Actions
      │
      ▼
Tekton Pipeline
      │
 ┌────┴────┐
 ▼         ▼
Buildah   Tests
 │
 ▼
Container Registry
 │
 ▼
OpenShift Cluster

## Tech Stack

- OpenShift
- Kubernetes
- Tekton Pipelines
- GitHub Actions
- Buildah
- Docker
- Python
- YAML
- Linux
- Git

## Project Outcomes

- Reduced deployment effort by 80%
- Automated build and deployment lifecycle
- Improved deployment consistency
- Enhanced DevOps productivity

## Repository Structure

```text
.github/workflows/   # GitHub Actions Workflow
.tekton/             # Tekton Pipeline Tasks
service/             # Application Source Code
tests/               # Test Cases
Dockerfile           # Container Build Definition
requirements.txt     # Python Dependencies
