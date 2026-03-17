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
2. Build Docker Image
3. Deploy to Kubernetes
4. Access Application

   
---

## 📷 Output
<img width="2879" height="764" alt="image" src="https://github.com/user-attachments/assets/d7dcdffd-0432-45e7-a442-ab387185effc" />
<img width="762" height="143" alt="image" src="https://github.com/user-attachments/assets/7e27bcdd-166e-4384-ae23-1de3d308b130" />


- Web UI for image upload
- Displays detected faces count
- Shows processed image with bounding boxes

(Add screenshots here)

---

## ✅ Result
The Face Recognition application was successfully deployed using Docker containers and Kubernetes, demonstrating scalable AI deployment.

---

## 📚 Conclusion
This project shows how AI applications can be containerized and deployed in a scalable environment using Kubernetes.

