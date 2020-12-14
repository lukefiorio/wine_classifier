# Wine Color Classification
### Neural Network binary classification

This project uses data from the UCI Machine Learning Repository on wine quality to predict wine class (red, white).  This dataset is originally pitched as a quality prediction task (wine rating between 0 and 10), but we approach it as a binary wine color classification task in this project. The data can be found and downloaded here: 
- white wines: https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-white.csv
-   red wines: https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.csv

For this project, we download directly from a link made available through University of Washington (https://library.startlearninglabs.uw.edu/DATASCI420/2019/Datasets/RedWhiteWine.csv).

The dataset that we use to build and test our model contains several features on wine characteristics, including the wine color, of 6,500 wine samples.  Wine color (red, white) is our target variable, which we build and test several neural network models to predict.

Our data set is not balanced (1,599 red wines; 4,898 white wines), however since neural networks do not inherently suffer from class imbalance, they are a reasonable model choice for this project.
