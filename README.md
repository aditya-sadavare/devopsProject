# End-to-End Web Application Deployment Using Docker, Jenkins, and AWS EC2  

## **Project Overview**  
This project demonstrates a **fully automated CI/CD pipeline** for deploying a Node.js web application on AWS EC2. The workflow integrates **Jenkins** for continuous integration, **Docker** for containerization, and **AWS EC2** for cloud deployment.  

---

## **Key Features**  
- **CI/CD Pipeline**: Automated code fetching, building, and deployment using Jenkins.  
- **Dockerization**: Containerized the Node.js application for environment consistency.  
- **AWS Deployment**: Scalable infrastructure setup with Jenkins and Docker on AWS EC2.  

---

## **Technologies Used**  
- **Core Technologies**: Node.js, Docker, Jenkins, AWS EC2  
- **Tools**: Git & GitHub, Docker Compose, Postman (API testing), VS Code  

---

## **Project Demo**  
Click the image below to watch the demo video:  

[![Watch the video](https://img.youtube.com/vi/1gmm0ISbwNA/maxresdefault.jpg)](https://www.youtube.com/watch?v=1gmm0ISbwNA)  

---

## ** "We have stopped our EC2 service because it is a free-tier account, so the site is currently not visible. However, we can start it anytime if needed. Proof of EC2 instance status is attached." **

# Run Locally

## 1. Install Docker
- Download and install [Docker](https://www.docker.com/get-started).
- Verify installation:
  ```sh
  docker --version
## 2. Set Up Your Jenkins Pipeline

1. Create a New Pipeline
In Jenkins, click on New Item, enter a name, select Pipeline, and click OK.

2. Configure Pipeline:
1)Scroll to the Pipeline section.
2)Set Definition to Pipeline script.
3)Paste your pipeline script (Jenkinsfile) that utilizes Docker Compose.
4) Build pipeline.
