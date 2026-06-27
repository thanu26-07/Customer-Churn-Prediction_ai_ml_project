# Customer Churn Prediction using Random Forest Classifier

## Project Objective

The objective of this project is to predict whether a bank customer is likely to leave the bank (churn) based on customer information such as credit score, age, balance, tenure, and account details. This helps businesses identify customers at risk and improve customer retention strategies.

---

## Dataset Used

* **Dataset:** Bank Customer Churn Dataset
* **Total Records:** 10,000
* **Target Variable:** Exited

  * 0 → Customer Stayed
  * 1 → Customer Left

### Features Used

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Balance
* Number of Products
* Has Credit Card
* Active Member
* Estimated Salary
* Satisfaction Score
* Card Type
* Points Earned

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Google Colab

---

## Machine Learning Algorithm

* Random Forest Classifier

---

## Steps Performed

1. Imported required libraries.
2. Loaded the customer churn dataset.
3. Checked dataset information and missing values.
4. Removed unnecessary columns.
5. Encoded categorical features using Label Encoding.
6. Split the dataset into training and testing sets.
7. Trained a Random Forest classifier.
8. Predicted customer churn.
9. Evaluated the model using Accuracy, Confusion Matrix, and Classification Report.
10. Visualized feature importance.
11. Calculated churn probability for predictions.

---

## Model Performance

* Algorithm: Random Forest Classifier
* Accuracy: **86.5%**

---

## Project Outcome

The model successfully predicts whether a customer is likely to churn based on customer demographics and banking information. It can assist banks in identifying high-risk customers and improving customer retention strategies.

---

## Future Improvements

* Deploy the model as a web application using Streamlit.
* Compare Random Forest with other machine learning algorithms.
* Perform hyperparameter tuning to improve prediction accuracy.
* Add batch prediction for multiple customers.

The purpose of this project is to predict whether a customer is likely to leave the bank based on customer information. Through this project, I gained hands-on experience in data preprocessing, machine learning model development, and performance evaluation using Scikit-learn.
