# Starbucks Capstone
Capstone Project for Udacity Data Scientist Course

## Introduction
The data provided is set to mimic a customers behavior and purchasing habits on the Starbucks mobile app. For context Starbucks sends out regular offers to users of the app. The offer varies from ads, discounts, or buy one get one free deals. Not all users receive offers every week and not all users receive the same offers. This blog post is aimed at a technical audiance but I will do my best to describe the process as simply as possible.

My goal was to combine the data given and predict whether or not a customer was likely to spend $10 or more at Starbucks based on the offer received. To do this I pulled in age, gender, and the avenue the offer was provided through (web, mobile, social , email).

After doing this I joined, cleansed, and explored the data. I created both a Random Forest and Neural Network model to test the data. I used accuracy as my main factor as the goal was to determine whether or not the customer was likely to spend more then $10 based on the factors at hand.

If you would like to read more about my results please view my blog post [here](https://medium.com/p/a55b248a06f3/edit).

## Conclusion
This project was the most in depth machine learning project I have undertaken yet. I particularly enjoyed trying multiple models and seeing how much customization you are able to perform on the models once you truly grasp them. I did find improving the models difficult however, I felt that to make the model more accurate it was trial and error and I was not familiar enough with the process to know what I needed to do differently.

If I was to go back and improve the project I would attempt more models to see if I was able to improve the accuracy using different models than the neural network and random forest.

## Strategy
The problem at hand is a binary classification problem, understanding this a machine learning model seemed like a good fit. I expected the models to be able to recognize the patterns in the data and the relationships between the features and the targets. 
My process was as follows:
- Data Processing: Before training any model I prepare the data. This includes dealing with missing data, encoding certain fields (like gender), and normalizing the features.
- Model Selection: I decided to start with the model I felt would fit the task best in the Random Forest Classifier. It is excellent at handling both linear and nonlinear data.
- Model Evaluation: After training the model I use multiple tools to evaluate performance (Confusion matrix, accuracy, precision, and recall). This helped provide additional information on my model.
- Model Improvement: After viewing the results for my initial Random Forest Classifier I thought it best to try a more complex model. I decided on using a neural network model. I chose this for the ability to solve complex problems and customization.
- Model Visualization: I visualized the models outcomes and performance. This allowed a better understanding and helped with identifying important features.

## Expected and Alternative Solutions
My expected solution and goal was to create a model that accurately predicts whether the amount spent is going to be over $10. For alternative solutions there are other machine learning models that could be useful such as Support Vector Machines, Gradient Boosting, or deep learning models. Additional feature engineering could also be used for alternative solutions.

## Libraries required
Before running the script you must have the following libraries installed
- pandas
- numpy
- math
- json
- matplotlib
- sklearn
- seaborn
- tensorflow

## Project and file structure
The structure for this project is relativly simple. There is one jupyter notebook titled Starbucks_Capstone_notebook.ipynb that contains all the code for the project.
There is also a data folder that contains 3 .json files
- portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
- profile.json - demographic data for each customer
- transcript.json - records for transactions, offers received, offers viewed, and offers completed

## Acknowledgements 
I would like to thanks Udacity and Starbucks for providing this data and the project. It has been incredibly useful in my machine learning growth.

I would also like to acknowledge this [stack overflow post](https://stackoverflow.com/questions/60106364/syntaxerror-invalid-syntax-when-using-lambda-function-in-pandas-apply) which assisted in splitting values.

