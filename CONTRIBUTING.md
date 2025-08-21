# 🤝 Contributing to AI-Fashion Lab @ NPUST

Thank you for your interest in contributing to the **AI-Fashion Lab**!  
This document outlines the process and best practices for contributing to our repositories.

---

## 🧭 How You Can Contribute
- 📘 **Documentation**: Fix typos, improve clarity, or add tutorials.  
- 🔬 **Research Projects**: Submit code, experiments, or trained models.  
- 📊 **Datasets**: Add new data preprocessing scripts or annotations.  
- 🛠️ **Tools**: Build evaluation utilities or visualization dashboards.  

---

## 📂 Repository Structure
Each project repository follows this general layout:

````

project-name/
├── data/               # Datasets (not pushed to GitHub if large)
├── src/                # Source code
├── notebooks/          # Jupyter notebooks
├── results/            # Logs, visualizations, checkpoints
├── requirements.txt    # Dependencies
└── README.md           # Project documentation

````

---

## 🚀 Contribution Workflow

1. **Fork** the repository to your GitHub account.
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
    ```

3. **Create a new branch**:

   ```bash
   git checkout -b feature/my-feature
   ```
4. **Make changes** and commit:

   ```bash
   git add .
   git commit -m "Add: new color clustering module"
   ```
5. **Push** to your fork:

   ```bash
   git push origin feature/my-feature
   ```
6. **Open a Pull Request (PR)** on the original repo:

   * Describe the changes clearly.
   * Link any relevant issue or discussion.
   * Ensure CI checks/tests pass.

---

## ✅ Code Style Guidelines

* Use **Python 3.10+**.
* Follow **PEP8** style (lint with `flake8` or `black`).
* Write **docstrings** for all functions/classes.
* Include **examples** where helpful.

---

## 🧪 Testing

* Each new feature should include a test script or notebook.
* Run all tests before submitting a PR:

  ```bash
  pytest
  ```

---

## 📝 Commit Messages

Use clear, descriptive commit messages:

* `Fix: typo in dataset loader`
* `Add: YOLOv8 segmentation training pipeline`
* `Update: documentation for color calibration`

---

## 🔐 Access Rules

* Interns contribute under the `Interns-2025` team.
* Supervisors have final approval on merging PRs.
* Sensitive/private datasets must **not** be uploaded.

---

## 💡 Tips for Interns

* Start with issues labeled **good first issue**.
* Document your weekly progress in the `internship-2025-summer` repo.
* Don’t hesitate to ask for guidance in Discussions/Issues.

---

## 📜 License

By contributing, you agree that your code will be released under the repository’s license (usually **MIT**).
