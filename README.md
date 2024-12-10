## ⚡ Household Electric Power Consumption Analysis  

### 📖 Project Overview  
This project analyzes household electric power consumption data to identify usage patterns, understand correlations between features, and predict energy consumption using machine learning models.  

### 🎯 Objective  
The objective of this project is to:  
- Explore trends in household energy consumption.  
- Investigate correlations between different electrical parameters.  
- Develop and evaluate an LSTM model for energy usage prediction.  

### 🔍 Key Insights and Features  
- **Seasonality**: Energy consumption is higher in winter and lower in summer.  
- **Patterns in Sub-Metering**: Sub-metering for kitchen and laundry displays unique trends over time.  
- **Correlation Analysis**: Strong interdependence observed between `Global_active_power` and `Global_intensity`.  
- **Data Gaps**: Missing data suggests potential sensor issues or power outages.  
- **LSTM Model**: Achieved low prediction errors, with a Mean Absolute Error (MAE) of 0.19 kW/day.  

### 🛠 Tools and Technologies Used  
- **Programming Languages**: Python 🐍  
- **Libraries**: TensorFlow, Keras, Scikit-Learn, pandas, matplotlib, seaborn  
- **Techniques**: Time Series Analysis, Data Preprocessing, Machine Learning (LSTM), GridSearchCV  

### 📚 Project Learning  
- Learned LSTM model implementation for time-series data prediction.  
- Mastered feature engineering and data resampling techniques.  
- Improved knowledge of energy data trends and their implications.  
- Gained experience in model optimization using GridSearchCV.  

### 🚀 How to Use the Dashboard  
1. Clone this repository.  
2. Install the required libraries (`TensorFlow`, `Keras`, `pandas`, etc.).  
3. Run the provided code to preprocess data, visualize insights, and train the LSTM model.  

### 📊 Dashboard Preview  
> Below are the graph visualizations included in the report:  

#### 1. **Missing Data Analysis**  
Visualizes the gaps in the data recording process.  

#### 2. **Feature Resampling and Trends**  
Shows the average feature values resampled monthly, quarterly, and yearly.  

#### 3. **Correlation Matrix**  
Illustrates relationships between different features in the dataset.  

#### 4. **Loss and Validation Trends**  
Displays the loss and validation loss during LSTM model training.  

#### 5. **Residuals Observation**  
Compares true and predicted values from the LSTM model.  

### 💡 Why This Project Matters  
Understanding energy usage patterns is essential for:  
- Optimizing energy consumption in households.  
- Enhancing sensor reliability and data recording processes.  
- Developing accurate predictive models for better energy management.  

### 💬 Feedback  
Your feedback is appreciated!  
Feel free to open an issue or contribute by submitting a pull request. 😊  
