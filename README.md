

# 🧬 Teach-the-Tutor: Biology Active Recall Coach

<div align="center">

![Version](https://img.shields.io/badge/Version-1.0.0-blue)
![Python](https://img.shields.io/badge/Python-3.11-yellow?logo=python)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?logo=typescript)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript)
![Shell](https://img.shields.io/badge/Shell-Bash-121011?logo=gnu-bash)
![Dockerfile](https://img.shields.io/badge/Dockerfile-Ready-0db7ed?logo=docker)
![License](https://img.shields.io/badge/License-MIT-green)

**An AI-powered Active Recall Coach that helps biology students learn, quiz, and teach-back concepts through real-time voice interaction.
Built for the #MurfAIVoiceAgentsChallenge.**

[Features](#-features) • [Project-Structure](#️-project-structure) • [Quick-Start](#-quick-start) • [Demo-Video](#-demo-video) • [Author](#-author)

</div>

---

# 🧬 Teach-the-Tutor: Biology Voice Learning Companion

*A smart biology tutor that explains concepts, quizzes you, and evaluates your “teach-back” — helping you master biology using proven Active Recall.*

---

## 📌 Overview

Biology is memory-heavy: diagrams, cycles, definitions, mechanisms, NCERT facts — everything must be remembered and understood clearly.

This project is a **voice-based Active Recall Coach** designed for:

✔️ NEET Aspirants
✔️ Class 11–12 Biology Students
✔️ B.Sc. Life Science Students
✔️ Anyone wanting to deeply understand biology

The AI coach follows a **3-step learning system**:

### **1️⃣ Learn Mode**

Explains any biology topic simply (Cell Division, Genetics, Photosynthesis, Human Physiology, etc.)

### **2️⃣ Quiz Mode**

Asks MCQs and short-answer questions to check your retention.

### **3️⃣ Teach-Back Mode**

You explain the concept — and the AI gives feedback like a real tutor.


https://github.com/user-attachments/assets/ccaece6d-1e8a-4c35-b893-ae8ccf6d54d8


---

## 🎥 Demo Video

(Replace with your link)

📎 https://drive.google.com/file/d/1uPmIqE8OVfHCjjbNrZhUWbfQ-GW85apC/view?usp=vids_web

---

## 🎯 Features

### **✔ Concept Explanation (Learn Mode)**

* Simplified explanations for all biology chapters
* Includes diagrams (verbal), examples, and keywords
* Follows NCERT-aligned structure

### **✔ Quiz Mode for Active Recall**

* MCQ, one-word, and 3-line answer questions
* Randomized or topic-based quizzes
* Immediate feedback

### **✔ Teach-Back Analysis**

* You explain the concept
* AI scores clarity, key terms, and accuracy
* Gives improvement suggestions

### **✔ Session Memory (JSON Persistence)**

Stores:

* Topics studied
* Quiz performance
* Previous mistakes
* Teach-back scores

The agent uses past data to adapt future sessions.

### **✔ Grounded & Safe**

* No medical advice
* No misinformation
* Only academic biology learning support

---

## 🛠️ Tech Stack

* **Python**
* **TypeScript**
* **Murf Falcon Voice Models**
* **JSON Storage**
* **Docker (Optional)**
* **Speech-to-Text + Text-to-Speech**

---

## 📁 Project Structure

```
/Teach-the-Tutor-Biology-Voice-AI
│
├── src/
│   ├── agent.py
│   ├── active_recall.py
│   ├── memory_manager.py
│   ├── quiz_bank.json
│   └── biology_topics/
│
├── logs/
│   └── session_memory.json
│
├── requirements.txt
├── docker-compose.yml
└── README.md
```

---

## ⚙️ Quick Start

### **1. Clone the Repo**

```bash
git clone https://github.com/yourusername/Teach-the-Tutor-Biology.git
cd Teach-the-Tutor-Biology
```

### **2. Install Dependencies**

```bash
pip install -r requirements.txt
```

### **3. Run the Biology Voice Tutor**

```bash
python src/agent.py
```

---

## 🧪 Sample JSON Output

```json
{
  "date": "2025-11-25",
  "topic": "Cell Cycle - Mitosis",
  "quiz_score": 4,
  "teach_back_accuracy": "78%",
  "notes": "User understood prophase and metaphase well. Needs clarity on anaphase."
}
```

---

## 🚀 Future Improvements

* Add diagram image support
* Adaptive difficulty quizzes
* Biology formula sheet generator
* NEET weekly full-length mock tests
* Web dashboard to view progress

---
<img width="1920" height="1080" alt="Screenshot (132)" src="https://github.com/user-attachments/assets/c969c9c5-3e03-4631-a54d-00cccdd26857" />

## 👨‍💻 Author

**Om Gedam**

**GitHub:** @itsomg134
**Email:** [omgedam123098@gmail.com](mailto:omgedam123098@gmail.com)
**Twitter (X):** @omgedam
**LinkedIn:** Om Gedam
**Portfolio:** [https://ogworks.lovable.app](https://ogworks.lovable.app)

Built with ❤️ for every biology learner.

<img width="1280" height="720" alt="Brown and Beige Modern AI Features YouTube Thumbnail" src="https://github.com/user-attachments/assets/961a7098-41f2-4f87-aaf3-b2643e7b160d" />

