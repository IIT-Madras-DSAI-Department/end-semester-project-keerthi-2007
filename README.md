[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/R05VM8Rg)
# IIT-Madras-DA2401-Machine-Learning-Lab-End-Semester-Project

## 📌 Purpose of this Template

This repository is the **starter** for your End Semester Project submission in GitHub Classroom. You can implement your solution and push your work in this repository. Please free to edit this README.md file as per your requirements.

> **Scope (as per assignment brief):**
> This repository contains a complete implementation of Logistic regression with and without PCA ,XGBOOST,KNN and stacked model of KNN and XGBOOST .

---

**Important Note:** 
1. TAs will evaluate using the `.py` file only.
2. All your reports, plots, visualizations, etc pertaining to your solution should be uploaded to this GitHub repository

---

## 📁 Repository Structure

* Algorithms - It contains the implementation of Logistic regression without PCA ,with PCA ,KNN with PCA .
* Stacked_model.py - It contains the implementation of Stacked model of KNN and XGBOOST .
* xgboost_.py - It contains the implementation of XGboost Algorithm.
* main_1.py - It contains the code for the best model i.e, KNN .
* xgboost_hyp_pca - Since it is taking too much time to run xgboost algorithm i used pca which reduced time comparatively .And its code is in this file .
* ML_assignment_2-2.pdf - Report for everything
* main_2.py - It contains the code for second best model XGboost with PCA but it takes around 8 mins to run 

---

## 📦 Installation & Dependencies

* Make sure numpy and pandas are imported
* Also i assumed that the train and test dataset are same as assignment -2 's datasets hence i removed even column from them explicitly .
* If the test dataset doesnt have even column just comment out the line where i removed even column

---

## ▶️ Running the Code

All experiments should be runnable from the command line **and** reproducible in the notebook.

### A. Command-line (recommended for grading)

* While running the code change the dfval path to the test set you will be using 
  
---

## Things which I did/changed :
* The stacked model code didnt run in my system .It gave the session crashed out as it used all the available RAM .So i didnt mention any F1 scores or related values in report .
* Also I didnt upload one single algorithms.py because i thought it will be confusing because of variable names hence i wrote one algorithm in a single file and did hypertunign in the same file .
* Also two best models which i got are xg boost with pca and KNN but in terms of time i think KNN .So i uploaded both of them seperately main_1 -KNN and main_2 -xgboost with pca .

## 🧾 Authors

**<Vallem Keerthi Reddy, Roll No.DA24B051**, IIT Madras (2025–26)



