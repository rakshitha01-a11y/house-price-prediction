# paris house price prediction
📌 Project Title & Overview

Title: Paris Housing Price Prediction using Advanced Machine Learning.

Summary: An end-to-end data science project that analyzes property attributes in Paris to predict market values with high precision.

🎯 Core Objectives

Data Insight: Analyze historical housing data to find pricing trends.

Key Factor Identification: Determine which features (e.g., luxury amenities vs. size) impact price most.

Algorithm Development: Build and train multiple regression models.

Performance Benchmarking: Compare models to find the most accurate prediction engine.

📊 Dataset & Column Descriptions

A detailed look at the inputs our model uses:

squareMeters: The total area of the house (The most significant factor).

isNewBuilt: Indicates if the property is a recent construction.

hasPool / hasGarage: Presence of luxury and utility amenities.

cityPartRange: The neighborhood "rank" or sector within Paris.

numPrevOwners: The history of the property ownership.

price: The Target Variable (what the model is trying to guess).

🛠️ Technologies Used

Python: The primary programming language.

Pandas & NumPy: For data manipulation and mathematical operations.

Matplotlib & Seaborn: For data visualization and heatmaps.

Scikit-Learn: For building the Machine Learning pipeline.

Google Colab: The cloud-based environment used for development.

⚙️ Project Workflow (Step-by-Step)

Data Collection: Gathering the Paris Housing dataset into the environment.

Data Cleaning: Removing duplicates and handling any missing information.

Exploratory Data Analysis (EDA): Visualizing correlations through heatmaps and scatter plots.

Feature Engineering: Selecting the most important variables for the model.

Data Preprocessing: Scaling numbers and encoding categories into a machine-readable format.

Model Training: Teaching the computer using 80% of the available data.

Model Evaluation: Testing accuracy on the remaining 20% of the data.

📈 Models Implemented

Linear Regression: To establish a simple baseline.

Decision Tree Regression: To capture non-linear, branching data patterns.

Random Forest Regression: To use an ensemble of trees for stable predictions.

Gradient Boosting Regression: To minimize errors through sequential learning.

🏆 Evaluation Metrics

We measure success using:

R² Score: How well the model fits the data (closer to 1.0 is better).

Mean Absolute Error (MAE): The average difference between predicted and actual price.

Mean Squared Error (MSE): A metric that penalizes larger prediction errors.

📝 Final Results & Conclusion

Winning Model: Based on our tests, Random Forest (or Gradient Boosting) typically provides the highest R² score (around 0.88 - 0.92).

Visual Proof: A final graph showing how closely our predictions follow the actual market prices.

👩‍💻 Author

Rakshitha V

Data Science Student

GitHub:[https://github.com/rakshitha01-a11y/house-price-prediction/blob/main/README.md]

[https://github.com/rakshitha01-a11y/house-price-prediction/blob/main/Paris_house_price_prediction.ipynb]

[https://github.com/rakshitha01-a11y/house-price-prediction/blob/main/ParisHousing.csv]
