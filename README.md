# CI-CD-Pipeline-to-Deploy-Node.js-Application
Automated deployment of a Node.js application using AWS CodePipeline, CodeBuild, and EC2/S3 for continuous delivery.

## 🎯 Purpose

The purpose of this project is to implement a CI/CD (Continuous Integration and Continuous Deployment) pipeline for automatically deploying a Node.js application whenever code changes are pushed to the repository.

This automation helps in:

* Faster application deployment
* Reducing manual deployment effort
* Continuous integration of new code changes
* Continuous delivery of updated application versions
* Improving development and deployment workflow efficiency

## 🧰 AWS Services Used

* **AWS CodePipeline** – Used to automate the CI/CD workflow.
* **AWS CodeBuild** – Used for building and testing the Node.js application.
* **Amazon EC2 / Amazon S3** – Used for hosting and deploying the application.

## 📸 Project Screenshots

### 1. CodePipeline
This shows the CI/CD pipeline workflow.
![Pipeline](CodePipeline.png)

### 2. S3 Buckets
This shows deployment artifacts stored in Amazon S3.
![S3](S3%20Buckets.png)

## 📂 Project Files

### Node.js Application File
[View app.js](app.js)

### Build Specification
[View buildspec.yml](buildspec.yml)

### Frontend File
[View index.html](index.html)

### Package Configuration
[View package.json](package.json)
