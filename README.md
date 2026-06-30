# 🧠 Context-Aware Smart To-Do List

> **Stop manually prioritizing. Let the algorithm do the heavy lifting.**

A minimalist CLI (Command Line Interface) task manager that doesn't just store your tasks—it **intelligently sorts** them by a dynamic priority score based on how soon they are due and how much effort they require. Built purely with Python and JSON, it’s perfect for developers who live in the terminal.

---

## ✨ Features

### Core MVP
- **➕ Add Tasks:** Create tasks with a title, due date (YYYY-MM-DD), and estimated effort (1–5 scale).
- **🧮 Auto-Priority Scoring:** Calculates a unique `Priority Score` for every task using a weighted algorithm.
- **📊 Sorted Output:** View your entire to-do list sorted from "Must do now" to "Can do later".
- **✅ Mark as Done:** Complete tasks and instantly move them to a local archive.
- **💾 Persistent Storage:** All tasks are saved locally in a `tasks.json` file—no database setup required.
- **📁 Archive History:** Finished tasks are moved to `archive.json` so you never lose your history.

### 🚀 Stretch Goals (Coming Soon)
- [ ] Pomodoro timer integration to log work sessions per task.
- [ ] CLI autocomplete for recurring task titles.
- [ ] Export weekly reports as a CSV file.

---

## 🛠️ Tech Stack

- **Language:** Python 3.8+
- **Data Storage:** JSON (file-based, no external DB)
- **Date Handling:** `datetime` (standard library)
- **Dependencies:** Zero! (Uses only Python's standard library).

---

## 📦 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites
- Python 3.8 or higher installed on your system.
- (Optional) `pip` for future dependency management.

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/your-username/smart-todo-cli.git
    cd smart-todo-cli
