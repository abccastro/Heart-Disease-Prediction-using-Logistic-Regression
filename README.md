# Heart Disease Prediction

This program has used logistic regression algorithm with cross-validation to develop and train the model that could estimate the likelihood of heart disease based on important indicators associated with the condition. The model was then evaluated for its accuracy, precision, recall and auc scores. 

- Sex (Male or Female)
- Age Category
- Imputed race/ethnicity value (American Indian/Alaskan Native, Asian, Black, Hispanic, White and Other)
- Body Mass Index (BMI)
- Smoker (at least 100 cigarettes in his entire life)
- Heavy drinker
  - For adult men: having more than 14 drinks per week
  - For adult women: having more than 7 drinks per week
- Have/had a stroke
- Have/had a diabetes
- Have/had an asthma
- Have/had a skin cancer
- Have/had a kidney disease (excluding kidney stones, bladder infection or incontinence)
- Difficulty walking or climbing stairs
- Physical health (number of days during the past 30 days)
- Mental health (number of days during the past 30 days)
- Doing physical activity or exercise during the past 30 days other than the regular job
- Hours of sleep (on average)
- General health condition (Poor, Fair, Good, Very Good or Excellent)

The dataset were obtained from the website https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease. We created synthetic samples as well to balance the data distribution among the predictor class.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the following Python packages.
```bash
pip install numpy
pip install pandas
pip install matplotlib
pip install seaborn
pip install sklearn
pip install imblearn
pip install pylab
```

## Program Execution
Launch the Jupyter Notebook
```bash
Heart Disease Prediction.ipynb
```

## Group 7 Members
- Auradee Castro
- Miraj Sinya
- Amrita Gyawali
- Yajur Sethi
- Sharon Victor
