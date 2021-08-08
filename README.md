<h2>Framing of the Problem</h2>
Purpose is to explore the data, develop models that learn the data (batch, supervised & classification) and test them in predicting water sample's potability from chemical or physical attributes of it. There is no focus such as finding greatest score for some measure, various algorithms are implemented and tested.

<h2>The Data</h2>
Data is available <a href='https://www.kaggle.com/adityakadiwal/water-potability'>here</a>. All data is numerical, containing missing values. It has 9 columns of features and 1 column of label. It is a .csv file (513 KB), transformed into a pandas.DataFrame of shape (3276,10) right at the beginning. Data is splitted (80/20) and smaller piece is reserved as test set to use in final evaluations of models.

<h2>Tools</h2>
Python libraries used: pandas, numpy, matplotlib, seaborn, sklearn, scipy. Project has been developed with Jupyter Notebook, saved in file named water_potability.ipynb.
