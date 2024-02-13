# Data-Mining-1

DATA UNDERSTANDING

 Data Semantics
• Introduce the variables with their meaning and characteristics;
 Distribution of the variables and statistics
• Explore (single, pairs of…) variables quantitatively (e.g., statistics, distributions);
 Assessing data quality
• Are present errors, outliers, missing values, semantic inconsistencies, etc?
 Variable transformations
• Is it better to use for further modules transformed variables (e.g., log-transformated)?
 Pairwise correlations and eventual elimination of variables
• Matrix correlation (analyse high correlated variables);

CLUSTERING

  Analysis by centroid-based methods
• K-Means (mandatory), Bisecting K-Means (optional), X-Means (optional);
• Choice the attributes, identify the best value of k, discuss the clusters.
   Analysis by density-based clustering
• DBSCAN (mandatory), OPTICS (optional);
• Choice the attributes, identify the best parameter configuration, discuss clusters.
  Analysis by hierarchical clustering
• Choice the attributes, the distance function, analyse several dendrograms.
  Final discussion
• Which is the best algorithm? Remember that best is studied w.r.t. several aggregate
statistics, cluster distributions and w.r.t. the typology of algorithm used for that
particular dataset

CLASSIFICATION

  Classification of at least 1 target variable of your choice:
• by Decision Trees;
• by KNN;
• by Naive Bayes.
You should discuss the choice of the attributes and identify the best parameter
configurations (e.g. gain criterion for trees, best k for KNN etc.).
  Discussion
• Evaluate the quantitative performance of the algorithms w.r.t. confusion matrix,
accuracy, precision, recall, F1, ROC curve
• Discuss some insight (e.g. try to interpret the tree(s))
• Which is the best algorithm? Best can be studied w.r.t. the performance evaluation
or other preferred point of view;

PATTERN MINING

  Frequent Pattern extraction
• Using different values of support, etc;
  Discuss Frequent Pattern
• Including qualitative and quantitative analysis, e.g., how the number of patterns w.r.t k
min_sup changes;
  Association Rules extraction
• Using different values of confidence, etc;
  Discuss Association rules
• Including qualitative and quantitative analysis, e.g., how the number of rules w.r.t k
min_conf changes, histograms of rules’ confidence and lift;
  Exploit the most useful extracted rules
• E.g., use them to replace missing values or to predict the target variable;
  Regression: univariate and multivariate regression:
• Choosing 2 or more continous variables and using different regressors (linear, ridge, lasso,
Decision Tree, KNN)
