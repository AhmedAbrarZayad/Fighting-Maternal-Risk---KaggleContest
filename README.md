# Fighting-Maternal-Risk---KaggleContest

# Kaggle Community Olympiad - Fighting Maternal Risk

Predict maternal health risk from physiological data to help prioritize care and save lives.

---

## 📌 Overview

Every day, maternal complications threaten the lives of pregnant women — but early risk detection can save them.  
In this competition, the goal is to build a **machine learning model** that predicts a pregnant woman’s maternal health risk level:

- **Low Risk**
- **Mid Risk**
- **High Risk**

Using physiological data such as:

- **Age** (years)  
- **SystolicBP** (mmHg)  
- **DiastolicBP** (mmHg)  
- **BS** – Blood sugar level (mmol/L)  
- **BodyTemp** (°C)  
- **HeartRate** (beats per minute)  

---

## 🎯 Objective

Develop a **multi-class classification model** using the provided `train.csv` dataset and make predictions for the unseen `test.csv`.

Your model should aim for **balanced accuracy** across all three risk levels, handling possible **class imbalance** effectively.

---

## 📊 Evaluation Metric

The leaderboard uses **Accuracy Score**:

> Accuracy is calculated **independently for each class** (Low, Mid, High) and then averaged.  
> This ensures the model performs well across all classes.

**Important:** Class imbalance may exist, so design your model to balance **precision** and **recall**.

---

## 📂 Dataset Description

| Column       | Description |
|--------------|-------------|
| `Age`        | Age of the pregnant woman (years) |
| `SystolicBP` | Systolic (upper) blood pressure (mmHg) |
| `DiastolicBP`| Diastolic (lower) blood pressure (mmHg) |
| `BS`         | Blood sugar level (mmol/L) |
| `BodyTemp`   | Body temperature (°C) |
| `HeartRate`  | Heart rate (beats per minute) |
| `RiskLevel`  | Target label: Low Risk, Mid Risk, or High Risk |

---

## 📤 Submission Format

The submission file should be a **CSV** in the following format:

| Id | RiskLevel |
|----|-----------|
| 0  | Low Risk  |
| 1  | Mid Risk  |
| 2  | Low Risk  |
| …  | …         |

- `Id`: Matches the **Id** column from `test.csv`.
- `RiskLevel`: Predicted risk level (`Low Risk`, `Mid Risk`, `High Risk`).

**Example:** See `sample_submission.csv`.

---

## 🏆 Competition Details

- **Host:** Hasanul Banna Himel
- **Type:** Healthcare | Beginner
- **Prizes:** Kudos (No points or medals)
- **Participants:** 64 entrants, 17 teams

---

## 📧 Contact

- Email: [hasanulbannahimel2003@gmail.com](mailto:hasanulbannahimel2003@gmail.com)  
- LinkedIn: [Hasanul Banna Himel](https://www.linkedin.com/in/hasanul-banna-himel/)  

---

## 📚 Citation

Hasanul Banna Himel and Shahriyar Al Mustakim Mitul. *Kaggle Community Olympiad - Fighting Maternal Risk*.  
[Competition Link](https://kaggle.com/competitions/mlolympiadbd2025) — 2025. Kaggle.
