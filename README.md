# BehaviorBasedWeightModeling

This projects goal was to predict an individual’s weight based on various physical and lifestyle attributes using regression models. I employed multiple techniques including Linear Regression, Decision Tree, Random Forest, and XGBoost to evaluate predictive performance. Among these, the Random Forest Regressor performed best with an R² of 0.875, MAE of 5.52, and MAPE of 7.43%.

Beyond accuracy, I explored which features had the greatest influence on weight. According to the Random Forest model, the most important predictors were height, family history with overweight, physical activity level (FAF), and daily water consumption (CH2O).

Linear Regression provided additional interpretability:

Height had by far the strongest positive coefficient (~127), confirming its dominant role in predicting weight.

Other significant positive contributors included family history, meal frequency (FCVC), and eating habits like CAEC (consumption of food between meals).

Interestingly, factors like gender, sugar consumption (SCC), and alcohol consumption (CALC) had negative coefficients, suggesting nuanced relationships.

This project demonstrates the complementary value of both interpretable models and ensemble techniques in understanding and predicting health-related outcomes.

