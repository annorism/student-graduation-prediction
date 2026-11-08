# Student Graduation Prediction

A simple machine learning project that predicts student graduation outcomes using the Decision Tree classification algorithm.

## Overview

This project implements a Decision Tree model to classify student graduation status based on three academic attributes:

- **GPA (IPK)**
- **Attendance (Kehadiran)**
- **Assignment Score (Tugas)**

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib

## Machine Learning Workflow

1. Load the dataset using Pandas.
2. Encode the graduation labels.
3. Split the dataset into training and testing sets (80:20).
4. Train the Decision Tree classifier using the Entropy criterion.
5. Evaluate the model using:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
6. Visualize the Decision Tree.
7. Test predictions using new student data.

## Project Structure

```text
student-graduation-prediction/
├── decisiontree.py
├── README.md
└── requirements.txt
```

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the program:

```bash
python decisiontree.py
```

*Note: The original Python script expects the dataset file `Soal pertemuan 10 - Sheet1.csv` in the working directory.*
