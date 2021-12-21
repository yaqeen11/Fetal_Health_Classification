# Fetal health 
<p align="center" width="100%">
<img src="https://miro.medium.com/max/800/1*rmj7B0EumeMHL4SiW6tD5Q.gif" />
</p>

## Introduction:
Classify fetal health in order to prevent child and maternal mortality.
The goal of this statistical analysis is to help us  use the Cardiotocography (CTG) is during pregnancy to monitor fetal heart rate and uterine contractions.
It is monitor fetal well-being and allows early detection of fetal distress.
In this project, I will create a model to classify the outcome of Cardiotocogram test to ensure the well being of the fetus.


## Business Problem:
We help company that provides health insurance for pregnant women in order to maintain the health of their pregnancy in order to make the pregnancy stage healthy and free from risks and preserve the mother and her fetus for the success of the pregnancy stage.

## Data Description:
  ### source:
  The data was obtained from the kaggle website: https://www.kaggle.com/andrewmvd/fetal-health-classification
  This data has 2126 rows, 22 columns.


    
  ### Features:
  - baseline value: Baseline Fetal Heart Rate (FHR).
  - accelerations:Number of accelerations per second.
  - fetal_movement: Number of fetal movements per second.
  - uterine_contractions:Number of uterine contractions per second.
  - light_decelerations:Number of LDs per second.
  - severe_decelerations:Number of SDs per second.
  - prolongued_decelerations:Number of PDs per second.
  - abnormal_short_term_variability:Percentage of time with abnormal short term variability.
  - mean_value_of_short_term_variability:Mean value of short term variability.
  - percentage_of_time_with_abnormal_long_term_variability:Percentage of time with abnormal long term variability.
  - histogram_min:Histogram minimum value.
  - histogram_max:Histogram maximum value.
  - histogram_number_of_peaks:Number of peaks in the exam histogram.
  - histogram_number_of_zeroes:Number of zeroes in the exam histogram.
  - histogram_mode:Hist mode.
  - histogram_mean:Hist mean.
  - histogram_median:Hist Median.
  - histogram_variance:Hist variance.
  - histogram_tendency:Histogram trend.
  - fetal_health:Fetal health: 1 - Normal 2 - Pathological.





## Classification Algorithms:
  - Decision Tree
  - Logistic regression.
  - Random forest.
  - Knn.
  - SVM.
  - Extreme Gradient Boost.
  - Naive Bayes.


## Tools:
  - Jupyter (Python: numpy, pandas, matplotlib, seaborn, plotly, sklearn)
  - Power Point Trello Github
  - Zoom


## Questions:
  - what is majority class of fetal health?
  - What is the relationship between Baseline Fetal Heart Rate and uterine contractions for Pathological fetal?
  - Can uterine contractions and fetal movement express the fetal heath spacially Pathological type of fetal?
  - Can Fetal heart rate monitoring of short-term variation (STV) has a relationship with fetal health in terms of baseline value?
  - What is the relationship between severe decelerations and uterine contractions in each type of fetal health?
  - Does mean value of short term variability has a relationship with fetal health type in term of uterine contractions?


## MVP Goal:
The MVP goal is to answer at least two of the questions I mentioned.

---
## The team:
  [@Eman](https://github.com/Eeeemsa) ,  [@Yaqeen](https://github.com/yaqeen11) .
