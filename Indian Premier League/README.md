# Indian Premier League

__The Indian Premier League__ (IPL) is a professional Twenty20 cricket league in India contested during April and May of every year by teams representing Indian cities and some states. The league was founded by the Board of Control for Cricket in India (__BCCI__) in 2008. The IPL is the most-attended cricket league in the world and in 2014 ranked sixth by average attendance among all sports leagues. There have been ten seasons of the IPL tournament

![image.png](https://images.mid-day.com/images/2019/mar/rr-ipl-tropy_d.jpg)

## Data Profiling
- As part of data profiling we __understand our dataset__ using various pandas functionalities.
- Then with the help of __pandas profiling__ we find which columns of our dataset need preprocessing.
- In __preprocessing__ we deal with erronous and missing values of columns. 
- Again we do __pandas profiling__ to see how preprocessing have transformed our dataset.

## Understanding the Data
All Indian Premier League Cricket matches between 2008 and 2018.
This is the ball by ball data of all the IPL cricket matches till season 11.
The dataset contains 2 files: deliveries.csv and matches.csv.
- matches.csv contains details related to the match such as location, contesting teams, umpires, results, etc.
- deliveries.csv is the ball-by-ball data of all the IPL matches including data of the batting team, batsman, bowler, non-striker, runs scored, etc.

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

## Analysis 

Data Science / Analytics is all about finding valuable insights from the given dataset. Inshort, Finding answers that could help business. So, here also we will get to know answers to a few questions and a few hidden indights. A Few of them are mentioned below.

 - How many matches are being played every season?
 - Which team has most winning percentage?
 - How many runs were scored across the seasons?
 - Who were the successful batsman & bowler in each season?
 - Which team has hit maximum number of boundaries in the entire IPL?
 - Who is the favourite umpire of IPL ?
 - Who has won the most Man Of The Match award?
 - How is the score distributions for teams in each innings?
 - Is Toss winner a Match Winner in IPL T20?
 - How is the run scoring patters for teams in each overs?
 - How many times a team has scored and conceeded 200+ runs? 
 - Who are the batsmen with most number of 1s, 2s, 4s and 6s?
 - How is the Individual Scores pattern By Top Batsman each Innings?
 - What is the average batsman score across seasons?
 - How were the batsmen got out mostly?
 
 [Direct Link to Jupyter Notebook](https://github.com/prasunk/ExploratoryDataAnalysis/blob/master/Indian%20Premier%20League/Matches_DataProfiling.ipynb)
 
