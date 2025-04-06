# 🍷 Wine Quality Analysis 

Wine is intriguing because of the complexity and layers of its flavour. This project tries to go deeper and understand the attributes and the basic factors that determine the quality of white wine and make it taste a certain way.

The Wine Quality Dataset has been taken from UCI Machine Learning Repository for white wine analyses.

This project aims to:

1. Determine factors that significantly affect the quality of white wine,
2. Interpret the effects of such factors on the quality of white wine,
3. Use the determined factors to predict the quality of white wines,



## ⚙️ Methodology

Skills & Concepts Used:

Python    |    Statistics    |   Logistic Regression

I used Python to analyze this dataset, and Jupyter Notebook as my environment. The libraries I used were `pandas`, `numpy`, `matplotlib`, `statistics`, `scipy` and `sklearn`.


## 📊 Results

I found that the 3 most significant physicochemical variables that affect the quality of white wine are **volatile acidity**, **sulphates**, and **alcohol content**.
If density, fixed acidity or volatile acidity is increased, the wine quality score is predicted to decrease. On the other hand, when residual sugar, chlorides, total sulfur dioxide, pH, sulphates, or alcohol content is increased, the wine quality improves.

The model built was found to predict the quality of white wine fairly well, with an **error rate** of roughly 28%. The model was also tested on a red wine dataset, and predicted the quality with an error rate of 24%.

## 📜 License
This project is **copyrighted** and may **not** be used, copied, modified, or distributed.  
It is an academic project submitted for university coursework.  
Any unauthorized use, including plagiarism, will be considered a violation of academic integrity policies.  
