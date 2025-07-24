nano README.md
# 🏊‍♂️ Swimming Assistant

A lightweight AI-based swimming assistant built in Python that tracks swim sessions, uses fatigue feedback to adapt suggestions, and provides visual summaries.

## Features
- Log swim sessions (distance, type, fatigue)
- Get adaptive feedback using RL-style logic
- View weekly performance plots
- JSON-based local data storage

## How to Run
```bash
python swimming_assistant.py

Save and exit (in nano, press `CTRL + O` → Enter → `CTRL + X`).

---

### 2.2 Create `.gitignore`
This tells Git to ignore unnecessary files.

```bash
nano .gitignore
__pycache__/
*.pyc
*.json
