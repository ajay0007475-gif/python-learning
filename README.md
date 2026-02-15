🐍 Python Learning Repository

A structured and professional Python learning repository built using VS Code, Anaconda, and Jupyter Notebook.

This project follows real-world Git workflow practices including branching, clean commits, and environment management.

📌 Project Objective

Learn Python fundamentals step by step

Maintain clean project structure

Practice professional Git workflow

Make the repository beginner-friendly and reproducible

🛠 Tech Stack

Python 3.12

Anaconda

VS Code

Jupyter Notebook

Git & GitHub

📂 Project Structure
python-learning/
│
├── python_basics/
│ ├── 01_variables.ipynb
│ ├── 02_datatypes.ipynb
│ └── ...
│
├── app.py
├── requirements.txt
├── .gitignore
└── README.md

🚀 Getting Started (Setup Guide)

Follow these steps to run the project locally.

1️⃣ Install Required Software

Download and install:

VS Code
https://code.visualstudio.com/

Anaconda
https://www.anaconda.com/products/distribution

After installation, open:

Anaconda Prompt

2️⃣ Clone the Repository
git clone https://github.com/ajay0007475-gif/python-learning.git
cd python-learning

3️⃣ Create Virtual Environment
conda create -p venv python=3.12

Press Y when prompted.

4️⃣ Activate Virtual Environment
conda activate ./venv

You should now see:

(venv)

This means the environment is active.

5️⃣ Install Required Dependencies
pip install -r requirements.txt

6️⃣ Register Jupyter Kernel
python -m ipykernel install --user --name=venv --display-name "Python 3.12 (venv)"

7️⃣ Run Jupyter Notebook
jupyter notebook

Or open .ipynb files directly in VS Code.

8️⃣ Select Environment in Notebook

Inside the notebook:

Click Kernel (Top Right)

Select: Python 3.12 (venv)

Test with:

print("Hello World!")

If it runs → Setup Successful ✅

🔄 Development Workflow

This project follows a professional Git workflow:

Create a new feature branch
git checkout -b feature/topic-name

Commit changes
git add .
git commit -m "Add topic explanation and examples"

Push branch
git push origin feature/topic-name

Create Pull Request on GitHub
📦 Why Virtual Environment?

Keeps project dependencies isolated

Prevents version conflicts

Makes project reproducible

Follows industry best practices

🎯 Future Improvements

Add Python intermediate topics

Add small practice projects

Add unit testing examples

Improve documentation

👨‍💻 Author

Ajay Kumar

Learning Python with professional development practices 🚀
