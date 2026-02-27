# azure-devops-zero-downtime-
Implementation of CI/CD pipeline using Azure DevOps with Blue-Green deployment strategy on Azure App Service to achieve zero-downtime releases using deployment slots.


📌 Project Overview

This project demonstrates the implementation of a CI/CD pipeline using Azure DevOps to deploy an application to Azure App Service using Deployment Slots.

The objective of this project is to achieve Zero-Downtime Deployment using a Blue-Green strategy.

Instead of deploying directly to production, the application is first deployed to a staging slot. After validation and manual approval, a slot swap operation is performed to move the new version to production without service interruption.


🎯 Key Features

CI/CD pipeline using YAML

Self-hosted Azure DevOps Agent

Deployment to Staging Slot

Manual Approval before Production

Slot Swap for Zero-Downtime

Easy Rollback Strategy

🚀 Deployment Flow

Code Commit

Build & Package

Deploy to Staging Slot

Manual Approval

Swap Staging with Production

Result:

No downtime

Safe release process

Controlled production deployment


<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/ac9ba760-ccb7-4154-a853-c6ddb33a5fd1" />







