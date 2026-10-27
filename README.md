## Project Overview

This project uses Logistic Regression to predict whether a student will get placed or not based on their CGPA and IQ.

The model takes two inputs:

- CGPA
- IQ

The output is:

- 1 → Student will get placed
- 0 → Student will not get placed

The trained Machine Learning model is deployed using Flask with a simple HTML user interface.

## 📁 Project Structure

```text
student-placement-prediction-logistic-regression/
│
├── app.py
├── Placement_Y_N.csv
├── BCModel.pkl
├── README.md
│
└── templates/
    └── index.html
