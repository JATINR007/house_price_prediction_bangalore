# 🏠 Bangalore House Price Prediction

## 📌 Overview
A Machine Learning project that predicts residential property prices in Bangalore, Karnataka, using Python and a Random Forest Regressor. The project covers data preprocessing, model training, evaluation, and interactive price prediction using seven property details.

## 🎯 Objectives
- Predict house prices using property features.
- Apply data preprocessing and feature engineering.
- Train and evaluate a regression model.
- Generate predictions with default values for empty inputs.

## 📊 Dataset
**Source:** [Housing Price Prediction Dataset – Kaggle](https://www.kaggle.com/datasets/ameyachopade/housing-price-prediction-dataset)

The dataset is downloaded using `KaggleHub` and processed using Pandas and NumPy. Bangalore-specific predictions depend on the dataset containing suitable Bangalore property records.

## 🛠️ Technologies Used
- **Python** – Programming language
- **Pandas & NumPy** – Data processing
- **Scikit-learn** – Machine Learning and evaluation
- **Matplotlib & Seaborn** – Data visualization
- **KaggleHub** – Dataset download
- **Google Colab** – Development environment
- **Joblib** – Model serialization

## ⚙️ Workflow
1. Download and inspect the dataset.
2. Clean data and handle missing values.
3. Encode categorical features and prepare numerical features.
4. Split data into training and testing sets (80:20).
5. Train a Random Forest Regressor.
6. Evaluate performance using MAE, RMSE, and R².
7. Predict house prices using seven property inputs.
8. Save the trained model for future use.

## 🏡 Prediction Features
The prediction interface accepts:
- Location
- Total area (sq. ft.)
- BHK
- Number of bathrooms
- Property type
- Furnishing status
- Parking spaces

Default values are used when inputs are left blank. These features must match the dataset and the model's training columns.

## 🚀 Getting Started

### Google Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Create a new notebook.
3. Install the dependencies:

   ```bash
   !pip install -q kagglehub pandas numpy scikit-learn matplotlib seaborn joblib
   ```

4. Run the notebook cells in order to download the data, train the model, evaluate it, and generate predictions.

### Local Setup
```bash
git clone https://github.com/YOUR_USERNAME/bangalore-house-price-prediction.git
cd bangalore-house-price-prediction
pip install -r requirements.txt
python bangalore_house_price_prediction.py
```

## 📈 Evaluation Metrics
- **MAE:** Average absolute prediction error.
- **RMSE:** Error metric that penalizes larger mistakes.
- **R² Score:** Measures how well the model explains price variation.

Actual evaluation results should be added after running the model on the dataset.

## 🔮 Future Improvements
- Compare multiple regression algorithms.
- Tune hyperparameters for improved performance.
- Improve location-based features.
- Develop a Streamlit web application.
- Evaluate using verified Bangalore-specific housing data.

## ⚠️ Limitations
Predictions depend on dataset quality, feature availability, and market conditions. Results are estimates, not guaranteed property valuations.

## 👨‍💻 Author
**Jatin Rajeev Kumar**  



