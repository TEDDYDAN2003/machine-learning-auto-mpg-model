# machine-learning-auto-mpg-model

The model with thats best is evaluated in terms of:
The highest R² score   
The lowest RMSE/MAE 
…is typically the best for your specific dataset.

feature importance plot shows that displacement has the highest importance score in predicting mpg, it means that changes in engine displacement (the total volume of all the cylinders in an engine) have a strong impact on the fuel efficiency of the vehicle.


🔍 What is Displacement?
Engine displacement is typically measured in liters (L) or cubic inches (cu in).

It represents the size or capacity of an engine.
Larger displacement = larger engine = more air/fuel mixture used per cycle.

⛽ Why Displacement Affects MPG (Miles Per Gallon):
1.Bigger Engines Burn More Fuel

A larger engine requires more fuel to operate, which reduces fuel efficiency.

That means lower MPG.

2.Performance Over Efficiency

High-displacement engines are often built for power/performance, not fuel economy.

Smaller engines are designed to be more fuel-efficient.

3.Weight and Power Correlation

Vehicles with bigger engines are often heavier, needing even more energy to move, which again lowers MPG.
2. Helps detect overfitting
If your model performs great on training data but poorly on CV folds, it’s probably overfitting.

importance of Cross-validation : acts as a safeguard — it simulates how your model would do on truly unseen data
