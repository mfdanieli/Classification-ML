![Banner](imagem.png)

## Predict diabetes according to risk factors

### 1. Project overview
 
- *What is the goal?* 
Predict if a pacient has diabetes.
 
- *How will this question be investigated?* Train and test the KNN model to associate risk factors and diabetes, using the [Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database)

- *Why is this subjetc important?* 

  1. A [recent study](https://diabetesjournals.org/care/article/42/9/1609/36309/Understanding-the-Economic-Costs-of-Diabetes-and) estimate that undiagnosed diabetes can cost **$31.7 billion annually**.

  2. In India, close to **42%** of the people with diabetes in India **are not aware** of their disease status, according to [Claypool  et al. (2020)](https://drc.bmj.com/content/8/1/e000965?utm_content=americas&utm_campaign=usage&utm_medium=cpc&utm_source=trendmd&tid=xRcC2XdbS3AruBxKod5PPqdgMH1tPvz6BDUBfpZxRBxbqeyVrGycvEwy6xcPsIS8dQipAA==)).

  3. Diabetes tests can cost up to $29 in India [Patra, 2021](https://www.breathewellbeing.in/blog/list-of-diabetes-test-blood-glucose-level-normal-values-procedure-cost/). These costs can add up, since these tests often are retaken before a final diagnosis.

- *Hypothesis:* Diabetes can be diagnosed based on risk factors trhough modeling, reducing costs of exams and increasing diabetes identification among the population.

 - *Data Science skills and tools:* data exploration, wrangling, and visualization, machine learning (libraries pandas, numpy, matplotlib, seaborn, and sklearn).


### Solution strategy 
- Import database
- Data wrangling (in order to assure quality and useful data):
    - check missing values and data types 
- Data exploration and visualization (useful to identify which health characteristics have the greatest impact on the development of diabetes):
    - check data distribution, statitical metrics, correlations
    - summarize main characteristics of the data, gain better understanding of relashionships and extract important variables
- Standardize the variables: important to garantee proper scales
- Machine learning model training and testing: KNN model
- Select optimal "k value through the elbow method
- Evaluate model performance and its implications


> One-Line Box made with Blockquote


Apontar no final para o app
