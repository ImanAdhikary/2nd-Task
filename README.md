# Second-Task
   1. I have loaded the new Preprocessed csv dataset using pandas.

   2. Mean, Medium, Std values are processed.

   3. Plotted the histogram for all numeric columns.

   4. Done the Box plot of 'Fare' and 'Age'. Calculated the no of outliers present in 'Age' and 'Fare'.

   5. Done the Pairplot for feature relationship.

   6. Formed the Correlation matrix with heatmap. The strongest positive correlation is in between 'SibSp' and 'Parch' and The strongest negative correlation is in between 'Pclass' and 'Fare'.

   7. Done Scatter plot for 'Age' and 'Fare'

   8. Between 'Fare' and 'Age', 'Fare' is highly skewed with skewness = 1.494, we need log scaling. log1p handles 0 values safely.

   9. Conclusion:
       1. The 'Fare' column is highly skewed and needs log scaling before modeling. 
       2. The strongest positive correlation is in between 'SibSp' and 'Parch'
       3. The strongest negative correlation is in between 'Pclass' and 'Fare'
       
