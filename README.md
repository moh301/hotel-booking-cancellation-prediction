# Hotel Booking Cancellation Prediction

## Overview

This project focuses on predicting whether a hotel booking will be canceled or not using different machine learning models.

The main goal was to go through a full machine learning workflow starting from data cleaning to model comparison.

---

## Dataset

The dataset contains information about hotel bookings such as:

* Booking details
* Customer information
* Stay duration
* Pricing and some economic indicators

---

## Steps Done

### Data Cleaning

* Handled missing values
* Removed unnecessary and leakage columns
* Fixed data types

### Exploratory Data Analysis (EDA)

* Analyzed cancellation behavior
* Found that:

  * City hotels have higher cancellation rates
  * Higher lead time increases the chance of cancellation

### Preprocessing

* Encoded categorical variables
* Converted all features into numerical format

---

## Models Used

* Logistic Regression
* Decision Tree
* Tuned Decision Tree
* K-Nearest Neighbors (KNN)
* Random Forest

---

## Results

* Logistic Regression: ~68%
* Decision Tree: ~92% (overfitting)
* Tuned Decision Tree: ~86%
* KNN: ~88%
* Random Forest: ~95% (best performance)

---

## Conclusion

Random Forest gave the best results on this dataset.

The project shows how proper preprocessing and model comparison can significantly improve performance.

---

## Tools

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
