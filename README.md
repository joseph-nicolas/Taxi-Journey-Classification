# Taxi Journey Classification

## 📖 Overview
This project uses machine learning to classify anonymous taxi journeys as short or long trips. By training Support Vector Machine (SVM) and k-Nearest Neighbors (k-NN) models on geographical coordinates and distance data, we can accurately predict trip types and better understand transport patterns.

## ⚙️ How It Works
The dataset consists of anonymized taxi journey records, including start and end coordinates (latitude/longitude) and total distance. 
* **Target Variable:** Journeys are classified as `1` (Long trip, >= 5 km) or `0` (Short trip, < 5 km).
* **Models Used:** Support Vector Machine (SVM) with a linear kernel, and k-Nearest Neighbors (k-NN).

## 🚀 Getting Started

### Prerequisites
To run this project, you will need Python installed along with the following libraries:
* `pandas`
* `scikit-learn`

### Usage
1. Clone this repository.
2. Ensure the dataset (`RTA_Anonymous_Journies.csv`) is in the same directory as the notebook.
3. Open the Jupyter Notebook (`ML_Classification.ipynb`) and run the cells sequentially. 

The notebook handles data loading, feature scaling, model training, and outputs the classification reports and accuracy scores for both models.

## 👥 Authors
* **Yasser**
* **Joseph**
* **Liana**

## 📄 License
This project is for educational purposes. 
