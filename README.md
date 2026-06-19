# 🧩 ARC Prize 2024 — Human-Calibrated Problems

![Abstract Reasoning](https://img.shields.io/badge/-Abstract%20Reasoning-1a1b26?style=flat-square&logoColor=c0caf5) ![Logical AI](https://img.shields.io/badge/-Logical%20AI-1a1b26?style=flat-square&logoColor=c0caf5) ![Puzzle Solving](https://img.shields.io/badge/-Puzzle%20Solving-1a1b26?style=flat-square&logoColor=c0caf5) ![Python](https://img.shields.io/badge/-Python-1a1b26?style=flat-square&logoColor=c0caf5)

![Banner](./banner.png)

> [!IMPORTANT]
> **Host:** `ARC Prize Foundation`  
> **Platform Link:** [Kaggle Competition](https://www.kaggle.com/competitions/arc-prize-2024)  
> **Dataset Link:** [Kaggle Dataset](https://www.kaggle.com/competitions/arc-prize-2024/data)  
> **Domain:** `Abstract Reasoning & Logical AI`

## 📖 Overview

This is my workspace for the ARC Prize 2024. The goal here was to tackle abstract reasoning puzzles that require actual logic rather than just pattern matching. It was a really fun challenge trying to solve visual grids using Python!

## ⚙️ Standard Pipeline Workflow

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'background': '#0f0f12', 'primaryColor': '#1a1b26', 'edgeLabelBackground':'#11111b', 'tertiaryColor': '#1a1b26'}}}%%
flowchart LR
    A[Data Gathering] --> B[Preprocessing & EDA]
    B --> C[Model Training]
    C --> D[Inference & Submission]
    style A fill:#1e1e24,stroke:#7aa2f7,stroke-width:2px,color:#c0caf5
    style B fill:#1e1e24,stroke:#bb9af7,stroke-width:2px,color:#c0caf5
    style C fill:#1e1e24,stroke:#f7768e,stroke-width:2px,color:#c0caf5
    style D fill:#1e1e24,stroke:#9ece6a,stroke-width:2px,color:#c0caf5
```

## 🗂️ Notebook Architecture & Inventory

### 📂 Preprocessing & EDA
*Data cleaning, feature engineering, and exploratory data analysis.*

| Script / Notebook | Type | Versions | Average Size | Core Stack / Techniques |
|:------------------|:-----|:---------|:-------------|:------------------------|
| 📄 [EDA_and_Visualization](./Preprocessing%20%26%20EDA/EDA_and_Visualization.ipynb) | Single Notebook | `v1` | `238 KB` | `PyTorch` |
| 📁 **EDA_and_Visualization_2** | Multi-Version Script | [v1](./Preprocessing%20%26%20EDA/EDA_and_Visualization_2/v1.ipynb), [v2](./Preprocessing%20%26%20EDA/EDA_and_Visualization_2/v2.ipynb) | `Avg 72 KB` | `Pandas Data Prep` |

### 📂 Training
*Model training and tuning scripts.*

| Script / Notebook | Type | Versions | Average Size | Core Stack / Techniques |
|:------------------|:-----|:---------|:-------------|:------------------------|
| 📄 [Training](./Training/Training.ipynb) | Single Notebook | `v1` | `379 KB` | `PyTorch` |

---

## 🚀 Navigation & Usage Guidelines

> [!TIP]
> 1. **EDA & Preprocessing**: Verify data loaders, actigraphy or DICOM image transformations before model training.
> 2. **Training & Optimization**: Check model definition parameters and training logs to reproduce network weights.
> 3. **Inference & Post-Processing**: Run final pipelines to verify predictions and check submission formats.


---

> *"We dance round in a ring and suppose, but the Secret sits in the middle and knows."*
>
> — **Vigneshwaran S**
