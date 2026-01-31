# DATA4380-AbaloneAgeModel
Estimating the age of abalone traditionally requires counting growth rings on the shell — a process that is both time-consuming and destructive. To address this limitation, we developed and evaluated machine learning models that predict the number of abalone rings using non-invasive physical measurements such as length, diameter, height, and weight.

We developed a tuned Random Forest model achieved the best regression performance (R² = 0.586, RMSE = 2.116), with XGBoost performing similarly. Additionally, we also decided to frame as a classification task, the models achieved an Accuracy of 0.677 and a Macro-F1 score of 0.695, demonstrating balanced predictions across age groups.
