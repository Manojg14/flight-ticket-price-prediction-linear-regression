# ✈️ Flight Ticket Price Prediction using Machine Learning

## 📌 Project Overview

Airfare prices fluctuate based on several factors such as airline, departure time, arrival time, journey duration, source city, destination city, travel class, number of stops, and days left before departure.

This project develops a **Machine Learning Regression Model** to predict flight ticket prices using historical flight data. It demonstrates a complete end-to-end Machine Learning workflow, including data cleaning, exploratory data analysis (EDA), feature engineering, preprocessing, model training, evaluation, and prediction.

---

# 📂 Repository Structure

```
Flight-Ticket-Price-Prediction/
│
├── Dataset/
│   └── Flight_Fare.csv
│
├── Notebook/
│   └── flight-ticket-price-prediction-linear-regression.ipynb
│
├── Images&Video/
│   └── Screen Shots/ 
│   └── Graphs
|   └── flight-ticket-price-prediction-linear-regression demo.mp4
|
├── README.md

```

---

# 🎯 Business Problem

Flight ticket prices are dynamic and influenced by multiple factors. Customers often struggle to determine whether a ticket price is reasonable or if they should wait for a better deal.

This project aims to build a Machine Learning model capable of predicting flight ticket prices, helping travelers make informed booking decisions and enabling businesses to optimize pricing strategies.

---

# 🎯 Project Objectives

- Understand the flight ticket dataset
- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess the data
- Handle missing values and outliers
- Build and evaluate a regression model
- Predict flight ticket prices accurately

---

# 📊 Dataset Information

The dataset contains information about flight bookings and ticket prices.

| Feature | Description |
|----------|-------------|
| Airline | Name of the airline |
| Source City | Departure city |
| Destination City | Arrival city |
| Departure Time | Flight departure time |
| Arrival Time | Flight arrival time |
| Stops | Number of stops |
| Duration | Total journey duration |
| Days Left | Days remaining before departure |
| Class | Economy / Business |
| Price | Flight ticket price (Target Variable) |

> **Target Variable:** `Price`

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 📈 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset Shape
- Data Types
- Missing Value Analysis
- Duplicate Record Check
- Statistical Summary
- Correlation Analysis
- Outlier Detection
- Feature Distribution
- Target Variable Distribution

### Visualizations

- Histograms
- Box Plots
- Count Plots
- Scatter Plots
- Pair Plot
- Correlation Heatmap
- Bar Charts

---

# 🧹 Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate records
- Checked for missing values
- Verified data types
- Removed unnecessary columns 
- Treated outliers using the IQR method

---

# ⚙️ Feature Engineering

Feature engineering techniques included:

- One-Hot Encoding for nominal categorical variables
- Feature Selection
- Created model-ready dataset

---

# 🔄 Data Preprocessing

The preprocessing pipeline included:

- Missing Value Handling
- Outlier Treatment
- Label Encoding
- One-Hot Encoding
- Feature Scaling 
- Train-Test Split (80:20)

---

# 🤖 Machine Learning Model

### Regression Algorithm Used

- Linear Regression

---

# 📏 Model Evaluation Metrics

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

# 📈 Project Workflow

```
Data Collection
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
Data Preprocessing
        ↓
Train-Test Split
        ↓
Linear Regression Model
        ↓
Model Evaluation
        ↓
Flight Ticket Price Prediction
```

---

# 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/Flight-Ticket-Price-Prediction.git
```

### Navigate to the project directory

```bash
cd Flight-Ticket-Price-Prediction
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```
---

# 📊 Expected Output

The trained model predicts the estimated **flight ticket price** based on:

- Airline
- Source City
- Destination City
- Departure Time
- Arrival Time
- Number of Stops
- Journey Duration
- Travel Class
- Days Left Before Departure

---

# 📚 Learning Outcomes

This project demonstrates:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Regression Modeling
- Model Evaluation
- Machine Learning Workflow
- Git & GitHub Project Management

---

# 👨‍💻 Author

**Manoj G**

**Aspiring Ai Engineer | Data Scientist | Machine Learning Engineer | Data Analyst**
---
