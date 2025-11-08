# Gender-Specific-Analysis-of-Diabetes-Prediction-Using-Machine-Learning

This project, titled “Gender-Specific Analysis of Diabetes Prediction Using Machine Learning,” aims to analyze how gender influences the risk and prediction accuracy of diabetes using patient health data. Diabetes remains one of the world’s most critical chronic diseases, and understanding gender-based differences in its prediction can support more personalized and effective healthcare solutions.

The study uses a publicly available dataset from Kaggle, which includes demographic, lifestyle, and medical features such as age, BMI, blood pressure, glucose levels, and HbA1c levels. The dataset is divided into male and female subsets to explore gender-specific prediction trends. Before modeling, extensive data preprocessing is performed—this includes cleaning, handling missing values, encoding categorical variables, scaling numerical attributes, and addressing class imbalance using SMOTE (Synthetic Minority Oversampling Technique).

Three machine learning models are employed to predict diabetes:

1. Random Forest
2. AdaBoost
3. Support Vector Machine (SVM)

Each model is optimized using Grid Search cross-validation to identify the best hyperparameters and evaluated using metrics such as Accuracy, Precision, Recall, and F1-Score.

The experimental results indicate that Random Forest consistently outperforms the other models across both gender groups, achieving the highest accuracy and balanced performance. AdaBoost performs competitively with slightly lower recall, while SVM shows high precision but struggles with minority class predictions. Interestingly, optimal hyperparameter values vary between male and female datasets, suggesting that gender-specific tuning can enhance model performance.

The project highlights the importance of addressing class imbalance and performing gender-based data analysis for more accurate and fair medical predictions. Future work could explore larger datasets, hybrid ensemble techniques, and explainable AI methods to interpret how individual factors influence diabetes risk differently for men and women.
