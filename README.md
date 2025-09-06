NH₃ Concentration Prediction

This project focuses on predicting ammonia (NH₃) concentration using regression techniques and advanced curve fitting methods. It involves data analysis, model building, and evaluation to determine the most accurate predictive approach.

🔑 Key Steps

Data Handling

Loaded datasets containing ammonia concentration vs. sensor response, known concentrations, and interfering gases.

Performed exploratory data analysis (EDA) to understand distributions and trends.

Visualization

Applied Seaborn and Matplotlib to plot concentration-response relationships.

Highlighted sensor response patterns and anomalies.

Modeling Approaches

Built Linear Regression and Polynomial Regression models for NH₃ concentration prediction.

Applied a Five-Parameter Logistic (5PL) model for robust curve fitting, capturing nonlinear response behavior.

Evaluation

Compared models using R² score and error metrics.

Visualized predicted vs. actual curves to assess accuracy.

Insights

Demonstrated that while linear and polynomial models capture trends, the 5PL fit achieves superior robustness and accuracy.

Highlighted potential influence of interfering gases on sensor performance.

📈 Results

Achieved strong predictive performance with polynomial regression models.

5PL model provided the best overall fit (~98–99% R²), making it suitable for sensor calibration tasks.
