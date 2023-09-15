# Decision-Tree-Classifier

A Decision Tree Classifier is a popular machine learning algorithm used for both classification and regression tasks. It belongs to the family of supervised learning algorithms and is primarily used for making decisions based on input features. Decision trees are a versatile and interpretable approach to machine learning, making them valuable in various domains, including finance, healthcare, and marketing.

Decision trees are versatile, interpretable, and can handle both numerical and categorical data. However, they can be prone to overfitting if not properly pruned or regularized. Techniques like ensemble learning (e.g., random forests, gradient boosting) can be used to improve the performance and robustness of decision tree classifiers.

## Implementation

- Importing the required Libraries and reading the dataset
- Performing EDA (Exploratory Data Analysis) on the data
- Encoding the Categorical Variables
- Normalization of the data
- Splitting the data into the Train and the Test data
- Building the Model
  -  Decision Tree Classifier model using Entropy Criteria (C5.0)
  -  Decision Tree Classifier model using Gini Criteria (CART)
- Conclusion

## Packages Used

- pandas
- numpy
- seaborn 
- matplotlib.pyplot
- warnings
- from sklearn import preprocessing
- from sklearn.model_selection import train_test_split
- from sklearn import tree
- from sklearn.tree import DecisionTreeClassifier
