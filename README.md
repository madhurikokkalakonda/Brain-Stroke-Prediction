# Brain Stroke Prediction Study

## Introduction

This study investigates the potential relationship between work status, hypertension, glucose levels, and the incidence of brain strokes. Utilizing a dataset from Kaggle, we aim to identify significant factors that contribute to the likelihood of brain stroke occurrence. Our focus is on understanding how hypertension and average blood glucose levels interact with work type, potentially influencing stroke risk.

## Data Exploration

The dataset consists of information on 4982 patients, encompassing 11 variables such as gender, age, hypertension, heart disease, marital status, work type, residence type, average glucose level, BMI, smoking status, and stroke occurrence. This diverse set of variables allows for a comprehensive analysis of factors affecting stroke incidence.

### Summary Statistics

We began our analysis by examining the skewness of variables related to work status, average glucose levels, hypertension, and BMI. Continuous variables like age, BMI, and glucose levels were assessed for normality through histograms and Q-Q plots, while categorical variables were visualized using bar plots.

## Methods

Our methodology included data visualization techniques like histograms, bar charts, box plots, and Q-Q plots to explore the relationships between the variables and stroke occurrence. We used stratified random sampling to minimize the effects of confounding variables and employed statistical tests such as the Chi-square and Spearman’s correlation to analyze the data.

### Logistic Regression Analysis

We conducted simple and multiple logistic regression analyses to predict stroke occurrence. The analyses considered age groups, work type, and blood glucose levels, with a special focus on the interaction between hypertension and blood glucose levels regarding work type.

## Results

- **Spearman’s Correlation Test**: Indicated a strong positive correlation between stroke occurrence and both age and blood glucose levels. Work type showed a weak positive correlation with stroke, which was not statistically significant.
- **Chi-Square Test**: Revealed significant associations between stroke status and variables such as age, work type, and blood glucose levels.
- **Logistic Regression**: Highlighted the impact of hypertension and blood glucose on the relationship between work type and stroke, with a significant effect observed in the interaction analysis.

### Confusion Matrix

The confusion matrix for our binary classification model showed an accuracy of 90.74%, with high sensitivity but low specificity, indicating the model's performance in predicting stroke occurrence.

## Limitations

Our study acknowledges several limitations, including the potential for bias, the challenge of establishing causation from correlation, the impact of confounding variables, and the risks associated with extrapolation. We addressed some of these through careful methodological choices such as stratified sampling.

## Conclusion

The findings suggest that age and blood glucose levels are strongly positively correlated with stroke occurrence, while the association with work type is weaker and not statistically significant. These insights could help in identifying high-risk individuals and informing prevention strategies.

## Future Directions

Further research is needed to explore other variables that may influence stroke risk and to apply more sophisticated statistical techniques to enhance predictive accuracy.

