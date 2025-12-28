# Airline Passenger Satisfaction Prediction using AutoML

## Project Overview
Customer satisfaction is a critical metric in the airline industry.  
This repository demonstrates how to predict airline passenger satisfaction using **AutoML** with **AutoGluon**.

The workflow includes:
1. Data exploration and preprocessing
2. Dataset description
3. AutoML model training and leaderboard evaluation
4. Selecting the best model (WeightedEnsemble_L2)
5. Feature importance analysis
6. Evaluation on test data
7. Actionable business insights

## Dataset
**Source:** Kaggle – Airline Passenger Satisfaction  
**Author:** teejmahal20  
**Link:** [Airline Passenger Satisfaction Dataset](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)

### Target Variable
- `satisfaction` → values: `"satisfied"`, `"neutral or dissatisfied"`

### Feature Categories
- **Customer Information:** Gender, Age, Customer Type  
- **Flight Details:** Class, Type of Travel, Flight Distance  
- **Service Quality Ratings:** Seat Comfort, Inflight Wifi, Cleanliness, Food & Drink, Inflight Entertainment, Inflight Service, Onboard Service, Leg Room Service, Gate Location, Checkin Service, Online Boarding, Baggage Handling, Ease of Online Booking, Departure/Arrival Time Convenience  
- **Operational Metrics:** Departure Delay in Minutes, Arrival Delay in Minutes

## Objectives
- Train an AutoML model to predict passenger satisfaction
- Identify key drivers of satisfaction
- Generate insights for airlines to improve service quality

## Tools & Technologies
- Python
- Pandas
- AutoGluon
- Matplotlib & Seaborn
- Kaggle Notebook Environment

## How to Use
1. Open the notebook `Airline_Passenger_Satisfaction_AutoML.ipynb` in Kaggle or locally.  
2. Install dependencies (if running locally):

    ```bash
    pip install pandas autogluon matplotlib seaborn scikit-learn
    ```

3. Follow the notebook to:
   - Explore the data
   - Train models with AutoGluon
   - Evaluate predictions
   - Analyze feature importance and generate insights

## Insights
- **Service quality dominates satisfaction:** inflight wifi, online boarding, baggage handling  
- **Customer segmentation matters:** business vs personal travelers  
- **Operational improvements:** optimize boarding, seat comfort, inflight service  
- Minor factors (age, food, entertainment) have limited individual impact but improve overall experience

> This notebook is fully self-contained and demonstrates both **predictive modeling** and **business insights** using AutoML.
