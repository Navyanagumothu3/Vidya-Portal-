🎯 Project Overview

VidyaPortal is a responsive academic web portal front-end designed for students, faculty, and administrators.
It provides login pages, dashboards, notifications, and course materials using HTML, CSS, and JavaScript.

Problem Statement: Deploy a containerized front-end web application using Docker and Kubernetes, hosted on Cloud

<img width="1893" height="853" alt="{9821B863-3707-4B31-BD48-4E375B995560}" src="https://github.com/user-attachments/assets/f8c91d7b-4657-44cb-990e-26c2c494d7ff" />
<img width="1893" height="873" alt="{5CB0A3B6-DC70-4FB4-8ACB-5D6F0DCEF7D7}" src="https://github.com/user-attachments/assets/44ceb77f-28e7-4b1b-8de1-3ecb60a18421" />
<img width="1883" height="864" alt="{F86C2CBC-78CE-4633-9F64-84EE7A686D6B}" src="https://github.com/user-attachments/assets/a0551731-4274-489d-9c77-d4881a7e367c" />


⚙️ Features

Responsive login page for Students, Faculty, and Admins

Role-based dashboards (front-end only)

Access to notifications and course materials (UI mockup)

Profile and dashboard navigation menus

Works on desktop and mobile devices

🛠 Technology Stack

Frontend: HTML, CSS, JavaScript

Containerization: Docker

Orchestration: Kubernetes

Cloud Hosting: Microsoft Azure VM (Ubuntu)

Flow Diagram:
Local HTML/CSS/JS → Docker → DockerHub → Kubernetes → Azure VM → Public IP → Website

📝 Installation & Setup

1️⃣ Clone Repository
git clone https://github.com/your-username/VidyaPortal.git
cd VidyaPortal

2️⃣ Build Docker Image
docker build -t vidyaportal .

3️⃣ Push to DockerHub
docker tag vidyaportal yourdockerhubusername/vidyaportal:latest
docker push yourdockerhubusername/vidyaportal:latest

4️⃣ Deploy on Kubernetes
kubectl apply -f k8s/deployment.yaml
kubectl apply -f k8s/service.yaml

5️⃣ Access Application
Open browser: http://20.40.47.178/dashboard

📁 Kubernetes Structure (Front-End)

deployment.yaml – Deploy front-end container

service.yaml – Expose front-end service

configmaps/ – Optional front-end configs 

🧑‍💻 Demo Accounts (UI Mockup)

Role	Email

Student	arjun@university.edu

Faculty	sanjay@university.edu

Admin	admin@university.edu
