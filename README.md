# Spam/Ham Model

The goal of the project was to find features for a logistic regression model that classifies whether an email is spam or not. Content analysis was done on a set of spam and non-spam emails to identify any notable features. Examples of some analysis below:

![Plot 1](images/plot1.png)

![Plot 2](images/plot2.png)

![Plot 3](images/plot3.png)

Examples of features include number of words, punctuation, and whether an email had certain keywords. After applying features, the model was able to correctly label 98.8% of emails, a 23.2% improvement over a logistic model with simple features.

## Tools

Python and Jupyter notebook were used for main analysis, along with several packages such as Pandas, Numpy, Matplotlib, and Seaborn.
