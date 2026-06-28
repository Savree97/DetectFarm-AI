---
title: DetectFarm AI
emoji: 🌾
colorFrom: green
colorTo: blue
sdk: docker
pinned: false
---

<div align="center">

# 🌾 DetectFarm AI

### AI-Powered Farmland Analysis using Computer Vision & Generative AI

Automatically detect farmland plots from RGB satellite imagery, analyze field characteristics, and generate AI-powered agricultural recommendations using **Google Gemini 2.5 Flash**.

<p>

[![Live Demo](https://img.shields.io/badge/🚀-Live%20Demo-orange?style=for-the-badge)](https://huggingface.co/spaces/sav06/detectfarm-ai)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)](https://github.com/Savree97/DetectFarm-AI)
![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Docker](https://img.shields.io/badge/Docker-Deployed-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</p>

</div>

---

## 📌 Overview

DetectFarm AI is a **Computer Vision + Generative AI** application developed during my Undergraduate Research Internship at the **Centre of Excellence in Product Design & Smart Manufacturing, MANIT Bhopal**.

The application automatically detects agricultural plots from RGB satellite imagery, extracts meaningful geometric features, clusters farmland regions using Machine Learning, generates analytical reports, and produces intelligent farming recommendations using **Google Gemini 2.5 Flash**.

**Key capabilities**

- 🌾 Automatic farmland boundary detection
- 📊 Plot-level feature extraction & clustering
- 📈 Interactive analytics dashboard
- 📑 Excel report generation
- 🤖 AI-generated agricultural advisory
- ☁️ Docker deployment on Hugging Face Spaces

---

# 📷 Application Preview

| Home | Plot Detection |
|------|------|
| ![](screenshots/home.png) | ![](screenshots/analysis.png) |

| Statistics Dashboard | AI Advisory |
|------|------|
| ![](screenshots/statistics.png) | ![](screenshots/advisory.png) |

---

## 🔄 Workflow

```text
Satellite Image
      │
      ▼
Image Preprocessing
      │
      ▼
Boundary Detection
      │
      ▼
Feature Extraction
      │
      ▼
K-Means Clustering
      │
      ▼
Analytics & Excel Report
      │
      ▼
Gemini 2.5 Flash
      │
      ▼
AI Farm Advisory
```

---

## 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Backend | Flask, Python |
| Computer Vision | OpenCV, scikit-image |
| Machine Learning | scikit-learn, K-Means, PCA |
| Data Processing | NumPy, Pandas |
| Visualization | Matplotlib |
| AI | Google Gemini 2.5 Flash |
| Reports | OpenPyXL |
| Deployment | Docker, Hugging Face Spaces |

---

## 🚀 Run Locally

Clone the repository

```bash
git clone https://github.com/Savree97/DetectFarm-AI.git
```

Move into the project

```bash
cd DetectFarm-AI
```

Install dependencies

```bash
pip install -r requirements.txt
```

Start the application

```bash
python app.py
```

---

## 🐳 Docker

Build

```bash
docker build -t detectfarm-ai .
```

Run

```bash
docker run -p 7860:7860 detectfarm-ai
```

---

## 📂 Project Structure

```text
DetectFarm-AI
│
├── app.py
├── Dockerfile
├── requirements.txt
├── templates/
├── static/
├── screenshots/
└── README.md
```

---

## 🔮 Future Improvements

- Segment Anything Model (SAM)
- Deep-learning based segmentation
- NDVI support
- Weather API integration
- Crop classification
- Mobile application

---

## 👨‍💻 Author

**Savree Dohar**

B.Tech Computer Science & Engineering  
Thapar Institute of Engineering and Technology

**GitHub**  
https://github.com/Savree97

**LinkedIn**  
https://www.linkedin.com/in/savree-dohar-8a53002a2/

---

<div align="center">

⭐ **If you found this project useful, consider starring the repository!**

</div>
