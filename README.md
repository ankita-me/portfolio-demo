# Ankita Mishra • Software Engineer Portfolio

A clean, modern, and high-performance personal portfolio for **Ankita Mishra**, featuring backend engineering, cloud/DevOps experience, technical skills, and an automated **GitHub Actions CI/CD pipeline** deploying directly to **GitHub Pages**.

---

## 📌 Overview

This repository hosts the personal portfolio of **Ankita Mishra**, highlighting professional experience in Python backend development, REST APIs, microservices, databases, and cloud/DevOps automation.

- **Theme**: Neo-Minimalist Emerald Slate (Clean, readable, dark-mode styling with ambient emerald glow accents).
- **Automation**: Fully automated CI/CD pipeline using **GitHub Actions** (`deploy.yml`) that deploys changes live to **GitHub Pages** on every push.

---

## 👩‍💻 Profile Summary

Backend-focused Software Engineer with 1+ years of professional experience in:
- **Backend**: Python, FastAPI, REST APIs, Microservices
- **Databases & Caching**: PostgreSQL, MongoDB, Redis
- **Cloud & DevOps**: AWS (Lambda, ECS, S3), Docker, Jenkins, Kubernetes, CI/CD
- **Tools & Libraries**: Git, Linux, SQLAlchemy, Polars

---

## 💼 Work Experience

### 1. Prismatica Private Limited
**Independent Contractor / Freelance Software Developer** *(Jul 2025 – Present)*
- Built and maintained 10+ REST APIs using **FastAPI** for backend services and real-time applications.
- Maintained and enhanced 2–3 microservices supporting no-code applications and page management.
- Developed real-time visualization dashboards integrated with **Ollama** to fetch and display user-requested data dynamically.
- Worked with **PostgreSQL**, **MongoDB**, and **Redis** for data storage, caching, and analytics.
- Containerized backend applications using **Docker** and contributed to scalable microservice architecture.
- Integrated backend services with frontend dashboards and optimized API performance.

### 2. IT World Education
**Cloud & DevOps Internship** *(Jun 2024 – Sep 2024)*
- Built and deployed cloud-native applications using AWS services (**Lambda**, **ECS**, **Docker**, **S3**).
- Implemented CI/CD pipelines using **Jenkins**, **GitHub**, **Kubernetes**, **SonarQube**, and **Nexus**.
- Automated deployment workflows and container orchestration.

---

## 🚀 Featured Projects

### 1. Visualization Engine Project
- **Stack**: Python, FastAPI, Ollama, Redis, PostgreSQL
- Designed and implemented a visualization engine that generated dynamic dashboards based on user queries.
- Integrated Ollama LLM for real-time readings and dynamic data processing.
- Built high-performance FastAPI endpoints with Redis caching and PostgreSQL storage.

### 2. Automated GitHub Pages CI/CD Pipeline
- **Stack**: GitHub Actions, GitHub Pages, YAML, HTML5/CSS3
- Configured a declarative GitHub Actions workflow (`deploy.yml`) for automated testing and deployment.
- Deploys static site assets globally on GitHub Pages with zero manual intervention on push to `main`.

---

## 🎓 Education

- **Master of Computer Applications (MCA)** — *GATE, Golanthara (2023 – 2025)* | **CGPA: 8.61**
- **Bachelor of Science (B.Sc.)** — *Mahamayee Mahila Mahavidhyalaya (2017 – 2020)* | **CGPA: 7.60**
- **Higher Secondary (XII - Science)** — *Atomic Energy Central School, Chatrapur (2015 – 2017)* | **63.6%**
- **Secondary (X)** — *De Paul School, Berhampur (2003 – 2015)* | **79.6%**

---

## 📁 Project Structure

```text
ankita-devops-demo/
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Actions automated deployment workflow
├── index.html              # Main portfolio webpage (Resume-based content)
├── style.css               # Neo-Minimalist Emerald Slate styling
└── README.md               # Project documentation & setup guide
```

---

## ⚙️ How It Deploys Live (CI/CD Pipeline)

The deployment is handled automatically by [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml):

1. **Trigger**: Executes on every `git push` to `main` or `master` (and supports manual `workflow_dispatch`).
2. **Checkout**: Checks out repository code via `actions/checkout@v4`.
3. **Configure Pages**: Sets up GitHub Pages metadata using `actions/configure-pages@v4`.
4. **Package Artifact**: Archives the directory using `actions/upload-pages-artifact@v3`.
5. **Deploy**: Publishes the live site to GitHub Pages via `actions/deploy-pages@v4`.

---

## 🛠️ Deployment Instructions

### 1. Push Changes to GitHub

Open PowerShell in this directory:

```powershell
cd C:\Users\puja1\Downloads\cicd\ankita-devops-demo

# Stage modified files
git add .

# Commit changes
git commit -m "docs: update README with actual resume and portfolio content"

# Push to GitHub
git push origin main
```

### 2. Enable GitHub Pages (One-time Setup)
1. In your GitHub repository, open **Settings** > **Pages** (under *Code and automation*).
2. Under **Build and deployment > Source**, select **GitHub Actions**.

### 3. View Live Site
Go to the **Actions** tab to view your build progress. Your live site will be hosted at:
```text
https://<YOUR_GITHUB_USERNAME>.github.io/<YOUR_REPO_NAME>/
```

---

## 📬 Contact

- **Name**: Ankita Mishra
- **Location**: Bangalore, India
- **Email**: [puja1998.mishra@gmail.com](mailto:puja1998.mishra@gmail.com)
- **Phone**: +91 9040249390
- **LinkedIn**: [linkedin.com/in/ankita-mishra-30aa0a275](https://linkedin.com/in/ankita-mishra-30aa0a275)
