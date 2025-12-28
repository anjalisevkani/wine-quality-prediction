# 🍷 Wine Quality Prediction using Machine Learning

## 📌 Project Overview
This machine learning project aims to predict the **quality of wine**
based on its **physicochemical properties** such as acidity, sugar content,
pH level, and alcohol concentration.

The project is formulated as a **classification problem**, where wine samples
are categorized into quality classes using a supervised learning algorithm.
It demonstrates a complete ML pipeline from data loading to model evaluation.

---

## 📊 Dataset Information
- **Dataset:** Wine Quality Dataset  
- **Source:** UCI Machine Learning Repository  
- **Type:** Red wine quality data  
- **Features:** 11 numerical physicochemical attributes  
- **Target Variable:** Wine quality score  

### 🔑 Features Include:
- Fixed Acidity  
- Volatile Acidity  
- Citric Acid  
- Residual Sugar  
- Chlorides  
- Free Sulfur Dioxide  
- Total Sulfur Dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  

---

## 🛠️ Technologies & Libraries Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Google Colab 

---

## ⚙️ Machine Learning Model
- **Problem Type:** Classification  
- **Algorithm Used:** Logistic Regression  
- **Preprocessing Steps:**
  - Data cleaning and exploration  
  - Feature scaling (where required)  
  - Train–test split for evaluation  

Logistic Regression is used as a baseline classifier to understand
the relationship between chemical properties and wine quality.

---

## 📈 Model Performance
The model is evaluated using classification accuracy on the test dataset.

- **Training Accuracy:** 100%  
- **Test Accuracy:** 91.56% 

The results indicate that the model learns meaningful patterns from
the input features, though the dataset remains challenging due to
overlapping quality classes.

---

## 📊 Data Visualization
The project includes:
- Distribution plots of wine features  
- Correlation heatmap  
- Visual analysis of feature relationships  

These visualizations help in understanding which attributes
influence wine quality the most.

---

## 🚀 How to Run the Project
1. Clone this repository  
2. Open the notebook in **Google Colab** or **Jupyter Notebook**  
3. Ensure required libraries are installed  
4. Run all cells sequentially  

---

## 📁 Project Structure
wine-quality-prediction/
│── wine_quality_prediction.ipynb
│── README.md

## 📌 Conclusion
This project demonstrates how machine learning techniques can be applied
to predict wine quality using chemical composition data.
It highlights the importance of data exploration, preprocessing,
and evaluation in real-world classification problems.

---

## 👩‍💻 Author
**Anjali Sevkani**
