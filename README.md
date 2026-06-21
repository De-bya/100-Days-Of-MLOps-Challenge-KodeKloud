# 🚀 100 Days of MLOps Challenge — KodeKloud

![MLOps](https://img.shields.io/badge/MLOps-Challenge-blue?style=for-the-badge)
![Days](https://img.shields.io/badge/Days-100-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-In%20Progress-orange?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-KodeKloud-purple?style=for-the-badge)
![Progress](https://img.shields.io/badge/Progress-30%2F100-yellow?style=for-the-badge)

> A hands-on 100-day journey to master MLOps — from Python environments and model training to CI/CD pipelines, containerization, model serving, and production monitoring.

---

## 📌 About This Challenge

This repository documents my solutions and notes for the **100 Days of MLOps Challenge** on [KodeKloud](https://kodekloud.com). Each day covers a practical lab task designed to build real-world MLOps skills, progressing from foundational Python and ML tooling all the way to advanced production deployment pipelines on Kubernetes.

Every solution file follows a consistent structure: **Problem → Solution → Key Takeaways**, making this repository a reference I can return to long after the challenge ends.

---

## 🗂️ Repository Structure

```
100-Days-Of-MLOps-Challenge/
├── README.md
├── days/
│   ├── 001.md
│   ├── 002.md
│   └── ...100.md
└── assets/
    └── screenshots/
```

---

## 🗺️ Challenge Roadmap

The 100 days are organized into 9 progressive phases:

### 🐍 Phase 1 — Python & ML Tooling (Days 1–9)
| Day | Topic | Status |
|-----|-------|--------|
| 01 | Create a Python Virtual Environment for ML | ✅ Done |
| 02 | Set Up and Configure Jupyter Notebook Server | ✅ Done |
| 03 | Fix a Broken uv Lockfile Specification | ✅ Done |
| 04 | Create a Standard ML Project Structure | ✅ Done |
| 05 | Create a Makefile for ML Workflow Automation | ✅ Done |
| 06 | Set Up Code Quality Tools for ML Code | ✅ Done |
| 07 | Package an ML Project as Installable Python Package | ✅ Done |
| 08 | Configure Pre-Commit Hooks for ML Repository | ✅ Done |
| 09 | Create a Custom ML Project Template with Cookiecutter | ✅ Done |

### 📦 Phase 2 — Data Version Control with DVC (Days 10–19)
| Day | Topic | Status |
|-----|-------|--------|
| 10 | Install and Initialize DVC in an ML Project | ✅ Done |
| 11 | Track a Dataset with DVC | ✅ Done |
| 12 | Configure a DVC Remote Storage | ✅ Done |
| 13 | Pull DVC-Tracked Data from Remote | ✅ Done |
| 14 | Create a DVC Pipeline for Data Processing | ✅ Done |
| 15 | Parameterize a DVC Pipeline | ✅ Done |
| 16 | Track ML Metrics with DVC | ✅ Done |
| 17 | Run and Compare DVC Experiments | ✅ Done |
| 18 | Version Datasets and Models Across Git Branches | ✅ Done |
| 19 | Build Complete DVC ML Pipeline with Remote Storage | ✅ Done |

### 🔬 Phase 3 — Experiment Tracking with MLflow (Days 20–30)
| Day | Topic | Status |
|-----|-------|--------|
| 20 | Install and Start the MLflow Tracking Server | ✅ Done |
| 21 | Log an ML Experiment to MLflow | ✅ Done |
| 22 | Create and Organize MLflow Experiments | ✅ Done |
| 23 | Search and Tag MLflow Runs | ✅ Done |
| 24 | Enable MLflow Autologging | ✅ Done |
| 25 | Register, Version, and Manage Model Lifecycle | ✅ Done |
| 26 | Compare Model Runs and Select the Best | ✅ Done |
| 27 | Load Model from Registry with Custom Preprocessing | ✅ Done |
| 28 | Fix a Broken MLflow Project and Re-Run It | ✅ Done |
| 29 | Configure MLflow with Remote Tracking Server and Artifact Store | ✅ Done |
| 30 | End-to-End MLflow Lifecycle: Train, Register, Serve, Monitor | ✅ Done |

### 🏋️ Phase 4 — Model Training & Tuning (Days 31–40)
| Day | Topic | Status |
|-----|-------|--------|
| 31 | Train a Scikit-Learn Model with Reproducible Script | 🔒 Locked |
| 32 | Manage Training Configuration with YAML | 🔒 Locked |
| 33 | Evaluate a Trained Model and Generate Classification Report | 🔒 Locked |
| 34 | Implement Cross-Validation for Model Selection | 🔒 Locked |
| 35 | Hyperparameter Tuning with Optuna | 🔒 Locked |
| 36 | Automated Model Selection with FLAML AutoML | 🔒 Locked |
| 37 | Distributed Model Training with Joblib Parallelization | 🔒 Locked |
| 38 | Build Modular Training Pipeline with Config-Driven Stages | 🔒 Locked |
| 39 | Train a PyTorch Model with GPU Support and Checkpointing | 🔒 Locked |
| 40 | Production Training System: Tracking, Tuning, and Model Selection | 🔒 Locked |

### 🏪 Phase 5 — Feature Stores, Secrets & Data Quality (Days 41–49)
| Day | Topic | Status |
|-----|-------|--------|
| 41 | Install and Initialize a Feast Feature Store | 🔒 Locked |
| 42 | Define Feature Views in Feast | 🔒 Locked |
| 43 | Materialize Features to the Online Store | 🔒 Locked |
| 44 | Store MLflow's Admin Password in HashiCorp Vault | 🔒 Locked |
| 45 | Fix a Broken Vault KV Policy for the MLflow Reader | 🔒 Locked |
| 46 | Author Data-Quality Expectations with Great Expectations | 🔒 Locked |
| 47 | Debug a Failing Great Expectations Checkpoint | 🔒 Locked |
| 48 | Publish Great Expectations Data Docs as a CI Artefact | 🔒 Locked |
| 49 | Secrets + Data-Quality Integration Capstone | 🔒 Locked |

### 🐳 Phase 6 — Containerization with Docker (Days 50–56)
| Day | Topic | Status |
|-----|-------|--------|
| 50 | Create Docker Image for ML Training Environment | 🔒 Locked |
| 51 | Create Multi-Stage Docker Build for ML Serving | 🔒 Locked |
| 52 | Set Up Local ML Dev Environment with Docker Compose | 🔒 Locked |
| 53 | Create GPU-Enabled Docker Image for Deep Learning | 🔒 Locked |
| 54 | Push ML Model Images to Container Registry | 🔒 Locked |
| 55 | Add Health Checks and Graceful Shutdown to ML Containers | 🔒 Locked |
| 56 | Automate ML Docker Image Building in CI Pipeline | 🔒 Locked |

### 🚢 Phase 7 — Model Serving (Days 57–66)
| Day | Topic | Status |
|-----|-------|--------|
| 57 | Serve an ML Model with Flask | 🔒 Locked |
| 58 | Serve an ML Model with FastAPI | 🔒 Locked |
| 59 | Run Batch Predictions on a Dataset | 🔒 Locked |
| 60 | Package a Model as a BentoML Service | 🔒 Locked |
| 61 | Containerize an ML Model API with Docker | 🔒 Locked |
| 62 | Implement A/B Testing for Model Deployment | 🔒 Locked |
| 63 | Implement Async Batch Prediction with Task Queue | 🔒 Locked |
| 64 | Serve Multiple Models Behind Unified API Gateway | 🔒 Locked |
| 65 | Implement Canary Deployment for Model Updates | 🔒 Locked |
| 66 | Production Model Serving with Docker Compose | 🔒 Locked |

### 📊 Phase 8 — Monitoring & CI/CD (Days 67–84)
| Day | Topic | Status |
|-----|-------|--------|
| 67 | Add Prometheus as a Grafana Data Source | 🔒 Locked |
| 68 | Generate a Model Performance Report | 🔒 Locked |
| 69 | Generate a Data Quality Report | 🔒 Locked |
| 70 | Create Automated Tests with Evidently Test Suites | 🔒 Locked |
| 71 | Set Up Evidently Monitoring Dashboard | 🔒 Locked |
| 72 | Set Up Drift Detection Alerts | 🔒 Locked |
| 73 | Automatic Retraining Triggered by Drift Detection | 🔒 Locked |
| 74 | Monitor Custom Business Metrics Alongside ML Metrics | 🔒 Locked |
| 75 | End-to-End Monitoring: Prometheus, Grafana, Evidently | 🔒 Locked |
| 76 | Create CI Pipeline for ML Code Linting and Testing | 🔒 Locked |
| 77 | Add Data Validation to CI Pipeline | 🔒 Locked |
| 78 | Add Model Validation Tests to CI | 🔒 Locked |
| 79 | Generate Model Performance Reports in CI with CML | 🔒 Locked |
| 80 | Automate Model Registration in CI/CD | 🔒 Locked |
| 81 | Automate Model Deployment with CD Pipeline | 🔒 Locked |
| 82 | End-to-End ML CI/CD Pipeline | 🔒 Locked |
| 83 | Automated Model Rollback with Health Checks | 🔒 Locked |
| 84 | Production ML CI/CD with Multi-Environment Promotion | 🔒 Locked |

### ☸️ Phase 9 — Kubernetes & Orchestration (Days 85–100)
| Day | Topic | Status |
|-----|-------|--------|
| 85 | Install Argo Workflows on Kubernetes | 🔒 Locked |
| 86 | Create a Basic ML Training Workflow in Argo | 🔒 Locked |
| 87 | Pass Data Between Argo Steps with Output Parameters and Branching | 🔒 Locked |
| 88 | Create an ML Pipeline with Prefect | 🔒 Locked |
| 89 | Parallel Model Training with Argo withItems Fan-Out | 🔒 Locked |
| 90 | Automated Retraining with Argo CronWorkflow | 🔒 Locked |
| 91 | Production ML Pipeline: Argo Workflows + MLflow on Kubernetes | 🔒 Locked |
| 92 | Deploy an ML Model on Kubernetes | 🔒 Locked |
| 93 | Configure HPA for ML Serving Deployment | 🔒 Locked |
| 94 | Deploy a Model with KServe InferenceService | 🔒 Locked |
| 95 | Kubeflow Pipelines — Install and Run a Basic KFP Pipeline | 🔒 Locked |
| 96 | GitOps Model Deployment with ArgoCD | 🔒 Locked |
| 97 | Capstone (1/4): End-to-End ML System — Train, Register, Serve | 🔒 Locked |
| 98 | Capstone (2/4): Monitoring and Automated Retraining | 🔒 Locked |
| 99 | Capstone (3/4): Orchestrate the Full MLOps Loop with Argo Workflows | 🔒 Locked |
| 100 | Capstone (4/4): Close the Loop with Prometheus + Grafana Observability | 🔒 Locked |

---

## 🧰 Tools & Technologies

| Category | Tools |
|---|---|
| Environment & Packaging | `uv`, `pip`, `virtualenv`, `pyproject.toml`, `Makefile`, `Cookiecutter` |
| Code Quality | `ruff`, `black`, `pre-commit` |
| Data Versioning | `DVC`, `SeaweedFS`, `S3` |
| Experiment Tracking | `MLflow`, `SQLite`, `Model Registry` |
| Model Training & Tuning | `scikit-learn`, `PyTorch`, `Optuna`, `FLAML` |
| Feature Store | `Feast` |
| Secrets & Data Quality | `HashiCorp Vault`, `Great Expectations` |
| Containerization | `Docker`, `Docker Compose` |
| Model Serving | `Flask`, `FastAPI`, `BentoML`, `KServe` |
| Monitoring | `Prometheus`, `Grafana`, `Evidently` |
| CI/CD | `GitHub Actions`, `CML` |
| Orchestration | `Argo Workflows`, `Prefect`, `Kubeflow Pipelines` |
| Kubernetes | `kubectl`, `KServe`, `ArgoCD`, `HPA` |

---

## 📋 Prerequisites

- Basic Python knowledge
- Familiarity with the command line
- Git basics
- A KodeKloud account (labs are browser-based — no local setup required)

---

## 📁 How to Use This Repo

Each day has its own markdown file under `days/` following this structure:

```
## Problem
What the lab asks you to do.

## Solution
Step-by-step commands and code used to solve it.

## Key Takeaways
Core concepts explained clearly for future reference.
```

Browse by day number or search by tool/concept to find what you need.

---

## 🔗 Resources

- [KodeKloud MLOps Course](https://kodekloud.com)
- [MLflow Documentation](https://mlflow.org/docs/latest)
- [DVC Documentation](https://dvc.org/doc)
- [Argo Workflows](https://argoproj.github.io/argo-workflows/)
- [KServe](https://kserve.github.io/website/)
