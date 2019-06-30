# Indian Premier League

__The Indian Premier League__ (IPL) is a professional Twenty20 cricket league in India contested during April and May of every year by teams representing Indian cities and some states. The league was founded by the Board of Control for Cricket in India (__BCCI__) in 2008. The IPL is the most-attended cricket league in the world and in 2014 ranked sixth by average attendance among all sports leagues. There have been ten seasons of the IPL tournament

![image.png](https://images.mid-day.com/images/2019/mar/rr-ipl-tropy_d.jpg)

## Data Profiling
- As part of data profiling we __understand our dataset__ using various pandas functionalities.
- Then with the help of __pandas profiling__ we find which columns of our dataset need preprocessing.
- In __preprocessing__ we deal with erronous and missing values of columns. 
- Again we do __pandas profiling__ to see how preprocessing have transformed our dataset.

## Pre-Processing 

- Find out missing values in given data set and replace them
- Drop unnecessary columns
- Derive new columns from given dataset.

## Pandas Profiling

Generates profile reports from a pandas DataFrame. The pandas df.describe() function is great but a little basic for serious exploratory data analysis. pandas_profiling extends the pandas DataFrame with df.profile_report() for quick data analysis.

For each column the following statistics - if relevant for the column type - are presented in an interactive HTML report:

- Essentials: type, unique values, missing values
- Quantile statistics like minimum value, Q1, median, Q3, maximum, range, interquartile range
- Descriptive statistics like mean, mode, standard deviation, sum, median absolute deviation, coefficient of variation, kurtosis, skewness
- Most frequent values
- Histogram
- Correlations highlighting of highly correlated variables, Spearman, Pearson and Kendall matrices
- Missing values matrix, count, heatmap and dendrogram of missing values

