# Demand-forecasting
Strategic Integration of Cutting Edge Analytics to Elevate and Resilience Supply Chain Operations

Project Overview
This project focuses on leveraging advanced analytics and artificial intelligence (AI) to improve supply chain management by enhancing resilience, efficiency, and ethical decision-making. It presents an AI-driven framework that includes demand forecasting, resilience assessment, and the integration of explainable AI for better transparency and decision-making.

Key Objectives
Demand Forecasting: Use of deep learning models to predict demand and optimize inventory, production schedules, and distribution strategies.
Resilience Metrics: Quantitative metrics for measuring resilience based on recovery time, flexibility, and operational continuity.
Ethical AI: Promote responsible AI use, addressing fairness, bias mitigation, and privacy concerns.
Explainable AI: Ensure transparency in decision-making by providing clear reasoning behind AI predictions and assessments.
Dataset
Source: DataCo Global Supply Chain Dataset
Size: 180,519 records and 53 columns, covering various aspects of supply chain operations like orders, products, customers, shipping, and business metrics.
Focus Products: The analysis focuses on three main products:
Perfect Fitness Perfect Rip Deck
Nike Men’s CJ Elite 2 TD Football Cleat
Nike Men’s Dri-FIT Victory Golf Polo
Methodology
Data Preprocessing:

Removed irrelevant columns.
Handled missing values (none found).
Addressed outliers using the Interquartile Range (IQR) method.
Data Transformation:

Extracted relevant time features (e.g., week, weekends).
Calculated metrics like shipping delay.
Modeling:

Applied various machine learning models:
Random Forest Regressor
Fully Connected Neural Network
Long Short-Term Memory (LSTM)
Prophet
Evaluated models using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
Inventory Optimization:

Calculated Reorder Points (ROP), Safety Stock, and Economic Order Quantity (EOQ) to optimize inventory levels based on demand forecasts.
Results
Random Forest Regressor showed superior performance in predicting demand across all three products, with better accuracy in the Nike datasets.
Prophet performed reasonably well, especially for products with seasonal patterns but was less accurate than Random Forest.
Model Evaluation
The models were evaluated using standard error metrics:

MAE (Mean Absolute Error): Measures the average magnitude of prediction errors.
MSE (Mean Squared Error): Penalizes larger errors.
RMSE (Root Mean Squared Error): Reflects typical error size.
Additionally, SHAP (SHapley Additive exPlanations) analysis was employed to interpret model predictions and understand feature importance.

Key Features
Explainable AI: Improved transparency in decision-making by explaining AI-driven insights.
Inventory Optimization: Helped businesses maintain the right stock levels and improve operational efficiency.
Challenges
Handling data volatility and uncertainties in demand forecasting.
Capturing seasonality and trends accurately across different products.
Integrating ethical AI to ensure fairness and avoid biases.
