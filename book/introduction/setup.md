---
marp: true
---

# Setting Up Your Python Development Environment

This guide will walk you through installing Python, setting up Anaconda, configuring VS Code, and preparing your system for Python development. We'll also cover setting up GitHub and GitHub Desktop for version control and collaboration.

---

## 1. Installing Python

### Option A: Install from python.org

1. Go to the [official Python downloads page](https://www.python.org/downloads/).
2. Download the latest Python 3.x installer for your operating system (Windows, macOS, or Linux).

---

3. Run the installer:
   - **Windows:** Check "Add Python to PATH" before clicking "Install Now".
   - **macOS/Linux:** Follow the prompts; you may need to use `sudo` on Linux.
4. Verify installation:
   ```sh
   python --version
   ```
   or
   ```sh
   python3 --version
   ```

---

### Option B: Install with Anaconda

[Anaconda](https://www.anaconda.com/products/distribution) is a popular Python distribution that includes Python, many scientific libraries, and the `conda` package manager.

1. Download the Anaconda installer for your OS from the [Anaconda Distribution page](https://www.anaconda.com/products/distribution).
2. Run the installer and follow the instructions.

---

3. After installation, open the **Anaconda Navigator** or use the **Anaconda Prompt** (Windows) or terminal (macOS/Linux).
4. Verify installation:
   ```sh
   conda --version
   python --version
   ```

---

#### Why Use Anaconda?

- Simplifies package management and deployment.
- Comes with Jupyter Notebook, Spyder, and many data science libraries pre-installed.
- Great for data science, machine learning, and scientific computing.

---

## 2. Setting Up a Virtual Environment

Virtual environments help isolate project dependencies.

### Using `conda` (Anaconda)

```sh
conda create -n myenv python=3.11
conda activate myenv
```

---

## 3. Installing Visual Studio Code (VS Code)

[VS Code](https://code.visualstudio.com/) is a free, powerful code editor.

1. Download and install from [code.visualstudio.com](https://code.visualstudio.com/).
2. Launch VS Code.
3. Install the **Python extension** (search for "Python" in the Extensions sidebar).
4. (Optional) Install the **Jupyter extension** for notebook support.

---

## 4. Setting Up GitHub and GitHub Desktop

### Create a GitHub Account

1. Go to [github.com](https://github.com/).
2. Click **Sign up** and follow the instructions.

### Install GitHub Desktop

1. Download from [desktop.github.com](https://desktop.github.com/).
2. Install and launch GitHub Desktop.
3. Sign in with your GitHub account.

---

## 5. Downloading the workshop files

With GitHub Desktop or Git, you can clone repositories to your local machine.

**Using GitHub Desktop:**
1. Click "clone a repository from the internet" and then .
2. Paste the repository URL and choose a local path.

**Using Git:**
```sh
git clone https://github.com/SB-Chalmers/bt_python.git
```
---
