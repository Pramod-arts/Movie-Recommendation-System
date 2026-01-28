# 🎬 Movie Recommendation System

An AI-powered movie recommendation system built with Django and machine learning, designed to deliver fast and accurate movie suggestions using content-based filtering.

---

## 🚀 Overview

This project recommends similar movies using TF-IDF vectorization and SVD dimensionality reduction.  
It includes a modern web interface, REST APIs, and supports datasets ranging from a few thousand to over a million movies.

---

## ✨ Features

- 🔍 Smart movie search with autocomplete  
- 🎬 AI-based content recommendations  
- ⚡ Fast and scalable architecture  
- 📱 Responsive web interface  
- 📡 REST API support  
- 🚀 Deployment-ready (Render, Heroku, Docker)

---

## ⚡ Quick Start

### Requirements
- Python 3.10+
- pip
- Git

### Installation
```bash
git clone https://github.com/yourusername/movie-recommendation-system.git
cd movie-recommendation-system

python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
