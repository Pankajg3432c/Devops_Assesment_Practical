# 🚀 FastAPI CI/CD Project

**Author:** Pankaj Gupta
**Role:** The Automator – GitHub Actions & CI/CD

---

## 📌 Project Overview

This project showcases a **FastAPI application** integrated with a robust **CI/CD Safety Shield**. It ensures that untested or buggy code **never reaches production**, maintaining code quality and stability.

**Key Objectives:**

* Automatic linting and testing on every pull request
* Safe Docker image creation and deployment
* Fast feedback to developers on failures

---

## 🧱 Tech Stack

* **Backend Framework:** FastAPI
* **Programming Language:** Python 3.11
* **Containerization:** Docker
* **CI/CD Tool:** GitHub Actions
* **Container Registry:** Docker Hub
* **Version Control:** Git & GitHub

---

## ▶️ How to Run the Project (Commands Only)

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Pankajg3432c/Devops_Assesment_Practical.git
cd Devops_Assesment_Practical
```

### 2️⃣ Build and Run Using Docker (Recommended)

#### Build Docker Image

```bash
docker build -t fastapi-app .
```

#### Run Docker Container

```bash
docker run -d -p 8000:8000 fastapi-app
```

### 3️⃣ Pull Image from Docker Hub

```bash
docker pull pankajg3432c/fastapi-app:latest
```

#### Run Pulled Image

```bash
docker run -d -p 8000:8000 pankajg3432c/fastapi-app:latest
```

**Access the application:**

```
http://localhost:8000
```

---

## 🔄 CI/CD Pipeline Summary (Conceptual)

* Triggers on every **Pull Request**
* Performs **linting** and **unit tests**
* **Merge blocked** if tests fail
* **Docker image build and push** occurs only if tests pass
* Ensures production always receives **stable and tested code**

**Benefits:**

* Automated quality checks
* Reduced risk of production bugs
* Faster feedback and iterations

---

## 🔐 Branch Protection Strategy

* Direct pushes to `main` are disabled
* Pull Requests are mandatory for merging
* CI pipeline checks must pass before merging
* Guarantees only validated code is merged

**Outcome:** Enhanced code reliability and safer deployment process.

---

## 🎯 Key Outcomes

* Faster developer feedback on code changes
* Zero buggy deployments
* Streamlined automation using GitHub Actions
* Production-ready, stable CI/CD workflow
