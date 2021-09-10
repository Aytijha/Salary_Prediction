# Salary_Prediction
A Python-based Machine Learning hands-on project to predict the Salary of an average Adult.

## Features and Limits

- Works best when age of the worker is in the inclusive range of [17, 90].
- Works perfectly for workers of all Education levels, viz. HS-grad/Bachelors etc.
- Works perfectly for workers of all Marital statuses, viz. married/divorced/single etc.
- Takes the Racial data (viz. Asian, Black, White etc) and Relationship data (viz. Husband/ Wife/ Own-child/ Other-relative/ No-relationships etc) to mimic the real-world scenario and predict as accurately as possible.
- Works for a wide range of Ocupations including Sales, Craft-repair, Tech-support, Fishing, Farming, Executive-Managerial, and various other fields of job.

Takes other factors in consideration such Country of Work, Total hours of work per week, etc, and predicts if the salary of the individual is above/below 50K.

> The data used for training the model is mostly dominated
> by US-residents. But to make the model capable of predicting
> non-US salaries as well, data from other places viz. Cuba,
> Taiwan, Mexico, India, etc has been used. But accounting for
> US-dominant data, it's safe to say that the model will have
> a higher accuracy for US-residents' test data, while also
> maintaining a pretty high accuracy for test data from any
> other countries.

## Installation
Python modules required to train/test the model or run the source file include:
> Pandas (works for all versions),
> Numpy,
> Seaborn (if if user is interested in viewing the CSV data in a graphical format),
> Matplotlib.

## Files present

- adult_data.csv containing the Training data.
- adult_test.csv containing the data used to test the model's accuracy.
- salary_pred_engine.ipynb containing the source code to train the model.
