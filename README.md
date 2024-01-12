# Integrated Bioinformatics Approach for Accelerated Drug Design and QSAR Modeling of Acetyl-CoA Carboxylase


Bioinformatics Project: ACC Compound Optimization
This comprehensive bioinformatics project focuses on accelerating drug design for Acetyl-CoA carboxylase (ACC) compounds. The project begins with meticulous data acquisition and cleaning, ensuring the quality and readiness of ACC data for drug development purposes.

Next various machine learning regression models were implemented using the Lazypredict library, comparing and selecting the most effective algorithms for predicting the bioactivity (pIC50) of ACC molecules based on their molecular fingerprints.

The project's centerpiece involves the development of a robust Quantitative Structure-Activity Relationship (QSAR) model using Random Forest Regression. This model achieves an impressive R-value of 0.86, demonstrating its efficacy in predicting pIC50 values and subsequently accelerating drug design and optimization for ACC compounds.

To aid in the interpretation of model performance, data visualization techniques, including bar plots for R-squared values, RMSE values, and calculation time, were employed. The model's accuracy was further assessed through metrics such as mean squared error (MSE) and coefficient of determination (R^2). The experimental vs predicted pIC50 values for training data were plotted, providing a visual representation of the model's predictive capabilities.

To facilitate future use or deployment, the trained Random Forest Regression model was saved as a Pickle object. 






