Self-Hosted DevOps Lab

This project is a self-hosted DevOps lab environment using Docker Compose. It includes the following key services:

- **Portainer:** Web UI for managing Docker containers and images.
- **Jenkins:** Continuous Integration and Continuous Delivery (CI/CD) automation server.
- **Gitea:** Lightweight Git server for hosting repositories.
- **SonarQube:** Code quality and security analysis platform.

Getting Started

Prerequisites

- Docker (version 24.x.x or higher)
- Docker Compose plugin (version 2.x.x or higher)

How to Run

1. Clone this repository:
   bash
   git clone <your-repo-url>
   cd <your-repo-folder>

2. docker compose up -d

3. Access the services in your browser:

   Portainer: http://localhost:9000

   Jenkins: http://localhost:8080

   Gitea: http://localhost:3000

   SonarQube: http://localhost:9001

Notes

  Initial account setup and configuration of each service is still pending.

  Make sure Docker daemon is running and your user has permission to run Docker commands.

Project Status

This is a work-in-progress lab environment designed for learning DevOps tools and workflows.
