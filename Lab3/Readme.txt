

Data file(sparkdata) contains all the collected files.
I have collected data using NYTimes article API.
I have chosen Technology, Sports, Diplomacy and Weather as our classes.
Code file contains titanic data set analysis and classification models for collected data. I have used Random forest,
Logistic regression and Naive Bayes for classification.
Validation set is stored in Valset directory.

The code file contains:
1) Article extraction using NTTimes API and beautifulsoup library in python
2) Article classification in PySpark using MlLib

Sparkdata contains collected articles which has their filenames as their topic

Validation set contains articles which dont have any labels and are used for the classification testing purpose.
