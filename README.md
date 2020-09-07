<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/6wj0hh6.jpg" alt="Project logo"></a>
</p>

<h3 align="center">Bank Marketing Data Mining</h3>

<div align="center">

</div>

---

<p align="center"> This project applied different data mining classification techniques to build a model to predict whether the customer will subscribe
bank long-term deposit. A Portuguese retail bank was collected customer data from 2008 through 2013 based on telephone communication.
    <br> 
</p>

## 📝 Table of Contents
- [About](#about)
- [Data Understanding and Exploring](#data_understanding_and_exploring)
- [Data Preparation](#data-preparation)
- [Data Modeling](#data-modeling)
- [Model Evaluation and Conclusion](#model-evaluation-and-conclusion)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>
This project aims to build a suitable model to recommend the best model because it can help the bank filter clients and use available resources more efficiently to achieve their goal. 

The objective of this data analysis project is to demonstrate how the classification and predictive analytics study can be applied to produce real, tangible improvements in a company’s business performance. 

## 🎈 Data Understanding and Exploring <a name="data_understanding_and_exploring"></a>

![alt text](https://github.com/cghimire/Bank-Marketing-Data-Mining/blob/master/Figures/Correlation_3.png "Correlation Plot")

*This plot demonstrates the correlation between different variables. There is no strong relation between predictors and predicted variable y, however, there is some relationship between predictor variable duration and predicted output y*.
![alt text](https://raw.githubusercontent.com/cghimire/Bank-Marketing-Data-Mining/master/Figures/Job_barplot.png "Job bar plot")

*This plot shows the number of clients Vs job category. The highest number of clients are from the job category "admin" followed by blue-color category. Similarly,
there are less students involved in the telemarketing campaign*.

## ⛏️ Data Preparation <a name = "data-preparation"></a>

![alt text](https://github.com/cghimire/Bank-Marketing-Data-Mining/blob/master/Figures/RemoveOutlier_%20campaignVariable.png "Outlier before and after")

*This figure compares the two different plots with outliers and without outliers*.

## 🚀 Data Modeling <a name = "data-modeling"></a>

In order to model the data, I am performing three data-mining classification techniques: 1) Logistic Regression 2)Decision Tree Model 3) Random Forest Model.

![alt text](https://github.com/cghimire/Bank-Marketing-Data-Mining/blob/master/Figures/Decision%20Tree_final.png "Decision Tree")


*This figure represents the decision tree structure. For example, If number of employed is greater than 5088, then that client belongs to NO category with 94% of probability: that means the client is more likely to say NO*.

## Model Evaluation and Conclusion <a name = "model-evaluation-and-conclusion"></a>

![alt text](https://github.com/cghimire/Bank-Marketing-Data-Mining/blob/master/Figures/AccuracyVsTreeSize.png "Accuracy Vs Treesize")

*This figure shows Effect of increasing tree count on accuracy in Random Forest Model*.

I performed three different classification models to classify whether a customer would open a bank account or not. Based on the model build for this project, Decision Tree and Random Forest model are more accurate to predict the output. The Random Forest model is a recommended model for this classification problem.

Since I have been using different data mining techniques, I am expecting the proposed classification models are powerful to predict the output. However, the proposed methods has some limitations. It is not feasible to study all the variables in detail, which might be interesting to predict the output, because of time limitation.

## 🎉 Acknowledgements <a name = "acknowledgement"></a>
I would like to thank some special peoples who helped me a lot on this project.My terrific professor, Dr. Xinlian Liu, encouraged me to start this
project. His ideas and suggestions are always valuable for me not only for this project but also for my further career in data science. Finally, I am very thankful to my entire CS 522- Data Mining class for their feedback and encouragement.
