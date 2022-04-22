Introduction
Classification is the process of recognizing, understanding and grouping of objects
and ideas into specific categories or sub-populations. With the help of
these pre-categorized training datasets, classification machine learning programs
leverage a wide range of algorithms to classify future data-sets into respective
and relevant categories. Classification has many real world applications, such as
fraud detection, email spam filtering, customer churn prediction, etc. Specifically,
it is widely used in product classification, where it is the key to uncovering
the reasons behind understanding a consumers’ general buying behaviors and
how to better market a product as a result.
2 Project Description
This project explores various classification methods and tries to find the best
model for classifying a group of products. The dataset used is from the Otto
Group Product Classification Challenge on Kaggle. Some of the models that
will be explored are decision trees, neural network, gradient boosting model. All
these models will then be bench marked against an ElasticNet classifier (Zou
and Hastie, 2005). The best model will be selected by cross validation and
comparing the prediction accuracy of the models. The ultimate goal is to get a
better understanding of the various models in order and apply to a work (real
world) scenario (classifying customer preferences for window coverings).
2.1 Dataset description
Description from Kaggle website
1
The Otto Group is one of the world’s biggest e-commerce companies, with
subsidiaries in more than 20 countries, including Crate & Barrel (USA), Otto.de
(Germany) and 3 Suisses (France). They sell millions of products worldwide
every day, with several thousand products being added to their product line.
A consistent analysis of the performance of our products is crucial. However,
due to our diverse global infrastructure, many identical products get classified
differently. Therefore, the quality of our product analysis depends heavily on
the ability to accurately cluster similar products. The better the classification,
the more insights we can generate about our product range.
The dataset contains over than 200,000 products with 93 features and the
objective is to build a predictive model which is able to distinguish between our
main product categories.
More information about the dataset can be found here - Otto Group Product
Classification Challenge
3 Scientific Research questions & Data mining
and statistical methods
The project aims to answer the following questions,
• Compare the accuracy of the different models. Does a particular model
perform better than other models? The models that will be built are
– Logistic Regression
– Naive Bayes
– LDA
– QDA
– KNN
– SVM
– Random Forest
– Elasticnet
• How does each model compare against the benchmark Elasticnet classifier?
• Is there a category (or categories) that are similar enough that all models
struggle to classify accurately? Is so, why and how to address it?
• It is better to dimensionally reduce data to its n principal components or
is it better to use the n most important features (Permutation Feature
Importance - PFI) (Altmann et al., 2010)?
2
References
H. Zou and T. Hastie, “Regularization and variable selection via the elastic
net,” Journal of the royal statistical society: series B (statistical methodology),
vol. 67, no. 2, pp. 301–320, 2005.
A. Altmann, L. Tolo¸si, O. Sander, and T. Lengauer, “Permutation
importance: a corrected feature importance measure,” Bioinformatics,
vol. 26, no. 10, pp. 1340–1347, 04 2010. [Online]. Available: https:
//doi.org/10.1093/bioinformatics/btq134
C. Molnar, G. K¨onig, B. Bischl, and G. Casalicchio, “Model-agnostic feature
importance and effects with dependent features–a conditional subgroup approach,”
arXiv preprint arXiv:2006.04628, 2020.
G. K¨onig, C. Molnar, B. Bischl, and M. Grosse-Wentrup, “Relative feature
importance,” in 2020 25th International Conference on Pattern Recognition
(ICPR), 2021, pp. 9318–9325.
