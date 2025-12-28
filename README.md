# Airline Passenger Satisfaction Prediction using AutoML

## Project Overview
Customer satisfaction is a critical metric in the airline industry.  
This repository demonstrates how to predict airline passenger satisfaction using AutoML with AutoGluon.

The workflow includes:
1. Data exploration and preprocessing
2. Dataset description
3. AutoML model training and leaderboard evaluation
4. Selecting the best model (WeightedEnsemble_L2)
5. Feature importance analysis
6. Evaluation on test data
7. Actionable business insights

---

## Dataset
Source: Kaggle – Airline Passenger Satisfaction  
Author: teejmahal20  
Link: https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction  

### Target Variable
- satisfaction → "satisfied", "neutral or dissatisfied"

### Feature Categories
- Customer Information: Gender, Age, Customer Type  
- Flight Details: Class, Type of Travel, Flight Distance  
- Service Quality Ratings: Seat Comfort, Inflight Wifi, Cleanliness, Food & Drink, Inflight Entertainment, Inflight Service, Onboard Service, Leg Room Service, Gate Location, Checkin Service, Online Boarding, Baggage Handling, Ease of Online Booking, Departure/Arrival Time Convenience  
- Operational Metrics: Departure Delay in Minutes, Arrival Delay in Minutes  

---

## Objectives
- Train an AutoML model to predict passenger satisfaction
- Identify key drivers of satisfaction
- Generate insights for airlines to improve service quality

---

## Tools & Technologies
- Python
- Pandas
- AutoGluon
- Matplotlib & Seaborn
- Scikit-learn
- Kaggle Notebook Environment

---

## How to Use

1. Open the notebook Airline_Passenger_Satisfaction_AutoML.ipynb in Kaggle or locally.

2. Install dependencies (if running locally):
   ```bash
   pip install pandas autogluon matplotlib seaborn scikit-learn
   ```

3. After installation, open and run the notebook locally using Jupyter Notebook or JupyterLab.  
   Ensure all cells execute sequentially to reproduce:
   - Model training
   - Leaderboard comparison
   - Feature importance analysis
   - Test set evaluation

---

## Model Summary
- Best Model: WeightedEnsemble_L2  
- Evaluation Metric: F1-macro  
- Test Accuracy: ~97.7%

The ensemble outperformed individual models such as LightGBM, XGBoost, and Neural Networks.

---

## Key Insights

### Service Quality is the Strongest Driver of Satisfaction
- Inflight wifi
- Online boarding
- Baggage handling

### Customer Segmentation Matters
- Business vs personal travel
- Loyal vs disloyal customers

### Operational Improvements Have the Highest Impact
- Boarding experience
- Gate location
- Inflight service

Demographics such as Age and Gender have minimal standalone influence.

---

## Conclusion
This project demonstrates the power of AutoML in building a high-performing classification model with minimal manual tuning.  
Beyond prediction, feature importance analysis provides clear, actionable insights that airlines can use to prioritize service improvements and enhance customer satisfaction.

---

## Author
Omar Mamdouh  
AI Engineer & Data Scientist | Machine Learning & AutoML Projects
