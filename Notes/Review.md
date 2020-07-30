# From Gwen:
- use [sns.swarmplot](https://www.google.com/search?q=sns.swarmplot&rlz=1C5CHFA_enUS728US728&sxsrf=ALeKk010uATmIg7ocMdrE1X4mg7LM0n6Zg:1594836937584&source=lnms&tbm=isch&sa=X&ved=2ahUKEwixl47J7s_qAhULG80KHbIFCQIQ_AUoA3oECA0QBQ&biw=1640&bih=916)
- [ensemble model](https://towardsdatascience.com/ensemble-learning-using-scikit-learn-85c4531ff86a) won most of the time.
- created polynomial features
- EDA, create a list of columns to run then put that into df[cols].fillna()

# From Henry:
- Readme file should include Problem statements and data Dictionary and table of contents.
    - his talked through the process, instead of just noting as he went along.
- outlier - remove based on the euclidean distance from the mean.  wrote a function to do it.
- saved the results of each model as csv and brought into the next notebook.
    - did not put a portion of data into a test set, instead used cross validation (cv=5) to test his model instead.
- created polynomial features
- created ordinal variables


# from Jocelyn
- had an Executive section 
- corr chart with labels converted to readable text.
- created correlation coef and included all above 0.5 for the columns to be used in model.
- clustered variables that were close to each other for every categorical variable.
- ran corr on ridge and lasso, then comparison between features and salesprice, then further removed or grouped features to run again.

By removing features we can get our notebooks smaller
- setup templates that you can plug and play into model comparison.
- make graphs and text readable format.