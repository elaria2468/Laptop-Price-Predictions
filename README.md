# Laptop Price Prediction
This project uses machine learning regression techniques to predict the price of laptops based on their specifications. It is designed as a practical application of data science to understand pricing patterns in consumer electronics.

### Overview

Laptop prices vary based on factors like processor, RAM, GPU, storage type, screen size, and brand. In this notebook, we build a regression model using Scikit-learn to estimate laptop prices from their features. This can help customers, retailers, or businesses make data-informed decisions.

### Dataset

The dataset contains various specifications for laptops, including:

- Brand
- Processor Type
- RAM (in GB)
- Storage (HDD/SSD)
- GPU
- Operating System
- Display Size
- Touchscreen and IPS availability
- Weight

Data has been cleaned, encoded, and transformed for modeling.

### Project Structure

Data Loading & Preprocessing  
Clean missing values, encode categorical data, convert text specs (like weight, storage) to numerical format.

Feature Engineering  
Convert yes/no columns, combine storage types, extract useful numeric features.

Model Building  
Train regression models (Linear Regression, Random Forest, etc.) using Scikit-learn.

Training & Validation  
Split data into train/test sets. Evaluate model using metrics like R², MAE, and RMSE.

Visualization  
Plot distribution of actual vs predicted prices and error metrics to assess model performance.


### Tech Stack

Python | Pandas | NumPy | Scikit-learn | Matplotlib | Seaborn


### Results

The model was able to achieve good predictive accuracy on the test set. Random Forest showed better performance than linear regression. Model performance may improve with more data and feature tuning.

### Future Work

- Deploy using Streamlit or Flask as a web app
- Add support for real-time prediction from user input
- Use advanced models like XGBoost or Gradient Boosting
- Include GPU benchmark or battery specs for more accuracy

---

### License

This project is for educational and research purposes.# Laptop-Price-Predictions
