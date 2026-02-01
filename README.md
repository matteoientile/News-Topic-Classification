# News Topic Classification 📰

**Student:** Matteo Ientile

**Context:** Data Science & Machine Learning Exam - Winter 2026

## 📌 Project Overview
This repository contains the solution for the News Topic Classification problem. The project implements a Machine Learning pipeline to classify news articles into distinct categories, addressing challenges such as high dimensionality and class imbalance. The optimal solution is ranked in top 25% across a leaderboard of 200+ people.

The solution is divided into two distinct parts:
1.  **Exploration & Tuning:** Deep analysis and hyperparameter search.
2.  **Final Pipeline:** The optimized, production-ready model.

---

## ⚠️ Important Note on Performance
**Please read before executing:**
> **`1_Exploration_and_Tuning.ipynb`** contains computationally expensive Grid Search and Randomized Search operations. It takes a significant amount of time to run. 
>
> The notebook has been saved with **all outputs visible**. It is recommended to view the static outputs rather than re-running the cells unless you intend to reproduce the full tuning process from scratch.

---

## 📂 Repository Structure

| File | Description |
| :--- | :--- |
| `1_Exploration_and_Tuning.ipynb` | **Analysis & R&D.** Contains Exploratory Data Analysis (EDA), split strategy, and extensive Hyperparameter Tuning. |
| `2_Final_Model_Solution.ipynb` | **Production Pipeline.** The final, reproducible solution using the best hyperparameters found. It retrains on the full Development set and generates the submission CSV quickly. |
| `requirements.txt` | List of Python dependencies required to run the environment. |
| `Report.pdf` | Official IEEE-format report describing the pipeline. |

---

## 🚀 How to Run

1.  **Install Dependencies**
    Ensure you are in the project directory and run:
    ```bash
    pip install -r requirements.txt
    ```

2.  **Data Placement**
    Ensure the dataset files (`development.csv` and `evaluation.csv`) are located in the root directory of this repository.

3.  **Generate Submission (Fast)**
    Run the solution notebook to reproduce the final model and submission file:
    * Open and run `2_Final_Model_
