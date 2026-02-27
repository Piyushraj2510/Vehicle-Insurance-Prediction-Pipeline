<h1 align="center">🚗 CLAIMGUARD-OPS</h1>

<p align="center">
  <i>Transforming Vehicle Insurance Data into Actionable Insights Instantly</i>
</p>

<p align="center">
  <img src="https://img.shields.io/github/last-commit/Piyushraj2510/ClaimGuard-Ops?style=flat-square" />
  <img src="https://img.shields.io/github/languages/top/Piyushraj2510/ClaimGuard-Ops?style=flat-square" />
  <img src="https://img.shields.io/github/languages/count/Piyushraj2510/ClaimGuard-Ops?style=flat-square" />
</p>

---

## 📌 About the Project

ClaimGuard-Ops is a production-ready **Vehicle Insurance Claim Prediction System** built using modern **MLOps practices**.

It includes:
- 📊 Data preprocessing pipeline  
- 🧠 Model training & evaluation  
- 🚀 API-based deployment  
- 🐳 Docker containerization  
- 🔁 CI/CD integration  

This project demonstrates how machine learning systems move from experimentation to production.

---

## 🚀 Live Demo

🔗 **Live Website / Deployment:**  
(http://3.92.18.19:5000/) 


## 🛠 Built with the tools and technologies:

<p align="center">

<img src="https://img.shields.io/badge/JSON-black?style=for-the-badge&logo=json" />
<img src="https://img.shields.io/badge/Markdown-black?style=for-the-badge&logo=markdown" />
<img src="https://img.shields.io/badge/npm-red?style=for-the-badge&logo=npm" />
<img src="https://img.shields.io/badge/TOML-brown?style=for-the-badge" />
<br/>
<img src="https://img.shields.io/badge/scikit--learn-orange?style=for-the-badge&logo=scikit-learn" />
<img src="https://img.shields.io/badge/esbuild-yellow?style=for-the-badge&logo=esbuild" />
<img src="https://img.shields.io/badge/FastAPI-teal?style=for-the-badge&logo=fastapi" />
<img src="https://img.shields.io/badge/NumPy-darkblue?style=for-the-badge&logo=numpy" />
<br/>
<img src="https://img.shields.io/badge/AWS-orange?style=for-the-badge&logo=amazon-aws" />
<img src="https://img.shields.io/badge/MongoDB-green?style=for-the-badge&logo=mongodb" />
<img src="https://img.shields.io/badge/Docker-blue?style=for-the-badge&logo=docker" />
<img src="https://img.shields.io/badge/Python-blue?style=for-the-badge&logo=python" />
<br/>
<img src="https://img.shields.io/badge/TypeScript-blue?style=for-the-badge&logo=typescript" />
<img src="https://img.shields.io/badge/Plotly-darkblue?style=for-the-badge&logo=plotly" />
<img src="https://img.shields.io/badge/BAT-grey?style=for-the-badge" />
<img src="https://img.shields.io/badge/pandas-purple?style=for-the-badge&logo=pandas" />
<br/>
<img src="https://img.shields.io/badge/YAML-red?style=for-the-badge&logo=yaml" />

</p>

---

## 🚀 Project Architecture
<p>
Data → Preprocessing → Model Training → Model Evaluation → Saved Model → FastAPI → Docker → Deployment
</p>

---
## 🧩 Use Cases

Insurance companies and platforms can leverage this project to:

✅ **Predict Claim Approval Probability** – Estimate likelihood of claim approvals based on historical data. 
✅ **Estimate Risk Levels** – Identify high-risk claims requiring manual review.  
✅ **Reduce Fraudulent Claims** – Flag suspicious claims automatically. 
✅ **Automate Claim Processing Decisions** – Reduce manual workload for claim adjusters.

---
## ⚙️ How to Run Locally

Follow these steps to set up and run ClaimGuard-Ops on your machine.

### 🔹 Prerequisites

Make sure you have:

✔ Python 3.8+  
✔ Docker & Docker Compose  
✔ Git

---

### 🔹 Clone the Repo

```bash
git clone https://github.com/Piyushraj2510/ClaimGuard-Ops.git
cd ClaimGuard-Ops

---
### 🔹 Install Dependencies

Using a Python virtual environment:

```bash
python -m venv venv
source venv/bin/activate      # Mac / Linux
venv\Scripts\activate         # Windows

```bash
pip install -r requirements.txt

---
###🔹 Run the API

```bash
uvicorn app:app --reload

Visit: http://localhost:8000 in your browser.

###🔹 Using Docker

Build and run the container:

```bash
docker build -t claimguard-ops .
docker run -p 8000:8000 claimguard-ops

Now open: http://localhost:8000

This ensures your environment mirrors the production setup.

##📝 Contribute 🚀

We welcome contributions! Here’s how you can help improve ClaimGuard-Ops:

###📌 Suggested Improvements

✔ Add more datasets for diverse insurance scenarios
✔ Improve model accuracy with new algorithms
✔ Add frontend UI for visual predictions
✔ Expand CI/CD to include automated model validation

###💡 How to Submit a Pull Request

1.Fork the repo

2.Create your feature branch

```bash
git checkout -b feature/my-awesome-feature

3.Commit your changes

```bash
git commit -m "Add awesome new feature"

4.Push to your fork

```bash
git push origin feature/my-awesome-feature

5.Open a Pull Request describing your change
