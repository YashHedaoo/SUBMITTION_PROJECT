
Assignment: MEAN Stack DevOps Deployment Project for DevOps Internship 

Overview
This project demonstrates the end-to-end deployment of a full-stack **MEAN (MongoDB, Express, Angular, Node.js)** application using modern DevOps practices.
The application is containerized using Docker, orchestrated using Docker Compose, deployed on AWS EC2, and automated with a CI/CD pipeline using GitHub Actions.

## 🛠️ Tech Stack

* **Frontend:** Angular
* **Backend:** Node.js, Express
* **Database:** MongoDB
* **Containerization:** Docker
* **Orchestration:** Docker Compose
* **CI/CD:** GitHub Actions
* **Cloud Platform:** AWS EC2
* **Web Server:** Nginx

##  Architecture

```
User → Nginx (Port 80)
        ↓
Frontend (Angular)
        ↓
Backend (Node.js API)
        ↓
MongoDB Database
```


##  Features Implemented

* Dockerized frontend and backend applications
* Multi-container setup using Docker Compose
* MongoDB integration using a container
* Nginx reverse proxy configuration
* CI/CD pipeline for automated build and deployment
* Deployment on AWS EC2 instance
* Auto-deployment using GitHub Actions and SSH

##  Setup 

###  1. Clone Repository

```
git clone [https://github.com/YashHedaoo/<your-repo-name>.git](https://github.com/YashHedaoo/SUBMITTION_PROJECT.git)
cd SUBMITTION_PROJECT
```

---

###  2. Run Application Locally

```
docker-compose up -d --build
```

---

### 🔹 3. Access Application

```
http://localhost
```

---

##  Cloud Deployment (AWS EC2)

###  Steps:

1. Launch an Ubuntu EC2 instance
2. Install Docker & Docker Compose
3. Clone repository
4. Run:

```
docker-compose up -d
```

### 🔹 Access:

```
http://<EC2-PUBLIC-IP> ## Not provided because I terminate it after using. I am a free-tier user 
```

---

##  CI/CD Pipeline

###  Workflow:

* Triggered on every push to the main branch
* Builds Docker images
* Pushes images to Docker Hub![Uploading Screenshot 2026-02-24 at 14.50.42.png…]()

* Connects to

## Some Screenshots

