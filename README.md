# pytanic
Data Visualization using Python

*RMS Titanic, known for its infamous shipwreck in the North Atlantic Ocean on 15 April 1912. Among the deadliest tragediest of all time, killing more than 1500 poeple of the estimated 2224 passengers and crew. The disaster drew much public attention, which not only led to better safety guidelines for ships but also provided foundational material for the disaster film genre.*

The dataset contains the details of only 891 passengers.

## Project Components
1. Data Inspection
2. Data Cleaning
3. Data Visualization
4. FAQs related to the DataSet 

## Overview of the Dataset
Given table contains the details of the columns along with their parameters, which is crucial for the understanding of the data analyst working with the dataset.

| Variable| Attributes / Definition | Meaning if any |
|-|-|-|
| Survival| 0<br>1 | No<br>Yes |
| pclass | 1<br>2<br>3 | Class A<br>Class B<br>Class C<br> |
| Sex | F<br>M | Female<br>Male |
| Age | Age in years| |
| sisbsp | Sibling<br>Spouse  | brother, sister, stepbrother, stepsister<br>husband, wife (mistresses and fiancés were ignored) |
| parch | Parent<br>Child  | mother, father<br>daughter, son, stepdaughter, stepson |
| ticket | ticket number |
| fare | passenger fare |
| cabin | cabin number |
| embarked | **Port of Embarkation**<br>C<br>Q<br>S | <br>Cherbourg<br>Queenstown<br>Southampton |

#### NOTE
In other projects you would notice that the analyst has two .csv files namely, `train.csv` and `test.csv`.<br>
  
`test.csv` file $=>$ used for **testing the model** generated.   
`train.csv` file $=>$ used for **training the model with the dataset** we work on. 
<br>  
The conclusive values and end results made by models also varies with the percentage of dataset alloted for each of the two .csv files.     
Which means that we may have different results when the data alloted for train.csv and test.csv is 50-50 as opposed to a case where it is 70-30 
<br><br>
Whereas in my project there is only one csv file, because I have decided not to divide my dataset in any manner and work with the dataset in it's entirity. 

## Conclusion
These the following conclusion we can make after analysing the following data.

<details>
<summary>Links to all the resources from where I learnt the following</summary>
1. https://medium.com/analytics-vidhya/data-visualization-titanic-data-set-91531c3ab5a6<br>
2. https://medium.com/@rohanhgupta91/analyze-titanic-dataset-of-kaggle-ab220334b75c<br>
3. https://medium.com/analytics-vidhya/what-is-the-difference-between-training-and-test-dataset-d20820e5f632<br>
4. https://towardsdatascience.com/machine-learning-with-the-titanic-dataset-7f6909e58280<br>
5. https://www.kaggle.com/subinium/awesome-visualization-with-titanic-dataset<br>
6. https://www.kaggle.com/startupsci/titanic-data-science-solutions/<br>
7. https://github.com/abhishekchhibber/Titanic-Data-Visualization<br>
8. https://mastermindlab.github.io/titanic/<br>
9. https://harvard-iacs.github.io/2019-CS109A/labs/lab-5/student/<br>
</details>