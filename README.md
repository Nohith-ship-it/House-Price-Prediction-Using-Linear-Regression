# House-Price-Prediction-Using-Linear-Regression
A regression-based predictive model for estimating real estate prices using multiple features, built with Python and scikit-learn.
📌 Project Overview

This project focuses on predicting house prices using a Linear Regression Machine Learning model.
The model uses multiple features such as area, number of rooms, house age, and location quality to estimate the price of a house.

🎯 Objective

To build a regression model that predicts house prices based on:

Square Footage
Number of Bedrooms
Number of Bathrooms
Number of Floors
Age of the House
Location Score
📂 Dataset Description

The dataset used in this project is a small synthetic dataset for demonstration purposes.

Features:
Feature	Description
sqft	Area of the house (in square feet)
bedrooms	Number of bedrooms
bathrooms	Number of bathrooms
floors	Number of floors
age	Age of the house (years)
location_score	Location quality (1–10 scale)
price	Target variable (house price)

⚙️ Technologies Used
Python
Pandas – Data handling
Scikit-learn – Machine learning model

🔄 Project Workflow
Data Collection (CSV file)
Data Loading using Pandas
Feature Selection
Model Training using Linear Regression
User Input Handling
Price Prediction
🧠 Model Used
Linear Regression

Linear Regression models the relationship between dependent and independent variables using a linear equation:

Price = b0 + b1×sqft + b2×bedrooms + b3×bathrooms + b4×floors + b5×age + b6×location_score

▶️ How to Run the Project
1️⃣ Install Required Libraries
pip install pandas scikit-learn
2️⃣ Project Structure
project/
│
├── house_data_extended.csv
├── house_price_prediction.py
└── README.md

3️⃣ Run the Program
python house_price_prediction.py

💻 Example Usage
Enter house details:
Square footage: 2100
Bedrooms: 4
Bathrooms: 3
Number of floors: 2
Age of house (years): 3
Location score (1-10): 8

Predicted House Price: ₹ 500000.00

📊 Key Features of the Project
User-friendly input system
Multi-feature prediction model
Simple and understandable code
Suitable for beginners

🚀 Future Enhancements
Add more real-world data
Include graphical visualization (matplotlib)
Use advanced models (Random Forest, XGBoost)
Build a web app using Flask or Streamlit

⚠️ Limitations
Uses a small dataset
Accuracy depends on data quality
Linear Regression assumes linear relationships

📚 Conclusion

This project demonstrates how machine learning can be used to predict house prices using multiple influencing factors. It serves as a foundational project for beginners to understand regression models.
