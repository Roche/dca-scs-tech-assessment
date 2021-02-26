# Technical assessment

This is a technical challenge to use it during hiring processess for DevOps positions.

## Introduction

In this repository there is a standalone web application in .NET Core 5.0. The application it's already _dockerized_.

## Goals

There are two main goals, go as far as you can go.

### Infrastructure

Deploy a Linux VM with Docker engine.

- Use a **free tier** from any public cloud provider
- Use any Linux distribution, but use base images without Docker already installed
- Install Docker engine
- Open service ports to the Internet
- Define as much as you can infrastructure as code
- Work as much as you can with configration management tools

### Pipeline

Build and deploy the project.

- Fork the repository, Use your favorite platform: GitHub, GitLab, BitBucket, Azure DevOps...
- Fix the errors you may find in the code
- Implement a CI/CD pipeline in your favorite CI/CD tool: GitLab, Azure DevOps, Jenkins, TravisCI...
  - Build the project in a Linux environment
  - Run project's unit tests
  - Deploy the application in the VM already provisioned

## Presentation

The solution should be shared through public repositories.
The pipeline should deploy the project and it should be accessible from the Internet.
