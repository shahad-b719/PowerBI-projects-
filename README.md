---
# 💼 Business Scenario 
--- 
Uber has been facing several challenges in the New Delhi area with high cancellation rates, declining customer satisfaction and low demand for certain vehicle types. You have been hired as a consultant by Uber to analyze the trends in the dataset provided and suggest actionable recommendations to overcome these challenges.

# 🧹Data Cleaning (Python)
⭐Booking_Id = Unique identifier

------
### 1. duplicated().sum() = 1,233 duplicates
   Used to assess whether there were any duplicates in the Booking ID column
   
### 2. drop_duplicates()
   used to remove duplicates.

### 3. df.dtypes()
   Used to determine the data type of each variable, several variables were identified to have the wrong data type.

### 4. pd.to_datetime()
   Date and time were changed from object into datetime data types, and seconds were removed from time.

## 📋The total number of rows is now 148,767.

# Booking value analysis - Power BI

<img width="567" height="328" alt="image" src="https://github.com/user-attachments/assets/0e5e5996-ea6f-452a-bf63-992469346983" />

### Highest booking value times = Weekends 4pm - 9pm and 10 am

### Vehicle type with the highest booking value = Auto 

### Payment method with the highest booking value = UPI 
---
# Cancellations - Power BI

<img width="573" height="322" alt="image" src="https://github.com/user-attachments/assets/c9ececb7-ca1c-4ce5-a5e5-75073bb11e0e" />

### top reason for driver cancellations = Customer related issues

### top reason for customer cancellations = Driver related issues 

### Driver vs Customer Cancellations = Instances of drivers cancellations are 44% higher than customer cancellations

