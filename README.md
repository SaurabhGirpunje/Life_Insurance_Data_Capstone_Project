## Life_Insurance_Data_Capstone_Project

### Objective

The dataset belongs to a leading life insurance company. The company wants to predict the bonus for its agents so that it may design appropriate engagement activity for their high performing agents and upskill programs for low performing agents.

### Software and Tools Required

1. [Github Account](https://github.com)
2. [VS Code IDE](https://code.visualstudio.com)
3. [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)
4. [Python](https://www.python.org/downloads/)
5. [Jupyter Notebook](https://jupyter.org/)
6. [Pandas](https://pandas.pydata.org/)
7. [Numpy](https://numpy.org/)
8. [Matplotlib](https://matplotlib.org/)
9. [Seaborn](https://seaborn.pydata.org/)
10. [Scikit-learn](https://scikit-learn.org/stable/)

#### Create a new environment
```
conda create -p venv python==3.10 -y
```  

        
        
### Model Output:  

| Model Name                       | Train RMSE | Test RMSE | Train R² | Test R² |
|----------------------------------|------------|-----------|----------|---------|
| Linear Regression Model          | 613.47     | 623.56    | 0.806    | 0.807   |
| Lasso Regression Model           | 613.72     | 623.72    | 0.806    | 0.808   |
| Ridge Regression Model           | 613.47     | 623.57    | 0.807    | 0.808   |
| Elastic Net Regression Model     | 675.72     | 688.87    | 0.765    | 0.764   |
| Decision Tree Regression Model   | 461.93     | 645.18    | 0.890    | 0.794   |
| Random Forest Regression Model   | 252.97     | 562.32    | 0.967    | 0.843   |
| Lasso + AdaBoost Regression Model| 623.63     | 637.61    | 0.800    | 0.799   |
| Lasso + Bagging Regression Model | 613.64     | 623.91    | 0.806    | 0.807   |
| Ridge + AdaBoost Regression Model| 623.95     | 638.12    | 0.800    | 0.799   |
| Ridge + Bagging Regression Model | 613.63     | 623.90    | 0.806    | 0.808   |