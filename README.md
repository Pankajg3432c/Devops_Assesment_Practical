# 🚀 FastAPI CI/CD Project

Author: **Pankaj Gupta**
Focus Role: **The Automator – GitHub Actions & CI/CD**

---

## 📌 Project Overview

This project demonstrates a **FastAPI application** with a strong **CI/CD Safety Shield**. The pipeline ensures that buggy or untested code never gets merged or released.

---

## Tech Stack Used

* **Backend Framework**: FastAPI
* **Programming Language**: Python 3.11
* **Containerization**: Docker
* **CI/CD Tool**: GitHub Actions
* **Container Registry**: Docker Hub
* **Version Control**: Git & GitHub

---

## ▶️ How to Run the Project (Commands Only)

### 1️⃣ Clone Repository

```
git clone https://github.com/Pankajg3432c/Devops_Assesment_Practical.git
cd Devops_Assesment_Practical
```

---

3️⃣ Run Using Docker (Recommended)

#### Build Docker Image

```
docker build -t fastapi-app .
```

#### Run Docker Container

```
docker run -d -p 8000:8000 fastapi-app
```

---

###  Pull Image from Docker Hub

```
docker pull pankajg3432c/fastapi-app:latest
```

```
docker run -d -p 8000:8000 pankajg3432c/fastapi-app:latest
```

---

## 🔄 CI/CD Pipeline Summary (Conceptual)

* Pipeline triggers on every **Pull Request**
* Runs **linting** and **unit tests**
* If tests fail → merge is blocked
* If tests pass → Docker image is built and pushed
* Ensures only stable code reaches release stage

---

## 🔐 Branch Protection Strategy (High Level)

* Direct push to main branch is disabled
* Pull Request is mandatory
* CI pipeline must pass before merge
* Prevents untested or broken code from merging

---

## 🎯 Key Outcome

* Faster feedback to developers
* Zero buggy deployments
* Clean automation using GitHub Actions
* Production‑ready DevOps workflow

---


