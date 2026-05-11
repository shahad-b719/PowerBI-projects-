---
# 💼 Business Scenario 
--- 
Uber has been facing several challenges in the New Delhi area with high cancellation rates, declining customer satisfaction and low demand for certain vehicle types. You have been hired as a consultant by Uber to analyze the trends in the dataset provided and suggest actionable recommendations to overcome these challenges.

# 🧹Data Cleaning (Python)
⭐Booking_Id = Unique identifier

------
## 1. duplicated().sum() = 1,233 duplicates
   Used to assess whether there were any duplicates in the Booking ID column
   
## 2. drop_duplicates()
   used to remove duplicates.

## 3. df.dtypes()
   Used to determine the data type of each variable, several variables were identified to have the wrong data type.

## 4. pd.to_datetime()
   Date and time were changed from object into datetime data types, and seconds were removed from time.

## 📋The total number of rows is now 148,767.

<img width="383" height="217" alt="image" src="https://github.com/user-attachments/assets/da03656f-b008-4165-81bb-22c5c1edf240" />
