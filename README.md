# Heart-Disease-Prediction-Analysis-V2
This is an in-depth analysis of heart disease prediction utilizing machine learning techniques implemented in Python. Heart disease is a prevalent and critical health concern globally, and predictive models can significantly aid in early diagnosis and intervention.

## Key Features:
- **Data Exploration:** Utilizing Pandas, Numpy, and Matplotlib, the analysis begins with exploring the heart disease dataset.
- **Model Building:** Employing a Random Forest Classifier, the model is trained on the dataset after preprocessing steps such as train-test split.
- **Model Evaluation:** The trained model is evaluated using various metrics such as accuracy, precision, recall, and F1 score.
- **Cross Validation:** Cross-validation techniques are applied to assess model performance more robustly.
- **ROC Curve:** The Receiver Operating Characteristic (ROC) curve and Area Under the Curve (AUC) are plotted to evaluate the model's predictive performance.
- **Confusion Matrix:** Visualizing the confusion matrix to understand the model's performance in terms of true positives, false positives, true negatives, and false negatives.
- **Regression Analysis:** Additionally, regression analysis is conducted, including the calculation of R² score, Mean Absolute Error (MAE), and Mean Squared Error (MSE).
- **Hyperparameter Tuning:** Both RandomizedSearchCV and GridSearchCV techniques are used for hyperparameter tuning to optimize model performance.
- **Model Serialization**: The final optimized models are serialized using both Pickle and Joblib for future use.

This analysis aims to provide valuable insights into heart disease prediction and offers well-documented code for reproducibility and further research.
