# Hotel Cancellation Forecast - Project
The accomodation industry is a 4.1 Trillion Dollar industry in 2021.
In today's fast-paced world, consumers are becoming more flexible with their stays, "Free Cancellation" offers are helping large booking websites like Booking.com and Hotels.com stay competitive by allowing consumers said flexibility.
However, these offers bring an old-new problem to the table - booking cancellations.
In this project we aim to allow accurate forecasting of booking cancellations in order to aid hotels and booking websites correctly anticipate hotel cancellations and act accordingly to prevent loss and maximize capacity.
##### By Oriel Perets & Dafna Meron

### Project setup
#### Importing dependecies:
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
