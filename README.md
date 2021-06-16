# Machine-Learning-Practices

First use Data_cleaned.ipynb to clean the dataset of "The US Presidential Elections", including find and remove bad data, split, aggregate, rename, normalize, summarize and visualize dataset.

ID3_Decision_Tree.ipynb implement ID3 decision tree to predict Democrats using some other categorical features as data ('State','Education','Religion','EthnicMale','EthnicFemale') from the cleaned dataset.

First part of Cross_Regression.ipynb implement ID3 decision tree to predict PovertyLevel using both continuous features('PerCapitaIncome') and existing categorical features('State','Education','Religion','EthnicMale','EthnicFemale')  from the cleaned dataset. Second part of Cross_Regression.ipynb implement 5-fold crossvalidation
to select the best regression tree.

Random_Forest.ipynb implement a random forest on 50 pre-pruned decision trees of depth 3 to predict Democrats using some other categorical features as data ('State','Education','Religion','EthnicMale','EthnicFemale') from the cleaned dataset. 
