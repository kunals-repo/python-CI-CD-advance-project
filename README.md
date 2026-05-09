Python CI/CD Pipeline using Reusable Workflows

📌 Project Overview
This project demonstrates a production-style Python CI/CD pipeline built using GitHub Actions reusable workflows. The pipeline automates code validation, testing, package building, and artifact management using modern DevOps practices.

The workflow runs on a dedicated self-hosted runner created exclusively for this project, providing better performance, flexibility, and environment control.

🚀 Features Implemented

Reusable Workflows (workflow_call)

Self-Hosted Runner

Matrix Strategy (Multiple Python Versions)

Dependency Caching

Python Package Build

Automated Unit Testing using Pytest

Code Quality Checks using Flake8

Artifact Upload and Management

Environment Variables Configuration

🛠️ Technologies Used
Technology	
Python : Application Development

GitHub Actions : CI/CD Automation

Pytest : Unit Testing

Flake8 : Code Linting

actions/cache : Dependency Caching

Upload Artifacts : Store Build Outputs

Self-Hosted Runner : Custom Pipeline Execution Environment


📊 CI/CD Workflow

Checkout Repository

Setup Python Environment

Install Dependencies

Cache Dependencies

Run Lint Checks

Execute Unit Tests

Build Python Package

Upload Build Artifacts

Simulate Deployment Stage

🎯 Key Learning Outcomes

GitHub Actions Reusable Workflows

CI/CD Pipeline Automation

Python Testing & Linting

Matrix Strategy Implementation

Dependency Caching

Artifact Management

Self-Hosted Runner Configuration

Enterprise DevOps Best Practices
    
