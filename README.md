<h1 align="center">
  <b>Hi, I'm Azeem Aslam</b>
</h1>

<h2 align="center">Computer Vision | NLP | Deep Learning | AI Automation</h2>

<h3 align="center">Scientific AI Developer, Technical Writer, and Freelancer</h3>

<p align="center">
  <b>I build practical AI systems for healthcare, veterinary science, manufacturing, automation, and NLP products.</b><br/>
  My work focuses on computer vision, medical imaging, segmentation, natural language processing,
  explainable AI, and deployable ML applications.
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=azeem-aslam-ch&label=Profile%20Views&color=0ea5e9&style=for-the-badge" alt="Profile Views"/>
  <a href="https://azeemaslam.com/" target="_blank" rel="noopener">
    <img src="https://img.shields.io/badge/Portfolio-Visit%20Now-7c3aed?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://linkedin.com/in/azeemaslam1" target="_blank" rel="noopener">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>

---

## About Me

I am a Computer Vision and Deep Learning Engineer with a strong interest in scientific AI systems. I work across the full pipeline: dataset preparation, annotation strategy, model training, evaluation, deployment, and technical reporting.

My current focus areas are:

- Medical and veterinary imaging AI
- Natural Language Processing, LLM apps, and AI agents
- YOLO-based object detection and instance segmentation
- Explainable AI for real-world decision support
- Streamlit, FastAPI, Docker, and cloud deployment
- Research documentation and professional technical reports

---

## Technical Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,js,r,html,css,nextjs,pytorch,tensorflow,opencv,sklearn,fastapi,docker,mongodb,github,git,vercel,vscode&perline=10" alt="Technical stack icons"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/YOLOv8-111827?style=for-the-badge&logo=target&logoColor=00bfff" alt="YOLOv8"/>
  <img src="https://img.shields.io/badge/Ultralytics-111827?style=for-the-badge&logo=ultralytics&logoColor=white" alt="Ultralytics"/>
  <img src="https://img.shields.io/badge/Streamlit-111827?style=for-the-badge&logo=streamlit&logoColor=ff4b4b" alt="Streamlit"/>
  <img src="https://img.shields.io/badge/RabbitMQ-111827?style=for-the-badge&logo=rabbitmq&logoColor=ff6600" alt="RabbitMQ"/>
  <img src="https://img.shields.io/badge/Selenium-111827?style=for-the-badge&logo=selenium&logoColor=43b02a" alt="Selenium"/>
  <img src="https://img.shields.io/badge/Playwright-111827?style=for-the-badge&logo=playwright&logoColor=2ead33" alt="Playwright"/>
  <img src="https://img.shields.io/badge/HuggingFace-111827?style=for-the-badge&logo=huggingface&logoColor=ffd21e" alt="Hugging Face"/>
  <img src="https://img.shields.io/badge/OpenAI-111827?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI"/>
  <img src="https://img.shields.io/badge/Plotly-111827?style=for-the-badge&logo=plotly&logoColor=3f4f75" alt="Plotly"/>
  <img src="https://img.shields.io/badge/Pytest-111827?style=for-the-badge&logo=pytest&logoColor=0a9edc" alt="Pytest"/>
</p>

**AI / CV:** YOLOv8, Ultralytics, OpenCV, Grad-CAM, Roboflow, PyTorch, TensorFlow, scikit-learn  
**NLP / LLM:** Hugging Face Transformers, XLM-RoBERTa, multilingual sentiment analysis, OpenAI API, Ollama  
**Backend / Data:** FastAPI, Streamlit, MongoDB, RabbitMQ, REST APIs, JWT authentication  
**Automation / Deploy:** Selenium, Playwright, Docker, Pytest, GitHub, Vercel, Streamlit Cloud  
**Reporting:** Matplotlib, Plotly, fpdf2, ReportLab, technical documentation

---

## Featured Projects

### 1. OvaPredict AI - Buffalo Oocyte Maturation Prediction

AI-based research system for predicting buffalo oocyte maturation from brightfield microscopy images of cumulus-oocyte complexes.

**Highlights**

- YOLOv8s-seg instance segmentation for COC microscopy images
- Direct classification pipeline: mature vs not mature
- Research pipeline: YOLO segmentation plus Random Forest feature analysis
- 52 morphological features from COC, oocyte, zona, and cumulus regions
- Professional PDF reports with KPI cards, 3D-style charts, confusion matrices, and feature importance
- Live Streamlit deployment for image upload and prediction

**Links**

[Live App](https://ova-predict-ai.streamlit.app/) |
[Repository](https://github.com/azeem-aslam-ch/ova-predict-ai)

---

### 2. CSU Sentiment Analysis - Police Public Sentiment Intelligence

Production backend system for the Chief Minister's Crime Surveillance Unit (CSU), Punjab. It monitors public sentiment about police services across social media, runs multilingual AI sentiment analysis, raises alerts, and serves analytics through a FastAPI backend.

**Highlights**

- Scrapes and processes public posts/comments from Facebook, X/Twitter, Instagram, TikTok, and YouTube
- Multilingual NLP pipeline for English, Urdu, Roman Urdu, and Punjabi/Shahmukhi
- XLM-RoBERTa transformer sentiment model plus rule-based analysis
- Ollama LLM narrative insight generation with `qwen2.5:14b`
- MongoDB storage, RabbitMQ queues, FastAPI REST API, alerts, dashboard analytics

**Links**

[Repository](https://github.com/azeem-aslam-ch/csu-sentiment-analysis)

---

### 3. Chest X-Ray Diagnostic Assistant

A Streamlit and PyTorch application for multi-disease chest X-ray classification with Grad-CAM visual explanations.

**Features**

- Upload PNG, JPG, or DICOM images
- Predict Normal, COVID, Lung Opacity, or Viral Pneumonia
- Generate Grad-CAM heatmaps for explainability

[Live App](https://chest-xray-app-mfawfpdbjakjdr7bsotynh.streamlit.app/) |
[Repository](https://github.com/azeem-aslam-ch/chest-xray-assignment) |
[Trained Model](https://drive.google.com/file/d/1JLddmWmofxj8fIjVzbu1iZlF8XQt8B2Z/view?usp=drive_link)

---

### 4. Azeem Aslam AI Agent - NLP Customer Support Platform

A production-style NLP and LLM customer support chatbot platform built with FastAPI, modern frontend code, Docker, and OpenAI API integration.

**Features**

- Custom AI persona powered by the OpenAI API
- Natural language understanding for support-style conversations
- Prompt-engineered responses with a domain-specific assistant flow
- Asynchronous FastAPI backend
- Dockerized workflow with CI/CD-ready structure

[Live Demo](https://azeembot.netlify.app/) |
[Repository](https://github.com/azeem-aslam-ch/ai-chatbot)

---

### 5. Additive Manufacturing Defect Detection

A Streamlit computer-vision application for detecting defects in 3D-printed components using YOLO-based object detection.

**Features**

- Detect cracking, stringing, layer shifting, and related defects
- Upload images and inspect model detections
- Export detection results for analysis

[Live App](https://3dprintingdefectdetection.streamlit.app/)

---

### 6. Vehicle Classification With YOLOv8

A Hugging Face Spaces app for detecting and classifying two-wheeler vehicles such as motorcycles, scooters, and bikes.

[Live App](https://huggingface.co/spaces/azeemaslam/vehicle-detector)

---

## More Projects

| Project | Area |
|--------|------|
| [Brain Tumor Detection](https://github.com/azeem-aslam-ch/Medical-imaging-with-YOLOv9-) | Medical imaging with YOLOv9 |
| [Industrial Object Detection](https://github.com/azeem-aslam-ch/industrial_object_detection-) | Industrial computer vision |
| [Active Phone User Detection](https://github.com/azeem-aslam-ch/phone_user_detection) | Mobile user detection |
| [Clinical Trial Insights](https://github.com/azeem-aslam-ch/Clinical_Trial-Insights) | Clinical data insights |

---

## GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=azeem-aslam-ch&theme=tokyonight&no-frame=true&margin-w=12&margin-h=12" alt="GitHub Trophies"/>
</p>

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=azeem-aslam-ch&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" width="49%"/>
  <img src="https://github-readme-streak-stats.herokuapp.com?user=azeem-aslam-ch&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="49%"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=azeem-aslam-ch&theme=tokyo-night&hide_border=true" alt="GitHub Contribution Graph" width="98%"/>
</p>

---

## Let's Connect

<p align="center">
  <a href="https://linkedin.com/in/azeemaslam1" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/LinkedIn-azeemaslam1-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:azeem.aslam91@yahoo.com">
    <img src="https://img.shields.io/badge/Email-Contact-blue?style=for-the-badge&logo=yahoo&logoColor=white" alt="Email"/>
  </a>
  <a href="https://www.kaggle.com/awaisaslam1" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/Kaggle-awaisaslam1-20beff?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle"/>
  </a>
  <a href="https://www.azeemaslam.com" target="_blank" rel="noopener">
    <img src="https://img.shields.io/badge/Website-azeemaslam.com-7c3aed?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website"/>
  </a>
</p>

---

<p align="center">
  <em>Pushing boundaries with intelligent vision-based systems and AI-powered solutions.</em>
</p>
