# Academic Backend Project – Dockerized Application with MongoDB Replica Set

This project is an academic application developed as part of my Software Development Technology program.  
Its main purpose is to **dockerize an application and test database resilience** using a **MongoDB replica set**.

---

## Tech Stack

- MongoDB (Primary / Secondary replica set)
- Docker
- Docker Compose
- HTML
- CSS
- JavaScript

---

## Project Objective

The goal of this project is to simulate a resilient database environment by deploying a **MongoDB replica set** using Docker Compose.

The application is designed so that:
- One MongoDB instance acts as the **primary node**
- Another instance acts as the **secondary node**
- If the primary database goes down, the secondary node continues to serve the application

This setup helps demonstrate **basic fault tolerance and data availability concepts** in a containerized environment.

---

## Features

- Dockerized backend application
- MongoDB replica set (primary and secondary nodes)
- Automatic failover testing between database instances
- Web-based interface using HTML, CSS, and JavaScript
- Container orchestration using Docker Compose

---

## How to Run the Project

> Note: This project was developed for academic purposes.

1. Clone the repository:
  git clone https://github.com/Bayron077/JARDIN-KAJUBVA.git
2. Navigate to the project directory:
  cd JARDIN-KAJUBVA
3. Start the application and database containers:
   docker-compose up
4. The application will connect to the MongoDB replica set automatically.
5. To test resilience, you can stop the primary database container and verify that the application continues running using the secondary node.

##Learning Outcomes

Through this project, I gained practical experience in:
-Containerization using Docker and Docker Compose.
-Configuring MongoDB replica sets.
-Understanding basic database resilience and fault tolerance concepts.
-Working with distributed systems concepts at an introductory level.

## Author
Bayron Castellanos
Software Development Technology Student.
Open to junior, trainee, or internship opportunities.
   

