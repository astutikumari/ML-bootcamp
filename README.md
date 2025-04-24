**Movie Rating Prediction using Machine Learning**

📌 **Project Overview**

This project aims to predict movie ratings using various attributes such as year, duration, votes, genre, director, actors, language, and production details. The model is trained on an Indian IMDb movie dataset and explores multiple machine learning models with proper preprocessing, feature engineering, and performance evaluation techniques.


📂 **Dataset**

    Source: IMDb India movie dataset

    Encoding: ISO-8859-1 (Latin-1) to handle a broader range of characters

    Attributes Used:

    Year

    Duration

    Votes

    Genre

    Director

    Actor 1

    Language




💡 **Feature Engineering**

    Director Success Rate: Average rating for each director

    Genre Average Rating: Average rating for each genre


📈 **Model Training and Comparison**


    Models Used:

     Random Forest Regressor

     XGBoost Regressor

    Pipeline:

     StandardScaler for normalization

     Model training inside Pipeline

     Cross-validation:

    Used 5-fold cross-validation for fair model comparison

    Hyperparameter Tuning:

     Used GridSearchCV for XGBoost with parameters like n_estimators, max_depth, and learning_rate


📊 **Evaluation Metrics**

     Root Mean Squared Error (RMSE)

     R-squared (R²)

    Actual vs. Predicted Rating scatterplot


🔍**Explainability**

    Used SHAP (SHapley Additive exPlanations) to interpret the XGBoost model and visualize feature importance via a beeswarm plot.


✅ **Outcome**

    A trained XGBoost model that predicts movie ratings with good accuracy and interpretable features, useful for recommendation engines or rating estimation platforms.


🛠 **Tools & Libraries**

    Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, SHAP

✅ **Future Improvements**

     Include more granular cast or budget data Incorporate NLP on plot summaries or reviews Deploy the model as a web app or API
