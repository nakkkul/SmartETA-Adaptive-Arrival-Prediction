# ETA-Predictive-Analytics

Introduction :-
The objective of this project was to design and implement a machine learning model capable of predicting the Estimated Time of Arrival (ETA) for routes in a fictional city. The system aims to factor in various elements such as the distance of the route, traffic conditions, the number of turns, and traffic lights, among others, to make accurate predictions.

The data was simulated, and various features were engineered to capture the complexity of real-world traffic and route characteristics. Two machine learning models, Decision Tree Regressor and Random Forest Regressor, were employed to predict the ETA, and their performances were compared.

A key observation was that "Time of Day" and "Day of the Week" did not have a significant impact on ETA, whereas "Distance," "Current Speed," and "Historical Average Speed" were the most influential features.

Model Development :-
Two models were trained on this dataset:

Decision Tree Regressor
Random Forest Regressor

Both models were evaluated using the Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
Given these results, the Random Forest Regressor is better suited for the ETA prediction task as it captures the complexities and non-linear relationships more effectively.

Future Improvements :-
Hyperparameter Tuning.
Further fine-tuning of the Random Forest parameters (e.g., number of trees, depth of trees) could improve the model’s accuracy even more.

Conclusion :-
The Random Forest Regressor has proven to be a strong model for predicting ETA in this simulated city scenario, outperforming the Decision Tree Regressor. The focus on distance, current speed, and historical speed as primary features was key to achieving accurate predictions. Future enhancements can further refine the model, making it suitable for real-world applications where accurate ETA predictions are crucial for navigation and logistics.
