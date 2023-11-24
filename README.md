# houses-lin-reg
EDA and linear regression on California housing dataset

There are 3 notebooks in this project:
- *data-prep* -> exploratory data analysis on dataset from https://www.kaggle.com/datasets/camnugent/california-housing-prices and transforming it for the linear regression model
- *lin_reg_model* -> fitting a linear regression model to the data + visualisations
- *regularization* -> recreating Ridge and Lasso regression visualisations from https://www.youtube.com/watch?v=Xm2C_gTAl8c&list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF&index=27

What I learned:
* scikit-learn library (especially building Pipelines)
* scaling, imputing and one-hot encoding data
* creating new features to avoid colinearity
* finding best model hyperparameters through grid search
* improving the model with regularization and polynomial features
* checking the assumptions of linear regression and interpreting the coefficients

Disclaimer: the notebooks were prepared as homework for an university ML class (taught by Marta Szczęsna)
