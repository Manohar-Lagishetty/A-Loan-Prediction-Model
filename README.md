# A-Loan-Prediction-Model
The Loan Prediction System allows you to apply for loans and receive notifications when they are approved.  By the data provided by the applicant, the system notifies the applicant of the loan's availability.

A loan prediction machine learning model using Naive Bayes Gaussian Algorithm is a classification model that predicts whether a loan application will be approved or not based on certain input features. The model assumes that the features are independent of each other and follows a Gaussian distribution.

To improve the performance of the model, hyperparameter tuning using Grid search CV is employed. Grid search is a method for searching the best combination of hyperparameters for a machine learning model. The algorithm exhaustively searches through a grid of hyperparameters to find the best combination that maximizes the model's performance.

The hyperparameters for the Naive Bayes Gaussian Algorithm that will be tuned using Grid search CV include:

priors: The prior probabilities of the classes.

var_smoothing: A smoothing parameter that is added to the variance to ensure that it does not become zero.

The model will be trained on a labeled dataset containing loan applications and their respective approvals. The input features will include attributes such as credit score, income, loan amount, employment status, and others.

Once the model has been trained, it can be used to predict the approval status of a loan application with a high degree of accuracy. The performance of the model will be evaluated based on metrics such as accuracy, precision, recall, and F1 score.

Overall, this loan prediction model can be a useful tool for financial institutions to automate the loan approval process and minimize the risk of loan defaults.
