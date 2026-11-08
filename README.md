# Student Graduation Prediction

A simple machine learning project to predict student graduation status using the Decision Tree classification algorithm.

## Overview

This project uses a Decision Tree model to classify whether a student is predicted to graduate based on academic performance data.

The prediction uses three main features:

- **IPK (GPA):** Student grade point average.
- **Kehadiran (Attendance):** Student attendance percentage.
- **Tugas (Assignment):** Student assignment score.

The target variable is **Lulus**, with two classes: `Ya` and `Tidak`.

## Dataset

The dataset contains 20 student records with 4 columns:

| Column | Description |
|---|---|
| IPK | Student GPA |
| Kehadiran | Attendance |
| Tugas | Assignment score |
| Lulus | Graduation status |

Class distribution:
- Ya: 11 records
- Tidak: 9 records

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib

## Machine Learning Workflow

1. Load the dataset using Pandas.
2. Encode the graduation labels using Label Encoder.
3. Separate features and target variables.
4. Split the dataset into training and testing sets (80:20).
5. Train the Decision Tree classifier using the Entropy criterion.
6. Evaluate the model using:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
7. Visualize the Decision Tree.
8. Perform predictions on new student data.

## Project Structure

```text
student-graduation-prediction/
│
├── README.md
├── decisiontree.py
├── requirements.txt
└── Soal pertemuan 10 - Sheet1.csv
```

## Installation

Install the required Python libraries:

```bash
pip install -r requirements.txt
```

## How to Run

Make sure the dataset is in the same directory as the Python script.

Run the program:

```bash
python decisiontree.py
```

## Example Prediction

The program tests two example student records:

- IPK: 3.4, Kehadiran: 88, Tugas: 84
- IPK: 2.2, Kehadiran: 60, Tugas: 55

The model generates graduation predictions based on the trained Decision Tree classifier.

## Author

**Rahma Anjani**

Informatics Student | Aspiring Software Developer
