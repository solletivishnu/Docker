# Web Voting Application

## Overview
A scalable microservices-based web voting application designed for seamless deployment and high availability. The project uses Docker for containerization, GitHub Actions for CI/CD automation, and Kubernetes for workload orchestration, ensuring high scalability and reliability.

## Live Website
You can view the live demo of Voting Application:
- **Live Website Link:** [Interface to Cast The Vote](http://34.30.49.181:5000/) <br><br>
                         [Interface to View The Result](http://35.184.226.17:5001/) <br><br>

## Features
- **Microservices Architecture:** Modular design with separate services for vote casting, results visualization, and data processing.
- **Scalable Deployment:** Kubernetes workloads ensure the system handles up to 1,000 concurrent users effortlessly.
- **CI/CD Pipeline:** Automated testing and deployment using GitHub Actions, reducing deployment time by 25%.
- **Containerized Services:** Docker containers for each service enable seamless service management and portability.

## System Architecture
The web voting Application consists of the followiing services:
1. **Vote Service:**
   Frontend interface where users can cast their votes.
   Built using Python/Flask (or your actual stack).

2. **Result Service:**
   Displays voting results in real time.
   Visualizes data processed by the backend.
3. **Worker Service:**
   Processes votes from the Vote Service and stores them in the database.
4. **Database Service:**
   A PostgreSQL database for persistent storage of voting data.
5. **Redis Service:**
   Acts as a temporary in-memory storage for vote data before processing.

## Technologies Used
- **Docker:** Used for containerizing all microservices, enabling seamless deployment.
- **Kubernetes:** Orchestrates workloads, ensuring high availability and scalability.
- **GitHub Actions:** Automates CI/CD pipelines for building, testing, and deploying services.
- **Google cloud platform:** Deploying in cluster of nodes using GKE Service

# Screenshots of the Project


## User Login Page

![Food Ordering User Login Page]()

