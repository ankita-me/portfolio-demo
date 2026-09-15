# Ankita Mishra • DevOps & Cloud Portfolio

A modern, high-performance DevOps portfolio with a creative **Cyber-Aurora Glassmorphism** theme and automated **GitHub Actions CI/CD** pipeline deploying directly to **GitHub Pages**.

---

## 🎨 New Features & Creative Theme

- **Theme**: Cyber-Aurora Glassmorphism with floating cosmic light orbs, cyber grid mesh, and frosted glass cards.
- **Header**: Features the introduction requested:
  > *"Hi, my name is Ankita Mishra — Here is the DevOps demo which I can deploy in my GitHub and make it live!"*
- **Sections**:
  - ⚡ **Interactive CI/CD Workflow**: Visual representation of the automated pipeline stages.
  - 👩‍💻 **About Ankita Mishra**: DevOps philosophy, cloud approach, and core strengths.
  - 🛠️ **DevOps & Cloud Skill Matrix**: AWS, Azure, GCP, GitHub Actions, Docker, Kubernetes, Terraform, Ansible, Prometheus, Grafana, DevSecOps.
  - 🚀 **Featured Projects**: Live GitHub Pages CI/CD workflow, Kubernetes GitOps microservices, Terraform multi-region infrastructure.
  - 💻 **Simulated Runner Console**: Live-styled terminal displaying commit-to-deploy logs.
  - 📬 **Interactive Contact**: One-click email copy with instant toast alert, GitHub and LinkedIn links.

---

## 📁 Project Structure

```text
ankita-devops-demo/
├── .github/
│   └── workflows/
│       └── deploy.yml   # GitHub Actions workflow for automated Pages deployment
├── index.html           # Ankita Mishra DevOps portfolio
├── style.css            # Cyber-Aurora glassmorphic styling & animations
└── README.md            # Setup and deployment guide
```

---

## 🚀 How to Deploy & Make It Live on GitHub

### 1. Create a New Repository on GitHub
1. Go to [github.com/new](https://github.com/new).
2. Set repository name (e.g. `ankita-devops-portfolio` or `devops-demo`).
3. Set visibility to **Public**.
4. Leave all template checkboxes unchecked.
5. Click **Create repository**.

---

### 2. Push from PowerShell / Terminal

Open PowerShell inside the project directory (`C:\Users\puja1\Downloads\cicd\ankita-devops-demo`) and run:

```powershell
cd C:\Users\puja1\Downloads\cicd\ankita-devops-demo

# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "feat: Launch Ankita Mishra DevOps Portfolio with Cyber-Aurora theme"

# Set branch to main
git branch -M main

# Link remote (replace <YOUR_USERNAME> and <YOUR_REPO>)
git remote add origin https://github.com/<YOUR_USERNAME>/<YOUR_REPO>.git

# Push to GitHub
git push -u origin main
```

---

### 3. Enable GitHub Pages Deployment
1. On GitHub, navigate to your repository's **Settings**.
2. Click **Pages** on the left menu (under "Code and automation").
3. Change **Source** under "Build and deployment" from *"Deploy from a branch"* to **GitHub Actions**.

---

### 4. Site Goes Live Automatically!
1. Head over to the **Actions** tab in your repository.
2. Watch the GitHub Actions pipeline build and deploy your site in ~30 seconds.
3. Once completed, your live site URL will be:
   ```text
   https://<YOUR_USERNAME>.github.io/<YOUR_REPO>/
   ```
4. Any future edit you commit and push will automatically re-deploy your portfolio live!
