🚀 Python CI/CD Pipeline using Reusable Workflows

📌 Project Overview
This project demonstrates a production-style Python CI/CD pipeline built using GitHub Actions reusable workflows.

The pipeline automates :

✅ Code Validation

✅ Unit Testing

✅ Package Building

✅ Artifact Management

✅ Deployment Simulation


The workflow runs on a dedicated Self-Hosted Runner created exclusively for this project, providing better performance, flexibility, and environment control.

---------------------------------------------------------------------------------------------

✨ Features Implemented :

🔁 Reusable Workflows (workflow_call)

🖥️ Self-Hosted Runner

⚡ Matrix Strategy (Multiple Python Versions)

📦 Dependency Caching

🐍 Python Package Build

🧪 Automated Unit Testing using Pytest

✅ Code Quality Checks using Flake8

📁 Artifact Upload and Management

🌍 Environment Variables Configuration

-----------------------------------------------------------------------------------------

🛠️ Technologies Used :

🐍 Python : Application Development

⚙️ GitHub Actionn : CI/CD Automation

🧪 Pytest : Unit Testing

✅ Flake8 : Code Linting

📦 actions/cache : Dependency Caching

📁 Upload Artifacts : Store Build Outputs

🖥️ Self-Hosted Runner : Custom Pipeline Execution Environment

-------------------------------------------------------------------------------------------------------

📊 CI/CD Workflow :

Code Push

     ↓
   
Checkout Repository

     ↓
   
Setup Python Environment

     ↓
   
Install Dependencies

     ↓
   
Cache Dependencies

     ↓
   
Run Lint Checks

     ↓
   
Execute Unit Tests

     ↓
   
Build Python Package

     ↓
   
Upload Build Artifacts

     ↓
   
Simulate Deployment

--------------------------------------------------------------------------------------------------------

📚 Conclusion :

This project showcases how to build a scalable and reusable Python CI/CD pipeline using modern DevOps practices with GitHub Actions and Self-Hosted Runners.
