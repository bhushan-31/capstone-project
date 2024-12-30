# Simplilearn_Capstone_EasyPay-Payment
JFSD: Capstone Project

# EasyPay Payment Application

## Overview

The EasyPay Payment Application is a scalable and high-availability e-wallet payment system designed for e-commerce platforms. This project implements best practices in DevOps to ensure smooth payment processing even during high traffic periods. The application uses Angular for the front-end, Spring Boot for the back-end, MySQL for the database, and Jenkins for continuous integration and deployment. The system is deployed on AWS using Docker containers for easy scaling and management.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Technologies Used

- **Angular**: Front-end framework for building dynamic, responsive user interfaces.
- **Java & Spring Boot**: Back-end framework for creating REST APIs and handling business logic.
- **MySQL**: Database for managing user and transaction data.
- **Docker**: Containerization platform for packaging and deploying applications.
- **AWS EC2**: Cloud hosting for the application.
- **Jenkins**: Automates the build, testing, and deployment process.
- **Git & GitHub**: Version control for code management and collaboration.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Features

- **Admin Interface**: Admins can add and manage restaurants and dishes.
- **User Interface**: Users can browse restaurants, select dishes, and manage their orders.
- **CI/CD Pipeline**: Automates the process of building and deploying both the front-end and back-end applications.
- **Containerization**: Both the Angular and Spring Boot applications are containerized using Docker.
- **Scalability**: Kubernetes on AWS ensures that the system can scale based on demand.
- **High Availability**: The system is designed for fault tolerance and minimal downtime.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone [https://github.com/Kaushikwagh/Simplilearn_Capstone_EasyPay-Payment.git]

2. Set up the MySQL database with the required tables:
  Create a MySQL database and tables for users, transactions, and orders.

3.Dockerize both the front-end and back-end applications:
  Use the provided Dockerfile for both Angular and Spring Boot applications.
  Build the Docker images:

  docker build -t easypay-frontend .
  docker build -t easypay-backend .

4. Set up the Jenkins pipeline:
  Configure Jenkins to automatically build and deploy the applications on code changes.

5. Deploy on AWS:
  Launch EC2 instances and deploy the containerized applications using AWS ECS or Kubernetes.

6. Test the application:
  Use Apache JMeter or another load-testing tool to simulate traffic and verify scalability.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

Project Structure

/easypay
│
├── /frontend         # Angular front-end application
├── /backend          # Spring Boot back-end application
├── /database         # MySQL schema and migration scripts
├── Dockerfile        # Dockerfile for the Angular application
├── Jenkinsfile       # Jenkins pipeline configuration
├── README.md         # Project documentation
└── .gitignore        # Git ignore file

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
<img width="729" alt="Screenshot 2024-12-27 at 8 07 49 PM" src="https://github.com/user-attachments/assets/2e3d680e-d5d2-4ca2-81dc-8e17b93b929e" />
<img width="831" alt="Screenshot 2024-12-27 at 8 07 36 PM" src="https://github.com/user-attachments/assets/f47e345e-c775-4323-a982-950dbbb2b400" />
<img width="808" alt="Screenshot 2024-12-27 at 8 07 26 PM" src="https://github.com/user-attachments/assets/dd566e20-d6ba-4a18-8bc7-8f7468157430" />
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
