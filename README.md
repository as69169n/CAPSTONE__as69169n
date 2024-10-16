# Predicting Heart Disease Risk Using Hypothesis Testing and Machine Learning

This project aims to predict the risk of heart disease using machine learning models and statistical hypothesis testing. By analyzing various health-related data points, the project attempts to identify patterns and make predictions that can help in early diagnosis or prevention of heart disease.

---

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Data](#data)
- [Usage](#usage)
- [Machine Learning Models](#machine-learning-models)
- [Hypothesis Testing](#hypothesis-testing)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Overview
Heart disease is one of the leading causes of death worldwide, and early detection is critical for effective treatment. This project utilizes a dataset of patient records, applying both machine learning techniques and hypothesis testing to predict the likelihood of heart disease. The goal is to create a robust predictive model that can aid healthcare professionals in identifying high-risk individuals.

### Objectives:
- Perform exploratory data analysis (EDA) to uncover trends in the dataset.
- Use hypothesis testing to validate assumptions about key health metrics (e.g., cholesterol, blood pressure).
- Train multiple machine learning models (Logistic Regression, Decision Trees, Random Forests, etc.) to predict heart disease risk.
- Evaluate the models’ performance based on accuracy, precision, recall, and other metrics.

---

## Project Structure
```bash
├── data/                   # Contains the dataset (raw and processed)
├── notebooks/              # Jupyter notebooks for EDA and modeling
├── src/                    # Python scripts for the main project logic
├── models/                 # Trained models
├── results/                # Results of analysis and models
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies
```

---

## Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.8 or above
- Jupyter Notebook (if you want to explore notebooks)
- Git (optional, to clone the project)

### Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/heart-disease-prediction.git
   cd heart-disease-prediction
   ```

2. **Install required packages**:
   Install the Python dependencies listed in the `requirements.txt` file:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the dataset** (if not included in the repository):
   - You can download the dataset from [UCI Machine Learning Repository - Heart Disease](https://archive.ics.uci.edu/ml/datasets/Heart+Disease) or another relevant source.
   - Place the dataset in the `data/` folder.

---

## Data
The dataset contains various health metrics related to heart disease, including:
- Age
- Sex
- Resting Blood Pressure
- Cholesterol
- Maximum Heart Rate
- Chest Pain Type
- Fasting Blood Sugar
- and more...

### Data Preprocessing:
The data undergoes several preprocessing steps including:
- Handling missing values.
- Feature scaling.
- Splitting into training and test sets.

---

## Usage

1. **Run the Jupyter notebooks**:
   You can explore the Jupyter notebooks in the `notebooks/` folder for step-by-step data analysis, hypothesis testing, and model training:
   ```bash
   jupyter notebook
   ```

2. **Run the main prediction script**:
   To train and evaluate models, you can run the script from the `src/` folder:
   ```bash
   python src/main.py
   ```

---

## Machine Learning Models

The project compares the performance of several machine learning models:
- **Logistic Regression**: A commonly used model for binary classification tasks like heart disease prediction.
- **Decision Tree**: A simple but effective model for classification.
- **Random Forest**: An ensemble model that improves prediction accuracy by aggregating multiple decision trees.
- **Support Vector Machine (SVM)**: A model used for classification with high-dimensional feature spaces.
- **K-Nearest Neighbors (KNN)**: A non-parametric model that works well with smaller datasets.

---

## Hypothesis Testing

In addition to machine learning, hypothesis testing is used to validate some statistical assumptions about key features:
- **T-test**: To compare the means of two groups (e.g., patients with heart disease vs. without).
- **Chi-square test**: To test associations between categorical variables (e.g., chest pain type and heart disease).

---

## Results

The models are evaluated based on the following metrics:
- **Accuracy**: Overall correctness of the model.
- **Precision**: How many of the positive predictions were actually correct.
- **Recall**: How many of the actual positives were correctly identified.
- **F1-Score**: A balance between precision and recall.
- **ROC-AUC Curve**: Measures the ability of the classifier to distinguish between classes.

### Key Findings:
- The Random Forest model achieved the highest accuracy at 85%, followed by Logistic Regression at 82%.
- Hypothesis testing indicated that certain features like cholesterol levels and maximum heart rate are significantly different between patients with and without heart disease.

---

## Contributing

Contributions are welcome! To contribute:
1. Fork this repository.
2. Create a new branch with your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request on GitHub.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Contact

Created by [Ashrita Sripuram](https://github.com/as69169n) – feel free to contact me if you have any questions!

---

This structure provides an organized, informative README that clearly explains your project to others. You can modify the sections based on your actual project scope, methods, and findings.
