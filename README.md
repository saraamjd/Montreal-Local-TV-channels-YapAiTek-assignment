## Montreal-Local-TV-channels-YapAiTek-assignment!
This project is a Regression Supervised Learning method for Montral Local TV Channels dataset.
We aim to develope a model that predict Market Share_total for the next season based on the training dataset.
For preprocessing, first we have to find the null values and drop them.
Second, we need to factorize the columns with nonnumeric value in order to find the correlation between Market Share_total and other columns and use them for predictions.
For predictions, we apply LinearRegression, Lasso, Ridge, DecisionTreeRegressor, RandomForestRegressor models and evaluate their performance. Then we use the model with the highest score (RandomForestRegressor) for prediction.
we also apply Sequential Neural Network for the prediction
Both predictions will be saved into CSV files.
