# IN-PLAY-BETTING

This project is about predicting the outcome of football matches. The outcomes are categorized into three classes: Home team wins, Away team wins, and Draw. The project is divided into several notebooks, each serving a specific purpose.

## EDA_n_training.ipynb

This notebook is responsible for the initial exploration of the dataset and training of the model for predicting home team wins. It includes data preprocessing, exploratory data analysis, and model training. The model used for prediction is Logistic Regression. The trained model is then saved for future use.

## away_train.ipynb

This notebook is similar to the previous one but is responsible for predicting if the away team wins. It follows the same steps: data preprocessing, exploratory data analysis, and model training. The model used for prediction is also Logistic Regression. The trained model is then saved for future use.

## draw_train.ipynb

This notebook is responsible for predicting if the match ends in a draw. It follows the same steps as the previous notebooks: data preprocessing, exploratory data analysis, and model training. The model used for prediction is Logistic Regression. The trained model is then saved for future use.

## prediction.ipynb

This notebook is responsible for making the final prediction. It loads the previously trained models and uses them to predict the outcome of the matches. The prediction is based on the probabilities given by each model for each class. The class with the highest probability is chosen as the final prediction. The weights of the probabilities are adjusted based on the precision of each model's performance. The final prediction score on the testing dataset is approximately 68.8% .

## Conclusion

This project demonstrates the process of predicting the outcome of football matches using machine learning. It includes data preprocessing, exploratory data analysis, model training, and prediction. The models used for prediction are trained using Logistic Regression and their performance is evaluated based on their precision. The final prediction is made by comparing the probabilities given by each model for each class and choosing the class with the highest probability.
