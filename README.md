# Predicting Student Academic Performance Using Machine Learning

## Project Overview
This project applies machine learning techniques to predict students' JAMB Scores based on various academic, social, and personal factors.  
The goal is to explore which factors contribute most to academic success and to develop a regression model for performance prediction.

---

## Files Included
- **student_performance_analysis.ipynb** — Jupyter Notebook containing all data processing, analysis, visualizations, and machine learning modeling.
- **machine_learning_report.pdf** — Formal project report (Introduction to Conclusion, 3–6 pages).
- **README.md** — This instruction and project description file.

---

## Dataset Information
- **Dataset Source**: Kaggle  
- **Number of Records**: 5,000 students  
- **Features**: 17 features including study hours, attendance rate, socioeconomic status, and extra tutorials.

---

## Project Steps
1. **Data Cleaning**  
   - Missing values filled (e.g., Parent Education Level).
   - Irrelevant columns (e.g., Student ID) removed.
   - Categorical variables encoded.

2. **Exploratory Data Analysis (EDA)**  
   - Statistical summaries and grouping techniques used to find trends.
   - Feature correlations examined.

3. **Visualizations**  
   - 5 plots created (using Matplotlib and Seaborn) to highlight patterns.

4. **Machine Learning Model**  
   - **Model Chosen**: Linear Regression.
   - **Performance Metrics**: MAE, MSE, RMSE, R² Score calculated.

---

## How to Run the Project
1. Install dependencies:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
2. Open the Jupyter Notebook:
    ```bash
    jupyter notebook student_performance_analysis.ipynb
    ```
3. Run all cells to reproduce the data analysis, visualizations, and model training.

---

## Results Summary
- Strong correlation found between study habits and JAMB scores.
- Model achieved an R² Score of approximately 0.81.
- Model can reasonably predict student academic outcomes based on the given features.

---

## Author
- **Name**: [Your Full Name]
- **Matric Number**: [Your Matriculation Number]
- **Course**: CSC 308 — Computer Science Innovation and New Technologies
- **Lecturer**: Mr. Uloko, F.O.
- **Academic Session**: 2024/2025

---

