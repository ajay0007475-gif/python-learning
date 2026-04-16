# 🐍 Python Learning Repository

A structured and professional Python learning repository built using **VS Code, Anaconda, and Jupyter Notebook**.

This project follows **real-world Git workflows** including:

* Feature branching
* Clean commits
* Pull Requests (PRs)
* Structured learning modules

---

## 📌 Project Objective

* Learn Python fundamentals step by step
* Maintain a clean and scalable project structure
* Practice **industry-standard Git workflow**
* Make the repository beginner-friendly and reusable

---

## 🛠 Tech Stack

* Python 3.12
* Anaconda
* VS Code
* Jupyter Notebook
* Git & GitHub

---

## 📂 Project Structure

```bash
python-learning/
│
├── python_basics/
│   ├── data types.ipynb
│   ├── variables.ipynb
│   ├── Operators.ipynb
│   ├── python_introduction.ipynb
│   ├── python_prerequisite.ipynb
│   ├── keywords.ipynb
│   ├── 07_conditionals.ipynb
│   ├── 08_for_loops.ipynb
│   ├── 09_while_loops.ipynb
│   ├── 10_loop_control.ipynb
│
├── Data_Structures/
│   ├── Data_structures.ipynb
│   ├── List.ipynb
│   ├── tuples.ipynb
│   ├── Sets.ipynb
│   ├── Dictionary.ipynb
│
├── app.py
├── requirements.txt
├── .gitignore
└── README.md
```

---

## ⚠️ Structure Note (Important)

This repository contains notebooks created in **two phases**:

### 🔹 Phase 1 — Initial Learning

* Files may have inconsistent naming (spaces, casing)
* Focus was on learning concepts

### 🔹 Phase 2 — Structured Learning

* Numbered notebooks (07, 08, etc.)
* Clean naming conventions
* One topic per file
* Follows professional standards

👉 This approach avoids breaking Git history while improving structure progressively.

---

## 🚀 Getting Started (Setup Guide)

### 1️⃣ Install Required Software

* VS Code
  https://code.visualstudio.com/

* Anaconda
  https://www.anaconda.com/products/distribution

---

### 2️⃣ Clone the Repository

```bash
git clone https://github.com/ajay0007475-gif/python-learning.git
cd python-learning
```

---

### 3️⃣ Create Virtual Environment

```bash
conda create -p venv python=3.12
```

---

### 4️⃣ Activate Environment

```bash
conda activate ./venv
```

---

### 5️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 6️⃣ Register Jupyter Kernel

```bash
python -m ipykernel install --user --name=venv --display-name "Python 3.12 (venv)"
```

---

### 7️⃣ Run Notebook

```bash
jupyter notebook
```

Or open `.ipynb` files in VS Code.

---

### 8️⃣ Select Kernel

Inside notebook:

* Click **Kernel (top right)**
* Select: `Python 3.12 (venv)`

Test:

```python
print("Hello World!")
```

---

## 🔄 Development Workflow (Professional)

### 1️⃣ Create Feature Branch

```bash
git checkout -b topic/<topic-name>
```

Example:

```bash
git checkout -b topic/sets
```

---

### 2️⃣ Stage Changes (Intentional)

```bash
git add python_basics/07_conditionals.ipynb
```

---

### 3️⃣ Commit (Structured Message)

```bash
git commit -m "feat: add conditional statements notebook

- Covered if, elif, else concepts
- Added real-world examples
- Included practice problems"
```

---

### 4️⃣ Push Branch

```bash
git push origin topic/<topic-name>
```

---

### 5️⃣ Create Pull Request (GitHub)

Include:

* Summary
* Changes
* Purpose

---

### 6️⃣ Merge Strategy

👉 Use **Squash & Merge**

✔ Keeps history clean
✔ Avoids unnecessary commits

---

### 7️⃣ Cleanup

```bash
git checkout main
git pull origin main
git branch -d topic/<topic-name>
git push origin --delete topic/<topic-name>
```

---

## 📦 Why Virtual Environment?

* Isolates dependencies
* Prevents version conflicts
* Ensures reproducibility
* Follows industry standards

---

## 🎯 Future Improvements

* Add intermediate Python topics
* Add mini projects
* Add unit testing (pytest)
* Add interview-focused content
* Improve documentation further

---

## 👨‍💻 Author

**Ajay Kumar**

Learning Python with **real-world engineering practices** 🚀
