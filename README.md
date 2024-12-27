# Heart Disease Prediction Using Machine Learning

This repository contains a machine learning project focused on predicting heart disease in patients using various features. The project implements different machine learning algorithms and evaluates their performance to determine the best model for heart disease prediction.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Algorithms Used](#algorithms-used)
- [Installation](#installation)
- [Usage](#usage)
- [Model Evaluation](#model-evaluation)

## Project Overview
This project uses a dataset of patient health metrics and applies machine learning techniques to predict whether a patient has heart disease. The goal is to create a model that can predict heart disease based on various health parameters such as age, cholesterol levels, blood pressure, etc.

## Dataset
The dataset used in this project is the [Heart Disease UCI dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease), which contains the following features:
- **Age**: Age of the patient
- **Sex**: Gender of the patient (1 = male, 0 = female)
- **CP**: Chest pain type
- **Trestbps**: Resting blood pressure
- **Chol**: Serum cholesterol
- **Fbs**: Fasting blood sugar
- **Restecg**: Resting electrocardiographic results
- **Thalach**: Maximum heart rate achieved
- **Exang**: Exercise induced angina
- **Oldpeak**: Depression induced by exercise relative to rest
- **Slope**: Slope of the peak exercise ST segment
- **Ca**: Number of major vessels colored by fluoroscopy
- **Thal**: Thalassemia (a blood disorder)
- **Target**: Presence or absence of heart disease (1 = disease, 0 = no disease)

### Download the dataset
To download the dataset, you can access the UCI repository, or you can place the dataset file (usually `heart.csv` or `heart_disease.csv`) in the project directory.

## Algorithms Used
The following machine learning algorithms were used in this project to predict heart disease:
1. **Logistic Regression**
2. **Decision Trees**
3. **Random Forest Classifier**


Each algorithm was trained and tested using the dataset to evaluate its performance.

## Installation

### Clone the Repository
To get started, clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/Heart_Disease.git
cd Heart-Disease
