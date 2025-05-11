# DevOps CI/CD Pipeline with GitHub Actions and Tekton

This repository demonstrates a CI/CD pipeline using **GitHub Actions** for continuous integration and **Tekton Pipelines** for deployment orchestration.

## 📁 Repository Structure

```
.
├── .github/
│   └── workflows/
│       └── workflow.yml          # GitHub Actions CI pipeline
├── .tekton/
│   └── tasks.yml                 # Tekton tasks for test and cleanup
├── README.md                     # Project overview
```

## ⚙️ GitHub Actions Workflow

The GitHub Actions workflow runs automatically on every push or pull request. It includes:

* ✅ **Linting** with `flake8`
* ✅ **Unit Testing** with `nose`

View the workflow file here:
[.github/workflows/workflow.yml](.github/workflows/workflow.yml)

## 🔧 Tekton Tasks

Defined in `.tekton/tasks.yml`, including:

* 🧪 `run-nose-tests`: Runs Python unit tests using `nosetests`
* 🧹 `cleanup-workspace`: Cleans up temporary files after execution

## 🚀 Goals

* Demonstrate integration of CI (GitHub Actions) and CD (Tekton)
* Provide a lightweight Python example for DevOps learners
* Submit deliverables for CI/CD course assignments

## 🛠 Requirements

* Python 3.10+
* GitHub Actions enabled
* Optional: OpenShift Developer Sandbox for Tekton testing

## ✅ Author

**Noor Uddin**
GitHub: [@noorcs39](https://github.com/noorcs39)
