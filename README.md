# 2-Tier Cloud Application Infrastructure

A two-tier cloud application deployment on AWS using Terraform, Docker, and Jenkins. This project demonstrates infrastructure provisioning, containerization, and CI/CD automation for frontend and backend services.

## Overview

The infrastructure separates frontend and backend services across dedicated EC2 instances within an AWS Virtual Private Cloud (VPC). Terraform is used to provision the infrastructure, Docker to containerize the services, and Jenkins to automate deployment through a three-stage pipeline.

## Technologies Used

- **Cloud Platform:** AWS
- **Infrastructure as Code:** Terraform
- **Compute:** Amazon EC2
- **Networking:** VPC, public and private subnets, Internet Gateway
- **Containerization:** Docker
- **CI/CD:** Jenkins
- **Scripting:** Bash

## Architecture

The project uses a two-tier architecture consisting of frontend and backend services hosted on separate EC2 instances.

- **VPC:** Provides an isolated network environment for the application.
- **Public and private subnets:** Organize resources according to their network placement.
- **Internet Gateway:** Enables internet connectivity for resources configured to use the public network.
- **Frontend EC2 instance:** Hosts the frontend service.
- **Backend EC2 instance:** Hosts the backend service.
- **Docker:** Packages application services into containers.
- **Jenkins:** Automates deployment through a three-stage pipeline.

## Deployment Workflow

1. **Infrastructure provisioning:** Terraform provisions the AWS networking and compute resources.
2. **Containerization:** Docker packages the frontend and backend services.
3. **Automated deployment:** Jenkins executes the configured three-stage pipeline.
4. **Connectivity validation:** End-to-end connectivity between the frontend and backend tiers is checked.

## Documentation

The deployment documentation is available in the PDF included in this repository.

The document covers the deployment process and supporting evidence.

## Key Learnings

- Provisioning cloud infrastructure using Terraform.
- Understanding AWS networking and two-tier application architecture.
- Containerizing application services with Docker.
- Automating deployment using Jenkins pipelines.
- Validating connectivity between application tiers.

## Future Improvements

- Add automated infrastructure teardown and cleanup.
- Integrate automated testing into the CI/CD pipeline.
- Introduce monitoring, logging, and deployment notifications.
- Improve infrastructure security through least-privilege IAM policies and restricted network access.
**Shruti Das**

[GitHub](https://github.com/Shrutidas18) · [LinkedIn](https://www.linkedin.com/in/shruti-das-8b8191247/) · [Portfolio](https://creative-portfolio-sh.vercel.app/)
