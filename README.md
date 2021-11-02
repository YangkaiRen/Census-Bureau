# Machine Learning Analysis on Census-Bureau Dataset.

[Top data link](https://archive.ics.uci.edu/ml/datasets/census+income)

### dictionary

__age__: continuous.    
__workclass__: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.   
__fnlwgt__: continuous.   
__education__: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.   
__education-num__: continuous.    
__marital-status__: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.    
__occupation__: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.   
__relationship__: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.   
__race__: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.    
__sex__: Female, Male.
__capital-gain__: continuous.   
__capital-loss__: continuous.   
__hours-per-week__: continuous.   
__native-country__: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.   
__income__: >50K, <=50K.

### Introduction
This data was extracted from the [Census bureau database](https://archive.ics.uci.edu/ml/datasets/census+income) by Ronny Kohavi and Barry Becker. The prediction task is to determine whether a person makes over $50K a year or not. There are 48842 instances and 14 attributes in the dataset. The data contains a good blend of categorical, numerical and missing values.

```python
---EDA
    |---EDA.ipynd
---code
    |--- main.ipynd
---data
    |--- adult.data
    |--- adult.test
    |--- adult.names
---feature
    |--- feature.ipynd
---model
    |--- model.py
```
