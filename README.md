# 📈 Linear Regression Project – E-commerce Customers

## 📖 Overview

This project demonstrates how to build a **Linear Regression Machine Learning model** to predict how much a customer spends yearly based on their behavior on an e-commerce platform.

The project covers the complete machine learning workflow, from exploring the dataset to training, evaluating, and interpreting the model.

---

## 🎯 Project Objective

Predict a customer's **Yearly Amount Spent** using the following features:

* 📱 Time on App
* 💻 Time on Website
* ⏱️ Average Session Length
* 🤝 Length of Membership

---

## 📂 Dataset

The dataset contains information about **500 customers**, including:

| Feature              | Description                             |
| -------------------- | --------------------------------------- |
| Avg. Session Length  | Average time spent per session          |
| Time on App          | Time spent using the mobile application |
| Time on Website      | Time spent browsing the website         |
| Length of Membership | Number of years as a customer           |
| Yearly Amount Spent  | **Target variable**                     |

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📊 Project Workflow

### 1️⃣ Import Libraries

Load all required Python libraries for data analysis and visualization.

### 2️⃣ Load the Dataset

Read the customer dataset using Pandas.

### 3️⃣ Exploratory Data Analysis (EDA)

* Inspect the dataset
* Check data types
* View statistical summaries
* Visualize relationships between variables

### 4️⃣ Feature Selection

Input Features:

* Avg. Session Length
* Time on App
* Time on Website
* Length of Membership

Target:

* Yearly Amount Spent

### 5️⃣ Train/Test Split

Split the dataset into:

* **70% Training**
* **30% Testing**

### 6️⃣ Train the Model

Train a Linear Regression model using Scikit-learn.

### 7️⃣ Make Predictions

Predict customer yearly spending on unseen data.

### 8️⃣ Evaluate the Model

Performance metrics used:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

---

## 📈 Results

The model achieved strong predictive performance with a relatively low prediction error.

The learned coefficients indicate that:

* 📈 **Length of Membership** has the strongest positive impact on yearly spending.
* 📱 **Time on App** is a significant predictor of customer spending.
* 💻 **Time on Website** has very little influence.

---

## 💡 Business Insight

The analysis suggests that customers who spend more time using the **mobile application** and have been members for a longer period tend to spend significantly more money.

This indicates that investing in the **mobile app experience** could potentially generate greater revenue than focusing solely on the website.

---

## 📷 Sample Visualizations

The notebook includes several visualizations, including:

* Scatter Plots
* Joint Plots
* Pair Plots
* Linear Regression Plot
* Residual Distribution

These help understand relationships between customer behavior and yearly spending.

---

## 📚 What I Learned

Through this project, I learned how to:

* Perform Exploratory Data Analysis (EDA)
* Visualize data using Seaborn and Matplotlib
* Build a Linear Regression model
* Split data into training and testing sets
* Evaluate model performance
* Interpret regression coefficients
* Extract business insights from machine learning models

---

## 🚀 How to Run

```bash
git clone https://github.com/Abdelrahman-Noaman/Linear-Rgression-Project.git

cd Linear-Rgression-Project

pip install -r requirements.txt
```

Then open the Jupyter Notebook and run all cells.

---

## 👨‍💻 Author

**Abdelrahman Noaman**

Computer & Software Engineering Student

Cloud & DevOps Enthusiast ☁️

Machine Learning Learner 🤖

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub!
