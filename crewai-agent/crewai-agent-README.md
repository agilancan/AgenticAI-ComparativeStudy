# CrewAI Agent – Meeting Preparation Assistant

This agent uses the **CrewAI** framework to simulate a multi-role virtual team that prepares you for business meetings by researching participants, analyzing industry trends, generating strategy, and summarizing everything in a briefing report.

---

## 📌 Use Case

**Scenario:** You're about to meet Apple executives to discuss switching your company from Windows to macOS.  
This agent team helps prepare by:
- Researching Apple and its reps
- Analyzing current industry trends
- Crafting strategy points and questions
- Summarizing all insights in a briefing

---

## 🧠 Agent Architecture

| Agent Role            | Task Description |
|------------------------|------------------|
| 🕵️ Researcher          | Looks up info on attendees & companies |
| 📊 Industry Analyst     | Summarizes relevant trends & challenges |
| 🧠 Strategy Advisor     | Creates strategic talking points |
| 📝 Briefing Coordinator | Compiles everything into a summary report |

---

## 🔧 Tools Used

- **Exa API** (search, fetch content, find similar)
- **OpenAI GPT-3.5/4**
- Custom Python tools integrated with CrewAI decorators

---

## 🗂️ Files

- `main.py`: Entry point that runs the whole agent workflow
- `agents.py`: Defines roles, goals, tools, and backstories
- `tools.py`: Connects with Exa and external APIs
- `tasks.py`: Modular task functions for each stage

---

## 📸 Demo (screenshot/video placeholder)

<p align="center"><img src="assets/Screenshot 2025-07-16 185827.png" width="1920"/></p>

---
