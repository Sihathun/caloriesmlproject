Evaluation Technique
To measure how well the machine learning models performed, we used two common evaluation metrics: R² Score and Mean Squared Error (MSE).

The R² Score (also called the coefficient of determination) tells us how much of the variation in calorie burn can be explained by the model. A score closer to 1 means better performance. For example, an R² score of 0.9982 means the model predicted the calorie burn almost perfectly.

The Mean Squared Error (MSE) measures how far off the model’s predictions are from the actual values. It calculates the average of the squares of the errors (the difference between predicted and actual values). A lower MSE means the predictions are more accurate.

We used these metrics on the test data (20% of the dataset that was not used for training) to check how well the models generalize to new, unseen data. This helps avoid overfitting and gives a good idea of how the model would perform in real-world scenarios.
