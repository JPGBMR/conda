# Environment Setup: Conda & Pip
Comprehensive guide to setting up Python virtual environments using **Conda** and **Pip**.

---

## Table of Contents:
1. [Prerequisites](#prerequisites)
2. [Conda Environment Setup](#conda-environment-setup)
   - [Create](#create-conda)
   - [Activate](#activate-conda)
   - [Install](#install-conda)
3. [Pip Environment Setup](#pip-environment-setup)
   - [Create](#create-pip)
   - [Activate](#activate-pip)
   - [Install](#install-pip)
4. [Summary](#summary)
5. [Contributing](#contributing)
6. [License](#license)

---

## Prerequisites
Before setting up an environment, ensure you have the necessary tools installed:

### Conda:
- Install [Miniconda](https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html) or [Anaconda](https://www.anaconda.com/).
- Verify installation:
  ```bash
  conda --version
  conda deactivate
  conda create --name test-env
  conda activate test-env
  conda install python=3.9 pyautogui numpy pillow
  conda update --all
  
### Pip activate
```bash
python -m venv test-env
# Activate the virtual environment:
# Windows: test-env\Scripts\activate
# Mac/Linux: source test-env/bin/activate
pip install --upgrade pip
pip install pyautogui numpy pillow
pip install --upgrade [library_name]  # (Optional for updates)
