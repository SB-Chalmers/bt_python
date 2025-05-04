---
marp: true
---

# Setting Up Your Python Development Environment

This guide will walk you through installing Python, setting up Anaconda, configuring VS Code, and preparing your system for Python development. We'll also cover setting up GitHub and GitHub Desktop for version control and collaboration.

---


# Installing Python

---

## 1. **Where to write code:** 
For the absolute easiest way to start you should use Google Colab [colab.research.google](https://colab.research.google.com/). If you are comfortable with getting more hands-on and want to save and run your code locally on your computer, install VSCode from [code.visualstudio](https://code.visualstudio.com/)

**Note:** Google colab is a ready-to-use editor but it can be limiting in the long term. The steps below that use VSCode are a more robust solution. If you do go with VSCode continue with the instructions below.


---

## 2. **Install Anaconda Navigator (optional):**  

Download and install [Anaconda navigator](https://www.anaconda.com/). Anaconda is a tool that allows you to manage your Python environments. A Python environment is simply a separate installation of Python that lets you have multiple versions and sets of libraries side by side. 

As you work on multiple projects over time, you may encounter conflicts between specific versions of Python and certain libraries. Anaconda helps you manage these conflicts by maintaining clean, isolated Python installations on the same computer (There are other ways of doing this using `venv`, but conda is a very easy way to do this).

---


1. Download the Anaconda installer for your OS from the [Anaconda Distribution page](https://www.anaconda.com/products/distribution).
2. Run the installer and follow the instructions.
3. After installation, open the **Anaconda Navigator** or use the **Anaconda Prompt** (Windows) or terminal (macOS/Linux).
4. Verify installation:


   ```sh
   conda --version
   python --version
   ```

---

## *Why Use Anaconda?*

- Simplifies package management and deployment.
- Comes with Jupyter Notebook and many data science libraries pre-installed.
- Great for data science, machine learning, and scientific computing.

---

## 3. **Set Up a GitHub Account:**  
Create a free GitHub account at [GitHub](https://github.com/). We'll use GitHub to access notebooks and files for this course and to practice best practices for documenting and managing our projects.

---

## 4. **Install GitHub Desktop (Optional):**  
Download the [GitHub Desktop client](https://github.com/apps/desktop). This application allows you to manage projects without using the command line. While this step is optional, GitHub Desktop can be a helpful tool for beginners. Over time, you may find yourself using it less frequently as you become more comfortable with Git and GitHub. Installing the GitHub desktop client also installs `git`, the version control software that forms the backbone of github.

---

## 5. **Connect Visual Studio to GitHub Copilot:**  
Follow the instructions [here](https://visualstudio.microsoft.com/github-copilot/) to connect Visual Studio to GitHub Copilot. While this workshop does not directly use ChatGPT, Copilot gives you access to AI-powered code suggestions and explanations. This feature can help boost your productivity, especially in independent projects, and can make coding feel less daunting or isolating.

---

## 6. **Set Up a Virtual Environment:**  
Follow [this tutorial](https://www.anaconda.com/docs/tools/anaconda-navigator/tutorials/manage-environments) or run the command below in your terminal to create a virtual environment for this course:  
```bash
conda create -n btpython python=3.11
conda activate btpython
```

--- 
`conda` calls the conda application installed on your computer.
`create` is the first command, instructing conda to create a virtual environment.
`-n` is called a flag. "n" stands for new, suggesting that we want to create a "new" virtual environment.
`btpython` This is a custom name that we want to call our python environment.
`python=3.11` Specifies the version of python to be downloaded from the internet.

`conda` We are calling the conda application again.
`activate` the first command, instructing conda that we want to activate a virtual environment .
`btpython` the name of the environment we want to activate.

---

This virtual environment ensures that the customizations we apply in this course won’t interfere with your other Python projects.


---

# You're now ready to start your Python journey!
