🌫️ Visibility Climate Prediction

This project focuses on building a machine learning model to predict visibility levels based on various weather and climate features. Accurate visibility prediction is crucial for climate-sensitive sectors such as aviation, transportation, and public safety.

🔍 What Was Done:
Developed a supervised ML model to classify visibility levels, using historical weather data.

Performed extensive Exploratory Data Analysis (EDA) to understand the relationships between visibility and features like temperature, humidity, wind speed, etc.

Applied feature engineering to improve model performance and interpretability.

Evaluated the model using key metrics such as precision, recall, and accuracy.

### 🔍 Correlation Heatmap of Weather Features

This heatmap highlights the relationships between various weather variables. Features like **Dry Bulb Temperature**, **Dew Point**, and **Wind Speed** show moderate to strong correlations, helping us identify impactful predictors for visibility.
![Correlation Heatmap](images/correlation_heatmap.png)

### 📊 Distribution of Key Weather Variables

Histograms reveal how weather features are distributed across the dataset, useful for understanding feature behavior before modeling.
![Feature Distributions](images/feature_distribution.png)


📈 Results:
Achieved around 85% accuracy in predicting visibility levels.

Obtained 80–90% precision and recall across key visibility categories, indicating strong performance in identifying correct visibility conditions.

Validated model performance using a confusion matrix, showing high reliability in real-world scenarios.

🛠️ Tech Stack:
Python, Pandas, Scikit-learn, Seaborn
