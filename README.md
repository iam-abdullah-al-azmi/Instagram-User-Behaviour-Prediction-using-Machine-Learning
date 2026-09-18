# Instagram User Behaviour Prediction using Machine Learning

In this project, observation has been made on how different parameters effect the happiness factor of social media (instagram) users using machine learning.

Dataset: [insta-usage-user-behavior-analysis-insights](https://www.kaggle.com/code/raqeebdeveloper/insta-usage-user-behavior-analysis-insights)

Models:

- Base models
  - Linear regression
  - Randomforest regressor
  - Gradientboosting regressor
- Meta learner
  - Voting regressor
  - Stacking regressor

Since, the dataset was highly correleated, we have performed the principal component analysis (pca) to reduce the high correlation and for better model training.

Optimization:

- GridSearch CV
- RandomSearch CV

Metrices:

- R2 Score
- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)

As the dataset was large, so, we initially run a small experiment to find the best model. After that, we trained the founded best model on full dataset.

To predict the user predicted happiness, we then used gradio for a user interface where user can change the parameter and see how the model predicts.
