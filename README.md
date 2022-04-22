# Introduction
This project explores various classification methods and tries to find the best model for classifying a group of products. The dataset used is from the Otto
Group Product Classification Challenge on Kaggle. Some of the models that will be explored are decision trees, neural network, gradient boosting model. All
these models will then be bench marked against an ElasticNet classifier (Zou and Hastie, 2005). The best model will be selected by cross validation and
comparing the prediction accuracy of the models. The ultimate goal is to get a better understanding of the various models in order and apply to a work (real
world) scenario (classifying customer preferences for window coverings).

# Dataset description
The Otto Group is one of the world’s biggest e-commerce companies, with subsidiaries in more than 20 countries, including Crate & Barrel (USA), Otto.de
(Germany) and 3 Suisses (France). They sell millions of products worldwide every day, with several thousand products being added to their product line.
A consistent analysis of the performance of our products is crucial. However, due to our diverse global infrastructure, many identical products get classified differently. Therefore, the quality of our product analysis depends heavily on the ability to accurately cluster similar products. The better the classification, the more insights we can generate about our product range. The dataset contains over than 200,000 products with 93 features and the
objective is to build a predictive model which is able to distinguish between our main product categories.

# Scientific Research questions & Data mining and statistical methods
The project aims to answer the following questions,
- Compare the accuracy of the different models. Does a particular model perform better than other models? 
- The models that will be built are
   – Logistic Regression
   – Naive Bayes
   – LDA
   – QDA
   – KNN
   – SVM
   – Random Forest
   – Elasticnet
- How does each model compare against the benchmark Elasticnet classifier?
- Is there a category (or categories) that are similar enough that all models struggle to classify accurately? Is so, why and how to address it?
- It is better to dimensionally reduce data to its n principal components or is it better to use the n most important features (Permutation Feature
Importance - PFI) (Altmann et al., 2010)?

# References
H. Zou and T. Hastie, “Regularization and variable selection via the elastic net,” Journal of the royal statistical society: series B (statistical methodology), vol. 67, no. 2, pp. 301–320, 2005.  
  
A. Altmann, L. Tolo¸si, O. Sander, and T. Lengauer, “Permutation importance: a corrected feature importance measure,” Bioinformatics, vol. 26, no. 10, pp. 1340–1347, 04 2010. [Online]. Available: https://doi.org/10.1093/bioinformatics/btq134 
  
C. Molnar, G. K¨onig, B. Bischl, and G. Casalicchio, “Model-agnostic feature importance and effects with dependent features–a conditional subgroup approach,”
arXiv preprint arXiv:2006.04628, 2020.
  
G. K¨onig, C. Molnar, B. Bischl, and M. Grosse-Wentrup, “Relative feature importance,” in 2020 25th International Conference on Pattern Recognition
(ICPR), 2021, pp. 9318–9325.
