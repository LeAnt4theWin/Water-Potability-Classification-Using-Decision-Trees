# Water-Potability-Classification-Using-Decision-Trees
In this project, I'll be using the water potability dataset (from kaggle) to predict water potability based on several physicochemical features. The goal is to classify water samples into two categories: potable (safe to drink) and not potable. Ill be using a Decision Tree Classifier and the KNN Classifier.
Water Potability Classification Using Decision Trees vs KNN

# Introduction

In this project, Ill be using the water potability dataset (from kaggle) to predict water potability based on several physicochemical features. The goal is to classify water samples into two categories: potable (safe to drink) and not potable. Ill be using a Decision Tree Classifier and the KNN Classifier. This is addressing SDG # 6 which is access to clean drinking water.

# Results

The model is more likely to classify a sample as non-potable, possibly indicating a bias or maybe some misclassfication in the model.

The relatively high number of false negatives suggests the model might benefit from being more sensitive to the potable class. Depending on the situation, this might be a significant issue, as failing to identify potable water could have serious costs.

A potential area for improvement would be to reduce the number of false negatives, perhaps by adjusting the decision threshold or collecting more representative training data for the potable class.

# Real World Application

With better accuracy for deteching good water samples, this model can be ran on a small cpu with a mounted sensor attached to a reuseable water containter. If the sensor senses that the water inside isnt good, then it can alert the user before drinking.

