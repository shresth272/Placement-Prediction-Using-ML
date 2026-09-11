# Placement Prediction Using ML

This is a simple machine learning project that I built to understand how machine learning can be used to predict student placement outcomes.

The dataset contains information about 100 students, and I used their CGPA and IQ as the main features for making the prediction. I trained a Logistic Regression model to predict whether a student is likely to be placed or not.

## About the Project

I started this project as a way to get familiar with the basic steps involved in building a machine learning model.

The project covers the process from loading and exploring the dataset to preparing the data, training the model, and using it to make predictions.

The two features used in the model are:

* CGPA
* IQ

The target variable represents the placement result:

* 1 means the student is placed
* 0 means the student is not placed

## Dataset

The dataset contains records of 100 students.

For this project, I kept the model simple and used only CGPA and IQ to make the prediction. This makes it easier to understand how the features affect the model and how a basic classification algorithm works.

## Model Used

I used Logistic Regression for this project because the output has two possible outcomes: placed or not placed.

Before training the model, I used `StandardScaler` to scale the input features. The data was then divided into training and testing sets before training the model.

## Project Workflow

```text
Dataset
   |
   v
Data Exploration
   |
   v
Feature Selection
   |
   v
Train-Test Split
   |
   v
Feature Scaling
   |
   v
Logistic Regression
   |
   v
Model Evaluation
   |
   v
Prediction
```

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Files in This Repository

```text
Placement-Prediction-Using-ML/
|
├── Toy_Project.ipynb
├── placement.csv
├── model.pkl
└── README.md
```

### Toy_Project.ipynb

The Jupyter Notebook contains the complete process of exploring the dataset, preparing the data, training the model, and making predictions.

### placement.csv

This is the dataset containing information about the 100 students used for the project.

### model.pkl

This file contains the trained machine learning model saved using Pickle.

## How to Run

First, clone the repository:

```bash
git clone https://github.com/shresth272/Placement-Prediction-Using-ML.git
```

Open the project folder:

```bash
cd Placement-Prediction-Using-ML
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Then open the notebook:

```bash
jupyter notebook
```

Open `Toy_Project.ipynb` and run the cells.

## What I Learned

While working on this project, I learned how to:

* Work with a dataset using Pandas
* Explore and visualize data
* Select features for a machine learning model
* Split data into training and testing sets
* Scale features using StandardScaler
* Train a Logistic Regression model
* Make predictions
* Save a trained model using Pickle

## Future Improvements

There are several ways I could improve this project in the future. For example, I could include more student-related features such as internships, technical skills, communication skills, projects, certifications, and academic performance.

I could also build a simple web interface where a user can enter the required details and get a prediction without having to run the notebook.

## Note

This project is mainly for learning and practice. The dataset contains only 100 students and uses just two features, so the model should not be considered a reliable way of predicting the actual placement chances of a student.

## Author

Shresth Gupta

GitHub: https://github.com/shresth272
