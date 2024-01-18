# TAFE_ML_Algorithms
Final project of 'Machine Learning Algorithms' course provided by Institute of Applied Technology (IAT) in collaboration with TAFE NSW.
In this project, **supervised learning**, **unsupervised learning** and **semi-supervised learning** are used to evaluate the given scenario.

Features:
  - Data visualisation & pre-processing
  - **Random Forest** for supervised learning
  - **K-means Clustring** for unsupervised learning
  - **Label Propagation** for semi-supervised learning
  - Tuning hyperparameters including **GridSearchCV**
  - Evaluation of results with
      - accuracy
      - precision
      - recall
      - F1
      - confusion matrix
      - ROC-AUC score


## Scenario

Your task is to help an organisation perform customer segmentation to better understand their customers’ needs and increase customer loyalty. You will be provided with a customer dataset detailing customer identity, age, gender, income, spending score and buy. The spending score has already been allocated to each customer based on their individual behaviours and purchases. 

The ‘buy’ data is represented in binary: 
- 1 - customer did buy the product
-	0 – customer did not buy the product

The raw data file is located at [/TAFE_ML_Algorithms/dataset.csv](https://github.com/siwoo-jung/TAFE_ML_Algorithms/blob/main/dataset.csv)

## Python code

The python code is located at [/TAFE_ML_Algorithms/code.ipynb](https://github.com/siwoo-jung/TAFE_ML_Algorithms/blob/main/code.ipynb)

## Final report

The final report addressing the whole chapters is located at [/TAFE_ML_Algorithms/final_report.pdf](https://github.com/siwoo-jung/TAFE_ML_Algorithms/blob/main/final_report.pdf)

## Conclusion (brief)

For all models, evaluation metrics, such as accuracy, precision, recall, F1 and ROC-AUC, were applied. Considering the given scenario, precision and recall were comparably more important. As shown in the below figure, random forest model outperformed in all metrics, followed by semi-supervised and unsupervised models. Considering the nature of each algorithm and the problem, supervised learning was expected to perform best in the first place. With the random forest model, the company will effectively distinguish potential loyal customers, and can plan business strategies accordingly.

![image](https://github.com/siwoo-jung/TAFE_ML_Algorithms/assets/142607954/8db0d43e-3954-4150-8c9a-990eaf9b0146)


