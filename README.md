# devops-task-1
CI/CD pipeline for Node.js app using GitHub Actions and Docker
# DevOps Task 1: CI/CD Pipeline

This repository contains the solution for the ElevateLabs DevOps Internship Task 1

## Objective
The goal was to set up a CI/CD pipeline using GitHub Actions to automatically build a Docker image for a sample Node.js web app and push it to DockerHub.

## Workflow (`.github/workflows/main.yml`)
The pipeline is defined in `.github/workflows/main.yml`  and performs the following:
1.  **Triggers** on any `push` event to the `main` branch.
2.  **Checks out** the repository code.
3.  **Logs in** to DockerHub using credentials stored securely as GitHub Actions Secrets.
4.  **Builds** the Docker image using the provided `Dockerfile`.
5.  **Pushes** the built image to my DockerHub repository.

## Application
The application is a simple "Hello, World!" Node.js/Express server.


<img width="1829" height="844" alt="Screenshot (30)" src="https://github.com/user-attachments/assets/9221fef2-7a47-4d2e-811a-f216af9090ee" />
