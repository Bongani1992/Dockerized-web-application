# Dockerized Web Application with Jenkins CI/CD

## Overview

This project demonstrates the implementation of a containerized web application using Docker and Nginx, integrated with a Jenkins Continuous Integration and Continuous Deployment (CI/CD) pipeline.

The objective is to showcase modern DevOps practices by automating application build and deployment processes while maintaining version control through GitHub.

---

## Key Features

* Containerized web application
* Nginx web server deployment
* Docker image management
* Jenkins CI/CD automation
* Source code management with GitHub
* Automated application deployment
* Infrastructure-ready architecture

---

## Technologies Used

### DevOps Tools

* Docker
* Docker Compose
* Jenkins
* Git
* GitHub

### Web Technologies

* HTML5
* CSS3
* JavaScript

### Operating System

* Linux

### Web Server

* Nginx

---

## Project Architecture

```text
Developer
    │
    ▼
GitHub Repository
    │
    ▼
Jenkins Pipeline
    │
    ▼
Docker Image Build
    │
    ▼
Docker Container
    │
    ▼
Nginx Web Server
    │
    ▼
Web Application
```

---

## CI/CD Workflow

The Jenkins pipeline automates the software delivery process by:

* Retrieving source code from GitHub
* Building a Docker image
* Validating the build process
* Deploying the application container
* Reporting deployment status

This approach ensures consistency, repeatability, and faster delivery of application updates.

---

## Project Structure

```text
dockerized-web-app/
│
├── app/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── Dockerfile
├── docker-compose.yml
├── Jenkinsfile
└── README.md
```

---

## Learning Outcomes

Through this project, the following DevOps concepts are demonstrated:

* Application containerization
* Continuous Integration
* Continuous Deployment
* Infrastructure automation fundamentals
* Version control best practices
* Container orchestration preparation
* Deployment pipeline management

---

## Future Improvements

* Docker Hub Integration
* Security Scanning
* Kubernetes Deployment
* AWS Infrastructure Deployment
* Terraform Automation
* Prometheus Monitoring
* Grafana Dashboards
* Automated Testing Integration

---

## Author

Bongani Nyapule

GitHub: https://github.com/Bongani1992

LinkedIn: https://www.linkedin.com/in/bongani-nyapule-04869558
