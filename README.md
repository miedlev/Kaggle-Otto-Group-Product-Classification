### Kaggle Competition | [Otto Group Product Classification Challenge](https://www.kaggle.com/c/otto-group-product-classification-challenge/data)


#### 1. My Conclusion Analysis Report - Jupyter Notebook
* [Otto-Group-Product Analysis](https://github.com/miedlev/Kaggle-Otto-Group-Product-Classification/blob/master/Otto%20Group%20Product%20Classification.ipynb)


#### 2. About Data :
* Each row corresponds to a single product. There are a total of 93 numerical features, which represent counts of different events. All features have been obfuscated and will not be defined any further.
* There are nine categories for all products. Each target category represents one of our most important product categories (like fashion, electronics, etc.). The products for the training and testing sets are selected randomly.

#### 3. Process Introduction :
It is a competition that can be said to be Kaggle's introductory period and conducts a Python-based analysis. My focusins was on 
1. Correlation coefficient Analysis 
2. Feature engineering
3. Hold-out Validation strategy
4. Ensemble Model Selection(RandomForestClassifier vs LGBMClassifier)
5. log_loss metrics / gbdt type
6. hyperparameter Tuning 


#### 4. Dependencies & Tech :
* [IPython](http://ipython.org/)
* [NumPy](http://www.numpy.org/)
* [Pandas](http://pandas.pydata.org/)
* [SciKit-Learn](http://scikit-learn.org/stable/)
* [SciPy](http://www.scipy.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [Matplotlib](http://matplotlib.org/)
* [StatsModels](http://statsmodels.sourceforge.net/)
* [LightGBM](https://lightgbm.readthedocs.io/en/latest/)


#### 5. Otto Group Product Classification Challenge
The Otto Group is one of the world’s biggest e-commerce companies, with subsidiaries in more than 20 countries, including Crate & Barrel (USA), Otto.de (Germany) and 3 Suisses (France). 
We are selling millions of products worldwide every day, with several thousand products being added to our product line.

A consistent analysis of the performance of our products is crucial. However, due to our diverse global infrastructure, many identical products get classified differently. Therefore, the quality of our product analysis depends heavily on the ability to accurately cluster similar products. 
The better the classification, the more insights we can generate about our product range.
