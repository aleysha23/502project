# Student Success Prediction

An educational machine learning project that explores whether student academic performance can be predicted using demographic, behavioral, and academic factors.

This project builds a basseline machine learning pipeline to predict a student's final grade (G3) using the Student Performance dataset.

---

# What is the Goal?

The goal of this project is to understand which factors influence student academic success and to build a predictive model that estimates a student's final grade.

Such models could potentially help educators identify students who may need additional support earlier in the semester.

---

# Learning Objectives

By completing this project, the following skills are demonstrated:

- exploratory data analysis (EDA)
- identifying potential data leakage
- preprocessing mixed data types
- building machine learning pipelines with scikit-learn
- evaluating a baseline predictive model

---

# Dataset

The dataset used is the Student Performance Dataset, which contains information about secondary school students including:

- study time
- absences
- family background
- lifestyle factors
- academic performance

The prediction target is:

**G3 — final grade**

To prevent data leakage, earlier grades (G1 and G2) were excluded from the feature set.

---

# Repository Structure

## Repository Structure

```
502project/
│
├── 502project.ipynb   # Main project notebook
├── student-mat.csv    # Dataset
└── README.md          # Project documentation
```

---
## Installation

### 1. Clone the repository

git clone https://github.com/aleysha23/502project.git

cd 502project


---

### 2. Create a virtual environment (recommended)

Using Python 3.12:
python3.12 -m venv venv

Activate the virtual environment:

**macOS / Linux**
source venv/bin/activate

**Windows**
venv\Scripts\activate

---

### 3. Install required dependencies
pip install pandas numpy scikit-learn matplotlib seaborn

---

## Running the Notebook

### Option 1 — Run in Google Colab

1. Open `502project.ipynb`
2. Upload the dataset `student-mat.csv`
3. Run all cells from top to bottom

---

### Option 2 — Run locally

Start Jupyter:
jupyter notebook

Then open:
502project.ipynb

and run all cells.


