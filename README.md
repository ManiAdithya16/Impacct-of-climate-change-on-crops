This project, "The Impact of Climate Change on Agricultural Productivity", analyzed the effect of rainfall and temperature on maize and soybean yields using various machine learning models. The study demonstrated how climate change impacts crop production and provided predictive models and insights for better agricultural decision-making.

Key Features & Methodology
Data Preprocessing: Comprehensive steps including data loading, handling missing values, and scaling/normalizing numerical features in the dataset, which comprises Area, Item, Year, average_rain_fall_mm_per_year, pesticides_tonnes, avg_temp, and hg/ha_yield.

Machine Learning Models:

Random Forest Classifier: Utilized for classification tasks related to crop yield, demonstrating high accuracy (e.g., 98% on the test set). This model also showed the lowest Root Mean Squared Error (RMSE) for yield prediction compared to other regression models like Linear Regression, Lasso, and Elastic Net.

k-Nearest Neighbors (kNN): Explored for classification, with its performance evaluated across different k values.

Linear Regression: Applied for understanding the relationship between individual climatic attributes and yield.

Decision Tree: Employed for analyzing information gain from various features.

Performance Evaluation: Models are rigorously evaluated using standard regression metrics (Mean Absolute Error, Mean Squared Error, R2 score, etc.) and classification metrics (Accuracy, Precision, Recall, F1-score, and Confusion Matrix).
