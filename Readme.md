# Predicting Hotel Booking Cancellations Using ML
Msc. Data Science, Department of IEM, BGU.
### Abstract
In the one and a half trillion dollars hotel industry, demand management is a crucial factor to revenue.  Hoteliers’ ability to make accurate demand forecasting is greatly affected by booking cancellations, which often result in vacancy, inaccurate room pricing, false cancellation policy implementation resulting in further reduction of the number of bookings and revenue. Accurate demand forecasting also assures hoteliers and reservation giants (such as Booking and Trivago) correct use of over-booking tactics, incentive-based programs, room deposits and cancellation policies. In this project we use data collected for over 119,000 bookings, combined with interpretable machine learning based classifiers to provide a tool which will be able to accurately predict booking cancellations in advance. The use of interpretable models (specifically decision tree-based models) will provide hotel management with important insights, as well as the ability to base management level decision on understandable cancellation and demand patterns. In this project, we demonstrate a Random Forest Classifier with 88% Recall score.

##### By Oriel Perets & Dafna Meron

#### Dependecies:
1. Core dependecies
    * Numpy
    * Pandas
2. Model dependecies (Scikit Learn)
    * classification
    * cross_val_score
    * RandomForestClassifier
    * Logistic Regressions
    * GaussianNB
    * Model_selection tools
3. Importing data
    * csv --> dataFrame

### Data exploration
1. Variable Identification
2. Univariate Analysis
3. Bi-Variate Analysis
4. Missing Values Treatment
5. Outlier Treatment
6. Variable Transofrmation
7. Variable Creation

#### Variable identification
* Target - 'is_canceled'
* Predictos - all other variables
* Continous:
    * total_of_special_requests
    * required_car_parking_spaces
    * adr
    * days_in_waiting_list
    * adults
    * stays_in_week_nights
    * stays_in_weekend_nights
    * lead_time
* Categorical:
    * hotel
    * arrival_date_month
    * arrival_date_day_of_month
    * arrival_date_week_number
    * deposit_type
    * agent
    * company
    * customer_type    
* Useless (removed):
    * reservation_status
    * reservation_status_date
