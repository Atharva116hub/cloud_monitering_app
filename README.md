# 🌥️ Cloud Monitoring App

A cloud-native application for monitoring and managing workloads, deployed on Kubernetes using AWS EKS.  
The app is containerized with Docker, pushed to AWS ECR, and deployed on an EKS cluster with Kubernetes manifests.

---

## 📌 Features
- Flask-based web application for monitoring data.
- Containerized using **Docker** for portability.
- AWS **ECR** for container image storage.
- AWS **EKS** for Kubernetes-based deployment.
- HTML templates for a simple web UI.
- Easy local testing before cloud deployment.

---

## 🛠️ Tech Stack
- **Programming Language:** Python (Flask)
- **Cloud Provider:** AWS
- **Containerization:** Docker
- **Orchestration:** Kubernetes (EKS)
- **Image Registry:** AWS ECR
- **Infrastructure Tools:** AWS CLI, kubectl
- **Templates:** HTML, CSS (Jinja2)

---

## 📂 Project Structure
cloud_monitering_app/
├── app.py # Main Flask app
├── ecr.py # Script to build & push image to AWS ECR
├── eks.py # Script to deploy on AWS EKS
├── Dockerfile # Container build instructions
├── requirements.txt # Python dependencies
├── templates/ # HTML templates for UI
└── README.md # Documentation


---

## ⚙️ Prerequisites
Before running the project, make sure you have:
- Python 3.9+
- AWS account with ECR & EKS setup
- AWS CLI installed & configured
- kubectl installed
- Docker installed

---

## 🚀 Setup & Deployment

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Atharva116hub/cloud_monitering_app.git
cd cloud_monitering_app

#Install dependencies
pip install -r requirements.txt

#Run locally
python app.py

#Build & Push to AWS ECR
python ecr.py

#Deploy to AWS EKS
python eks.py


Skills Demonstrated
Python • Flask • AWS ECR • AWS EKS • Docker • Kubernetes • AWS CLI • HTML/CSS • Cloud Monitoring
