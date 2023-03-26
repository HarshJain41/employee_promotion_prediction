# Employee Promotion Prediction
The objective of this project is to develop a predictive model that can accurately identify the employees who are most likely to be promoted. This will help the client to save time and resources by selecting only the most promising candidates for training and evaluation.

## About Dataset:
### Content
A large MNC have 9 broad verticals across the organisation. One of the problem is identifying the right people for promotion (only for manager position and below) and prepare them in time.

The final promotions are only announced after the evaluation and this leads to delay in transition to new roles. Hence, company needs help in identifying the eligible candidates at a particular checkpoint so that they can expedite the entire promotion cycle.

Multiple attributes have been provided around Employee's past and current performance along with demographics.

### Features:

- employee_id: Unique ID for employee
- department: Department of employee
- region: Region of employment (unordered)
- education: Education Level
- gender: Gender of Employee
- recruitment_channel: Channel of recruitment for employee
- no_ of_ trainings: no of other trainings completed in previous year on soft skills, technical skills etc.
- age: Age of Employee
- previous_ year_ rating: Employee Rating for the previous year
- length_ of_ service: Length of service in years
- awards_ won?: if awards won during previous year then 1 else 0
- avg_ training_ score: Average score in current training evaluations
- is_promoted: (Target) Recommended for promotion

## Methodology
The project involved the following steps:

Data collection and preprocessing: We collected data from online source, and performed indepth EDA.

Null Values: Handled Null Values

Feature engineering: We created new features based on employee demographics, performance metrics, and training history.

Class Imbalance: Handled Class Imbalance using SMOTE

Model selection: We experimented with several machine learning models, including logistic regression, K nearest neighbors, and random forests, to identify the best model for the task. We Finally chose our random forest classifier model.

Model training and evaluation: We trained the selected model on the training data and evaluated its performance on the validation data using metrics such as accuracy, precision, recall, and F1 score.

Model deployment: Work in Progress

## Results
The final model achieved an accuracy of 95% on the validation data, which is a significant improvement over the client's current process. The model was able to identify the most important factors that contribute to promotion likelihood, such as employee age, awards won, previous training performance, and years of service etc..

## Conclusion
This project demonstrates the effectiveness of machine learning in solving real-world HR challenges such as employee promotion prediction. The model developed can help the client to save time and resources by selecting only the most deserving candidates for training and evaluation, ultimately leading to better employee satisfaction and retention.
