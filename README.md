
   
# 🍷 Wine Quality Prediction   

## Overview   
  
This project predicts wine quality based on physicochemical properties using machine learning models. By leveraging Random Forest Classifier, Logistic Regression, and SVM, the goal is to classify wines into quality categories and uncover the key factors that influence wine quality.

## Project Workflow

1. **Exploratory Data Analysis (EDA)**  
   - Analyzed the distribution of features like acidity, sugar, and alcohol.  
   - Visualized patterns, correlations, and anomalies in the dataset.  

2. **Data Preprocessing**  
   - Handled missing values and standardized the dataset for optimal model performance.  
   - Ensured feature scaling to maintain consistency across all inputs.  

3. **Model Implementation**  
   - Built and evaluated Random Forest, Logistic Regression, and SVM models.  
   - Tuned hyperparameters to enhance accuracy and performance.  

4. **Model Evaluation**  
   - Compared models using metrics such as accuracy and F1-score.  
   - Selected the best-performing model for wine quality prediction.  

## Datasets

The dataset includes the following features:  

- **fixed acidity**  
- **volatile acidity**  
- **citric acid**  
- **residual sugar**  
- **chlorides**  
- **free sulfur dioxide**  
- **total sulfur dioxide**  
- **density**  
- **pH**  
- **sulphates**  
- **alcohol**  
- **quality**  

## Installation

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/chandkund/Wine-Quality-Prediction.git
   ```  
2. **Navigate to the project directory**:  
   ```bash
   cd Wine-Quality-Prediction
   ```  
3. **Install required packages**:  
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the script to analyze and predict wine quality:  
```bash
python wine_quality_prediction.py
```

## Results

The project successfully predicted wine quality categories, with the Random Forest Classifier achieving the highest accuracy. The analysis revealed that alcohol content and acidity were among the most influential factors in determining wine quality.
