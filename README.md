# ConcreteCompressiveStrength

In this project, I'll look at the <i>Concrete Compressive Strength Data Set</i> from the UCI repository.

This data set was uploaded by Prof. I-Cheng Yeh and used mainly in Prof. I-Cheng Yeh's 1998 paper (I-Cheng Yeh, "Modeling of strength of high performance concrete using artificial neural networks," Cement and Concrete Research, Vol. 28, No. 12, pp. 1797-1808 (1998).)

This data set is concerned about predicting concrete compressive strength with 8 different variables (i.e. input features) involved in concrete admixing. 7 of these variables are cement, blast furnace slag, fly ash, water, superplasticizer, coarse aggregate, fine aggregate. The last input feature is the age of concrete.

I'll be analyzing the data set and developing machine learning models to predict concrete compressive strength. Although I load the data directly from the UCI repository online, you can find Prof. I-Cheng Yeh's original data set and original README file with the names <i>Concrete_Data.xls</i> and <i>Concrete_Readme.txt</i> respectively in this repo.

Please find the details of this project below:
* __Language__: Python
* __Primary Libraries__: pandas, scikit-learn, scikit-optimize, matplotlib.pyplot, seaborn
* __Apps & Tools__: Google Colab / Jupyter Notebook
* __Machine Learning models__: Linear Regression, K-Nearest Neighbors (KNN) with & without GridSearchCV, Random Forest with & without GirdSearchCV, XGBoost with & without BayesSearchCV (i.e. Bayesian Optimization)
