# 🏋️ FitVisor – AI Powered Fitness Assistant

An AI-powered fitness platform that combines **Computer Vision**, **Retrieval-Augmented Generation (RAG)**, and **real-time pose estimation** to help users improve workout form, receive intelligent fitness guidance, and access evidence-based health information.

FitVisor provides real-time exercise analysis using **MediaPipe Pose**, an AI fitness chatbot powered by research papers, and a virtual fitness assistant to support users throughout their fitness journey.

---

# 🚀 Features

## 🏃 Real-Time Exercise Analysis

- Real-time squat form detection
- Automatic repetition counting
- Knee and hip angle calculation
- Live posture correction feedback
- Workout efficiency scoring
- Visual angle tracking

---

## 🤖 AI Fitness Chatbot

- Retrieval-Augmented Generation (RAG)
- Answers fitness-related questions
- Uses scientific research papers as knowledge source
- Evidence-based responses
- Context-aware question answering

---

## 🧠 AI Fitness Assistant

- Interactive virtual fitness assistant
- General fitness guidance
- Exercise recommendations
- Workout support

---

# 🛠 Tech Stack

## Frontend

- HTML5
- CSS3
- JavaScript

## Backend

- Python
- Flask

## AI / Machine Learning

- MediaPipe Pose
- OpenCV
- RAG
- LLM Integration

## Document Processing

- PDF Knowledge Base
- Research Paper Retrieval

---

# 📂 Project Structure

```
FitVisor
│
├── Assistant
│   ├── app.py
│   ├── web.py
│   └── templates/
│
├── Chatbot
│   ├── app.py
│   ├── ingest.py
│   ├── rag.py
│   ├── documents/
│   └── test_questions.py
│
├── Vision_train
│   ├── squats.html
│   ├── biceps.html
│   ├── js/
│   └── css/
│
└── .gitignore
```

---

# 💡 How It Works

## 1️⃣ Pose Detection

MediaPipe Pose detects body landmarks in real time using the webcam.

↓

## 2️⃣ Angle Calculation

Joint angles such as:

- Knee
- Hip
- Shoulder

are calculated to determine exercise posture.

↓

## 3️⃣ Exercise Analysis

The system:

- Counts repetitions
- Detects incorrect posture
- Provides live corrective feedback
- Calculates workout efficiency

↓

## 4️⃣ AI Chatbot

User questions are answered using a Retrieval-Augmented Generation (RAG) pipeline powered by a curated collection of fitness and health research papers.

---

# 📚 Knowledge Base

The chatbot retrieves information from a curated collection of scientific literature covering topics such as:

- Strength Training
- Muscle Hypertrophy
- Cardio
- Yoga
- Exercise Science
- Weight Loss
- Health & Nutrition
- Resistance Training

---

# 🎯 Future Improvements

- User Authentication
- Workout History
- Personalized Workout Plans
- Exercise Progress Dashboard
- Diet Recommendation System
- Multi-Exercise Detection
- Cloud Deployment
- Mobile Application

---

# 📷 Screenshots

> Add screenshots or GIFs here demonstrating:
>
> - Squat Detection
> - Live Angle Tracking
> - AI Chatbot
> - Virtual Assistant

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/arinwalwaikar/FitVisor.git
```

Navigate into the project

```bash
cd FitVisor
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the required modules

```bash
python app.py
```

---

# 📌 Applications

- AI Fitness Coaching
- Home Workout Assistant
- Posture Correction
- Smart Exercise Monitoring
- Educational Fitness Platform

---

# 👨‍💻 Author

**Arin Walwaikar**

GitHub: https://github.com/arinwalwaikar