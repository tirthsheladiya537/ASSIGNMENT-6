# Sales Forecasting Case Study

##  About the Project

This is my **Module 26 - Sales Forecasting Case Study**.

The main purpose of this project is to understand how historical sales data can be used to predict future sales.

I used a **Sales Forecasting dataset from Kaggle** and built a simple forecasting model using **Python and Linear Regression**.

---

##  Objective

The objectives of this project are:

* Explore sales data
* Check missing values
* Convert dates into the correct format
* Extract useful date features
* Understand sales trends
* Split data into training and testing data
* Build a Linear Regression model
* Predict sales
* Evaluate the model

---

##  Dataset

The dataset used in this project is:

**Store Item Demand Forecasting Dataset**

Source: Kaggle

The dataset contains:

* `date` - Date of sales
* `store` - Store number
* `item` - Item number
* `sales` - Number of items sold

Dataset: https://www.kaggle.com/competitions/demand-forecasting-kernels-only/data

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab
* Jupyter Notebook

---

##  Project Steps

### 1. Import Dataset

The Kaggle `train.csv` file is loaded using Pandas.

### 2. Explore Data

I checked:

* Number of rows and columns
* Column names
* Data types
* Missing values

### 3. Data Preprocessing

The date column was converted into datetime format.

I extracted:

* Year
* Month
* Day
* Day of Week

### 4. Data Visualization

I created graphs to understand the sales trend over time.

### 5. Training and Testing

The data was divided into:

* 80% Training Data
* 20% Testing Data

The split was done according to time order.

### 6. Machine Learning Model

I used **Linear Regression** to predict sales.

### 7. Model Evaluation

The model was evaluated using:

* MAE
* RMSE
* R² Score

### 8. Future Prediction

The trained model was used to make a simple future sales forecast.

---

##  Model

### Linear Regression

Linear Regression is a simple machine learning algorithm that finds a relationship between an input and an output.

In this project:

**Input:** Date/Time

**Output:** Sales

The model learns the sales trend from historical data and uses it to make predictions.

---

##  Evaluation Metrics

### MAE

Mean Absolute Error tells us the average difference between actual and predicted sales.

### RMSE

Root Mean Squared Error measures prediction error and gives more importance to larger errors.

### R² Score

R² Score tells us how well the model explains the variation in the sales data.

---

##  Project Files

```text
Sales-Forecasting/
│
├── Sales_Forecasting.ipynb
├── README.md
├── requirements.txt
└── dataset/
    └── train.csv
```

-

---

##  Google Colab

https://colab.research.google.com/drive/1h-cxkJqPEant8QvM8fCQpphCkq4uYmno?usp=sharing


---

##  Conclusion

This project helped me understand the basic process of sales forecasting.

I learned how to:

* Load a dataset
* Clean data
* Work with dates
* Visualize sales
* Train a machine learning model
* Make predictions
* Evaluate model performance

This project is created for learning and academic purposes.
