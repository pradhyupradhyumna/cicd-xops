# CI/CD Web App

This is a simple HTML app that gets deployed automatically to an EC2 instance using GitHub Actions and SSH.

## Structure
- index.html — Web page content
- .github/workflows/deploy.yml — GitHub Actions workflow (will add later)

## How It Works
When code is pushed to the `main` branch, GitHub Actions connects to the EC2 server via SSH, copies the latest code, and restarts the web server.