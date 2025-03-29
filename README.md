# 🍏 Apple Quality Prediction using Machine Learning


## 📌 Overview
This project uses **Machine Learning** to predict the quality of apples (Good/Bad) based on physical and chemical properties. The goal is to automate fruit quality assessment, improving efficiency in the food industry.

## 📊 Dataset
- The dataset contains various features related to apple quality, such as:
  - **pH Level**
  - **Sugar Content**
  - **Firmness**
  - **Color Intensity**
  - **Acidity**
- The target variable: **Quality** (1 = Good, 0 = Bad)

## 🔍 Exploratory Data Analysis (EDA)
- Visualized distributions using histograms & boxplots
- Identified correlations between features & quality
- Observed that **sugar level** and **firmness** are strong indicators of quality

## 🏆 Models Used
The following models were implemented and evaluated:
1. **Logistic Regression** (Baseline Model)
2. **Support Vector Machine (SVM)**
3. **Random Forest Classifier**
4. **XGBoost (Best Performing Model)**

## 🛠️ Model Evaluation
    Model	              Accuracy	Precision	Recall	
    Logistic Regression	  72.83%	89.93%	  86.11%	
    SVM	                  88.00%	86.16%	  89.97%	
    Random Forest	        88.00%	88.29%	  86.27%	
    XGBoost	              87.17%	86.05%	  88.10%

- The **Random Forest and SVM model** achieved the highest accuracy.
- The confusion matrix showed minimal misclassifications.

## 🚀 How to Run the Project
### 1️⃣ Clone the Repository

    git clone https://github.com/your-username/apple-quality-prediction.git
    cd apple-quality-prediction

## 📌 Future Improvements
- Expand dataset with more apple varieties
- Optimize hyperparameters for better performance
- Explore **Deep Learning models**

## 📜 License
This project is **open-source** under the MIT License.

---
### ⭐ Feel free to fork, star, and contribute to this project!

### 🔗 Connect with Me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)]([https://www.linkedin.com/in/your-profile/](https://www.linkedin.com/in/seeram-murali-ganesh-9a6b62258/)

