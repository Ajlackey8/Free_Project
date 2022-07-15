# Free_Project
## Analysis of Health Information and it's use in diagnosing and predicting Heart Disease for the Health Industry.
Author: Andrew Lackey
### Accurate predictions of Heart Disease:
Heart disease is the number one killer of Americans, accounting for 21% of all deaths in 2020. The ability to accurately predict and intervene with preventative measures is a valuable tool in helping hospitals and insurance companies reduce the number of people suffering and dying from these issues.
### Data:
[The data is from kaggle)](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
 and has 11 different features describing health related metrics such as age, maximum heart rate, blood pressure, etc. As well as whether or not the patient developed heart disease.

## Methods
* Data processed to impute or remove erroneous data or missing records.
* Data trends explored by creating correlations and visualizations of those correlations.
* KNearest Neighbor, Logistic Regression, and Neural Networking applied to the (split for training/testing) data set to create predictive models for predicting Heart Disease.
* Best model evaluated and selected.

## Results
### Visualizations of identified trends as well as data peculiarities

Correlation between price and sales
![scatter](https://user-images.githubusercontent.com/25378587/179225335-e8416fc2-0d2b-40e1-a89f-9bf4e41ed741.png)


The nearly uniform distribution of weight amongst types.
![image](https://user-images.githubusercontent.com/25378587/172199944-4c03469e-c865-4c41-9b98-48b6c35a9a86.png)

## Model
The most accurate predictive model used was a Neural Network which was able to correctly determine if a patient did/did not have heart disease with 88% precision. Resulting in 203 correct predictions out of 230.

## Recommendations:
Further tuning the neural network to bias the results in favor of positive results. False negatives could have unwanted consequences for both patient and healthcare provider so having the model require more confidence to assign a negative would create less accurate results, but create more conservative results that avoid false negatives.

### For further information
For any additional questions, please contact ajlackey8@gmail.com

![image](https://user-images.githubusercontent.com/25378587/172199927-710442e4-b103-42e5-9cef-37e5a1cbe7db.png)
