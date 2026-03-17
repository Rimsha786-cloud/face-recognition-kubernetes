# Face Recognition using Kubernetes

## 📌 Description
This project implements a Face Recognition system using OpenCV and Flask. The application is containerized using Docker and deployed using Kubernetes (Minikube). It provides a simple web interface where users can upload images and detect faces.

---

## 🚀 Technologies Used
- Python
- OpenCV
- Flask
- Docker
- Kubernetes
- Minikube

---

## ⚙️ Features
- Upload image through web UI
- Detect faces using OpenCV Haar Cascade
- Display number of faces detected
- Draw bounding boxes around faces
- Scalable deployment using Kubernetes

---

## 🏗️ Architecture

User → Kubernetes Service → Pod → Docker Container → Flask App → OpenCV Model

---

## ▶️ Steps to Run

1. Start Minikube
