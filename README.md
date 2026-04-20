# Final_Project_DTS2
By: Bailey Allard

This project I going to hopefully build a machine learning system that can predict movie ratings based on movies key features such as budget, revenue, genre, runtime, studio, language and others engineered features in order for future studios and producers to use this information to achieve higher ratings for their movies. What I was able to do so far is compare two different machine learning approachs so see which model either Random Forest or Neural network models are the best fit for this goal.

Dataset:https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

This is the dataset that I will be using for this project it includes 2 different csv files with ~5000 observations and 20+ features. With the target feature being vote_average (movie rating).
*14 Strings
*4 Integers
*2 Decimals
*4 Other

The install library requirements are:
*pandas
*numpy
*matplotlib
*seaborn
*scikit-learn
*tensorflow
*time


Final Models used:
Optimized Random Forest Model
Optimized Neural Network Model


| Model                    | MAE    | MSE    | RMSE   | R²     | Training Time (s) |
| ------------------------ | ------ | ------ | ------ | ------ | ----------------- |
| Optimized Random Forest  | 0.5906 | 0.6651 | 0.8155 | 0.2485 | 0.62              |
| Optimized Neural Network | 0.6024 | 0.6712 | 0.8193 | 0.2416 | 5.47              |


Final Model Recommendation: Optimized Random Forest Model
*Better predictive performance
*Faster training time
*Greater interpretability

