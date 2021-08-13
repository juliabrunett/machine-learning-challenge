# machine-learning-challenge
**Machine Learning Homework:** This project focused on taking potential exoplanet measurement data & using machine learning libraries to create a model that will successfully predict an outcome with new data at a 90% success rate.

**models:**
- julia_brunett.sav: Best model created to predict new exoplanets

**resources:**
- exoplanet_data.csv: Original data file with exoplanet measurement data

***model_1.ipynb***
- Random Tree Classifier model

***model_2.ipynb***
- Logistic Regression Classifier model

Create a README that reports a comparison of each model's performance as well as a summary about your findings and any assumptions you can make based on your model (is your model good enough to predict new exoplanets? Why or why not? What would make your model be better at predicting new exoplanets?).


## Overall Results Comparison:
- Best Model: Model 1

### Model 1 - Random Tree Classifier
- *Training Results:* 1.0
- *Testing Results:* 0.897
- **Summary:** This model is the best model, with a testing score of 0.897. This means that the model can predict an outcome correctly 89.7% of the time. This model would be good to predict which exoplanets are not true, as it has a pretty good success rate of predicting "False Positives".

Before Tuning:
![Model-1 Before](./images/model_1_b.png)

After Tuning:
![Model-1 After](./images/model_1_a.png)

### Model 2 - Logistic Regression Classifier
- *Training Results:* 0.889
- *Testing Results:* 0.886
- **Summary:** This model has a testing score of 0.886, which is good, but not the best compared to the first model. This model could be improved by using GridSearch again to see if there are any other parameters that can be modified to produce better results.

Before Tuning:
![Model-2 Before](./images/model_2_b.png)

After Tuning:
![Model-2 After](./images/model_2_a.png)





