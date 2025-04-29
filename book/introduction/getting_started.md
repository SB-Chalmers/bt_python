---
marp: true
---
# Getting Started with Python

Welcome to the Python course book! This guide will help you get started with Python, understand its background, and explore the different ways you can use it for your projects.

---

## What is Python?

Python is a high-level, interpreted programming language known for its simplicity and readability. It was created by Guido van Rossum and first released in 1991. Python emphasizes code readability and allows programmers to express concepts in fewer lines of code compared to other languages.

---

## A Brief History

- **1991:** Python 0.9.0 released by Guido van Rossum.
- **2000:** Python 2.0 introduced new features like list comprehensions and garbage collection.
- **2008:** Python 3.0 released, focusing on removing redundant constructs and improving consistency.

Python has grown rapidly in popularity due to its versatility, large community, and extensive libraries.

---

## Why is Python Popular?

- **Easy to Learn:** Simple, readable syntax.
- **Versatile:** Used in web development, data science, automation, AI, and more.
- **Large Ecosystem:** Thousands of libraries and frameworks.
- **Strong Community:** Extensive documentation and support.

---

## Python Versions

There are two main versions:
- **Python 2.x:** Legacy version, no longer maintained.
- **Python 3.x:** Actively developed and recommended for all new projects.

Always use the latest Python 3.x version unless you have a specific reason to use Python 2.

---

## Ways to Use Python

You can run Python code in several ways:
- **Interactive Shell:** Type `python` in your terminal to execute code line by line.
- **Script Files (.py):** Write code in a `.py` file and run it with `python filename.py`.
- **Notebooks:** Interactive documents that combine code, text, and visualizations (see below).
- **Online Platforms:** Use services like Google Colab or JupyterHub to run Python in your browser.

---

## IDEs and Environments

- **IDE (Integrated Development Environment):** A software application that provides tools for writing, testing, and debugging code. Popular Python IDEs include PyCharm, VS Code, and Thonny.
- **Text Editors:** Lightweight editors like Sublime Text or Atom can also be used.
- **Environments:** Virtual environments (using `venv` or `conda`) help manage dependencies and avoid conflicts between projects.

---

## Running Python Online

- **Google Colab:** Free, cloud-based Jupyter notebook environment. No installation required.
- **Jupyter Notebooks:** Run locally or on cloud services. Great for data analysis and visualization.
- **Repl.it:** Online IDE supporting Python and many other languages.

---

## What is a Notebook?

A **notebook** (like Jupyter or Colab) is an interactive document that allows you to mix code, text, images, and visualizations. Notebooks are ideal for:
- Experimenting with code
- Documenting your workflow
- Sharing results with others

---

### Notebook vs. .py File

| Feature         | Notebook (.ipynb)         | Python Script (.py)      |
|-----------------|--------------------------|--------------------------|
| Interactivity   | High (run cells)         | Low (run whole file)     |
| Documentation   | Supports rich text/markdown | Comments only           |
| Visualization   | Inline display           | Separate window/output   |
| Use Case        | Data analysis, teaching  | Application development  |

---


## Getting Started Checklist

1. **Install Python 3:** Download from [python.org](https://www.python.org/downloads/).
2. **Choose an IDE or Editor:** Either use Google Colab [colab.research.google](https://colab.research.google.com/) or install VSCode from [code.visualstudio](https://code.visualstudio.com/)

**Note:** Google colab is a ready-to-use editor but it can be limiting in the long term. The steps below that use VSCode are a more robust solution. If you do go with VSCode continue with the instructions below.


---

Here's a revised and polished version of your text with grammar fixes, improved clarity, and consistent formatting:

---

3. **Install Anaconda:**  
Download and install [Anaconda](https://www.anaconda.com/). Anaconda is a tool that allows you to manage your Python environments. A Python environment is simply a separate installation of Python that lets you have multiple versions and sets of libraries side by side. As you work on multiple projects over time, you may encounter conflicts between specific versions of Python and certain libraries. Anaconda helps you manage these conflicts by maintaining clean, isolated Python installations on the same computer.

4. **Set Up a GitHub Account:**  
Create a free GitHub account at [GitHub](https://github.com/). We'll use GitHub to access notebooks and files for this course and to practice best practices for documenting and managing our projects.

5. **Install GitHub Desktop (Optional):**  
Download the [GitHub Desktop client](https://github.com/apps/desktop). This application allows you to manage projects without using the command line. While this step is optional, GitHub Desktop can be a helpful tool for beginners. Over time, you may find yourself using it less frequently as you become more comfortable with Git and GitHub.

6. **Connect Visual Studio to GitHub Copilot:**  
Follow the instructions [here](https://visualstudio.microsoft.com/github-copilot/) to connect Visual Studio to GitHub Copilot. While this workshop does not directly use ChatGPT, Copilot gives you access to AI-powered code suggestions and explanations. This feature can help boost your productivity, especially in independent projects, and can make coding feel less daunting or isolating.

7. **Set Up a Virtual Environment:**  
Follow [this tutorial](https://www.anaconda.com/docs/tools/anaconda-navigator/tutorials/manage-environments) or run the command below in your terminal to create a virtual environment for this course:  
```bash
conda create -n btpython python=3.11 anaconda
conda activate btpython
```
This virtual environment ensures that the customizations we apply in this course won’t interfere with your other Python projects.


---

You're now ready to start your Python journey!
