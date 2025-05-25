# 🤖 Crew Real-Time AI Agent System

![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Python](https://img.shields.io/badge/python-3.11-blue)

---

## 📌 Overview

**Crew Real-Time** is a Python-based application that uses the `crewai` library to simulate a real-time collaboration system between multiple AI agents. These agents work like digital coworkers — performing tasks, sharing info, and making decisions together. 🧠🤝

Even if you're from a non-technical background, imagine this as building a **digital teamwork bot** that organizes a group of AIs to solve a problem collaboratively.

---

## 🧠 Key Concepts

| Concept        | What It Means (Simple Terms)                                                                                                                                 |
|----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **AI Agent**   | Like a virtual team member who can read instructions, act, and talk to others.                                                                               |
| **CrewAI**     | A platform to manage multiple AI agents working together like a crew on a ship.                                                                              |
| **Real-Time**  | Agents respond instantly to events or tasks, just like how a real crew would operate together on-the-go.                                                     |
| **Roles & Tasks** | Each agent has a role (e.g., researcher, planner, reporter) and they complete tasks while talking to each other.                                          |

---

## 🛠️ How It Works

This notebook sets up:

- A crew of intelligent agents using `crewai`
- Real-time task delegation across these agents
- Collaboration logic where agents communicate and complete tasks
# Clone the project
git clone https://github.com/yourusername/crew-real-time.git
cd crew-real-time

# Set up virtual environment (optional)
python -m venv venv
source venv/bin/activate  # or venv\\Scripts\\activate on Windows

# Install dependencies
pip install -r requirements.txt

### 🧬 Libraries Used

```python
crewai
appdirs
auth0-python
chromadb
json-repair
instructor

