# Bangalore_house_prediction

A machine learning project focused on cleaning real-world real estate data and building baseline regression models to estimate house prices in Bengaluru.

Brief:

Real estate data is often inconsistent and full of text variations. In this notebook, I worked through raw housing listings to clean up messy inputs, engineer practical features, and test how different linear regression models perform.### Key Steps:

->Handling Area Ranges: EDA.
->Feature Extraction: Cleaned room sizes to numerical bedroom counts and split availability dates into year/month features.
->Handling Location Cardinality: Grouped locations with 10 or fewer listings into an `Other` category to keep one-hot encoding manageable.
->Scaling: Scaled feature inputs using on the training split.



## Upcoming Improvements:

* Implement domain-specific outlier filtering (e.g., minimum square footage per bedroom, price-per-square-foot limits).
* Test a log transformation on the target `price` variable to address right-skewness.
* Re-run polynomial features only on continuous numerical columns.
* Explore tree-based models (Random Forest, Gradient Boosting).
* Build a lightweight web interface and deploy the trained model live.
