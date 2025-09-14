# **Flight Ticket Price Prediction - Kaggle Competition**

## **Introduction**

Welcome to the Kaggle competition where we predict the price of flight tickets using various features such as airline name, departure time, flight duration, and more. This project utilizes machine learning techniques to build models that forecast flight prices based on the provided training dataset.

---

## **Project Overview**

The goal of this project is to predict the price of flight tickets based on a set of features. By leveraging various data preprocessing, feature engineering, and model-building techniques, we aim to achieve an accurate prediction model for flight prices.

### **Key Features:**
- **airline**: Name of the airline company
- **flight**: Flight code (identifier for the flight)
- **source**: City from which the flight departs
- **destination**: City where the flight lands
- **departure**: Time period at which the flight takes off
- **arrival**: Time period at which the flight lands
- **stops**: Number of stops between source and destination cities
- **class**: Type of seat class (e.g., economy, business)
- **duration**: Time taken for the flight journey in hours
- **days_left**: Number of days between booking and departure
- **price**: The target variable (flight ticket price)

---

## **Project Workflow**

1. **Data Exploration**: 
   - Analyzed the dataset and identified data types, summary statistics, and missing values.
   - Visualized key features using animated plots to gain insights into patterns and trends.

2. **Preprocessing**:
   - Handled missing values by imputation or deletion where necessary.
   - Encoded categorical features (like airline, source, destination) using one-hot encoding.
   - Scaled numerical features to improve model performance.
   
3. **Model Building**:
   - Implemented multiple machine learning models, including linear regression, decision trees, random forests, and more.
   - Used hyperparameter tuning (via GridSearchCV) to optimize model performance.
   
4. **Evaluation**:
   - Compared model performances based on evaluation metrics like RMSE, MAE, and R^2.
   - Fine-tuned the best models for optimal results.

5. **Submission**:
   - Generated predictions for the test dataset.
   - Submitted the predictions to the Kaggle competition leaderboard.

---

## **Visualizations**

![Animated Price Prediction Visualization](assets/animated_visualization.gif)

The visualization below shows an animated exploration of the relationships between different features like flight duration, departure time, and ticket price. By analyzing these patterns, we gain a better understanding of the factors that influence flight ticket prices.

---

## **Technologies Used**

- **Programming Languages**: Python
- **Libraries**:
  - **Pandas**: For data manipulation and analysis.
  - **Matplotlib/Seaborn**: For creating static and animated visualizations.
  - **Scikit-learn**: For building machine learning models and evaluating them.
  - **Keras/TensorFlow** (if deep learning is used for advanced models).
  
---

## **Steps to Reproduce**

### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/flight-ticket-price-prediction.git
cd flight-ticket-price-prediction
