# Describe fundamental principles of machine learning on Azure

Costa Rica

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[brown9804](https://github.com/brown9804)

Last updated: 2025-01-16

----------


<details>
<summary><b>List of References </b> (Click to expand)</summary>

- [What is a confusion matrix?](https://www.nomidl.com/machine-learning/what-is-a-confusion-matrix/)
  
</details>



## Q: Identifying Anomaly Detection Examples

> Determine whether each of the following scenarios is an example of anomaly detection.

**Statements:**

1. Predicting stock prices based on historical data.
   - [ ] Yes
   - [x] No `This is incorrect because predicting stock prices is a regression problem, not anomaly detection.`
2. Classifying emails as spam or not spam based on their content.
   - [ ] Yes
   - [x] No `This is incorrect because classifying emails is a classification problem, not anomaly detection.`
3. Detecting fraudulent transactions by identifying unusual spending patterns.
   - [x] Yes `This is correct because detecting fraudulent transactions involves identifying deviations from normal behavior, which is an example of anomaly detection.`
   - [ ] No

## Q: Ensuring Transparency in Automated Machine Learning

> When developing a machine learning model through an automated machine learning user interface (UI), what steps should be taken to ensure the model adheres to Microsoft's transparency principle for responsible AI?

**Options:**
- [ ] A. Set Validation type to Auto. `This is incorrect because setting the validation type to auto does not directly address the transparency principle.`
- [ ] B. Set Primary metric to accuracy. `This is incorrect because setting the primary metric to accuracy focuses on performance, not transparency.`
- [ ] C. Set Max concurrent iterations to 0. `This is incorrect because setting the maximum concurrent iterations to 0 does not relate to transparency and would likely hinder the model training process.`
- [x] D. Enable Explain best model. `This is the correct answer. Enabling the "Explain best model" feature provides insights into how the model makes decisions, which aligns with the transparency principle by making the model's workings understandable.`

## Q: Understanding Confusion Matrix Metrics

> You are working on developing a classification model to predict outcomes. The confusion matrix for the model, evaluated on test data, is provided below:

|       | Actual Negative | Actual Positive |
|-------|-----------------|-----------------|
| Predicted Negative | 950             | 20              |
| Predicted Positive | 30              | 14000           |

Select the answer choice that completes each statement based on the information presented in the confusion matrix. 

**Options:**

1. There are [answer choice] correctly predicted positives.
    - [ ] 20 `This is incorrect because 20 represents the false negatives.`
    - [ ] 30 `This is incorrect because 30 represents the false positives.`
    - [ ] 950 `This is incorrect because 950 represents the true negatives.`
    - [x] 14000 `This is the correct answer. 14000 represents the true positives, which are the correctly predicted positive cases.`
        
2. There are [answer choice] false negatives.
    - [ ] 30 `This is incorrect because 30 represents the false positives.`
    - [ ] 950 `This is incorrect because 950 represents the true negatives.`
    - [ ] 14000  `This is incorrect because 14000 represents the true positives.`
    - [x] 20 `This is the correct answer. 20 represents the false negatives, which are the actual positive cases incorrectly predicted as negative.`

From [What is a confusion matrix?](https://www.nomidl.com/machine-learning/what-is-a-confusion-matrix/)

<div align="center">
  <img src="https://github.com/user-attachments/assets/037a8dcb-9c68-49ba-b070-e95fc5dea743" alt="Centered Image" style="border: 2px solid #4CAF50; border-radius: 5px; padding: 5px; width: 500px;"/>
</div>

## Q: Splitting Data for Machine Learning

> In a machine learning process, how should you split your data for training and evaluation to ensure effective model development?

**Options:**
- [ ] A. Use features for training and labels for evaluation. `This is incorrect because features are the input data used for training the model, while labels are the output data used for evaluation.`
- [ ] C. Use labels for training and features for evaluation. `This is incorrect because labels are the target outputs that the model aims to predict, and features are the inputs used to train the model.`
- [ ] B. Randomly split the data into columns for training and columns for evaluation. `This is incorrect because splitting data by columns would separate features from labels, making it impossible to train the model effectively.`
- [x] D. Randomly split the data into rows for training and rows for evaluation. `This is the correct answer. Randomly splitting the data into rows ensures that both the training and evaluation sets are representative of the overall dataset, leading to more reliable model performance.`


<div align="center">
  <h3 style="color: #4CAF50;">Total Visitors</h3>
  <img src="https://profile-counter.glitch.me/brown9804/count.svg" alt="Visitor Count" style="border: 2px solid #4CAF50; border-radius: 5px; padding: 5px;"/>
</div>
