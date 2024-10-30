# Dynamic ETA Prediction System

Introduction :-
This project provides a comprehensive solution for estimating the Estimated Time of Arrival (ETA) across city routes, simulating real-world scenarios using synthetic data. By leveraging OpenStreetMaps data and generating variables for route complexity, traffic conditions, and time of day, the project builds a robust framework for analyzing and predicting ETA dynamically. The system allows for continuous updates to ETA predictions as new data on route conditions become available, enabling flexible, segment-level estimations that adjust in real-time.

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
