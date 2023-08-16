1. The Naive Bayesian classifier is a simple probabilistic classifier that is often used for text classification tasks. It works by assuming that the attributes of a data point are independent of each other. In other words, it assumes that the probability of a data point belonging to a certain class is the product of the probabilities of each of its attributes belonging to that class.

Example

Consider the following training data set:

Class | Attribute 1 | Attribute 2 | Attribute 3

\-------|------------|------------|------------

0 | 1 | 0 | 0

0 | 0 | 1 | 1

0 | 1 | 1 | 0

1 | 1 | 1 | 1

1 | 0 | 0 | 1

This data set has two classes, 0 and 1. The class 0 has 4 data points, and the class 1 has 5 data points. The attribute values are also binary, 0 and 1.

To classify the tuple `X(1, 0, 0)`, we need to calculate the probability of it belonging to each class. The probability of `X(1, 0, 0)` belonging to class 0 is:

P(X(1, 0, 0)|Class 0) \* P(Class 0)


The probability of `X(1, 0, 0)` belonging to class 0 is the product of the probabilities of its three attributes being 0 or 1. The probability of the first attribute being 1 is `1/2`, since there are 2 possible values for the attribute and 1 of those values is 1. The probability of the second attribute being 0 is `1/2`, since there are 2 possible values for the attribute and 1 of those values is 0. The probability of the third attribute being 0 is `1/2`, since there are 2 possible values for the attribute and 1 of those values is 0. So the probability of `X(1, 0, 0)` belonging to class 0 is:

(1/2)^3 \* 4/9 = 1/54

The probability of class 0 is the number of data points in class 0 divided by the total number of data points, which is `4/9`. So the overall probability of `X(1, 0, 0)` belonging to class 0 is:

(1/2)^3 \* 4/9 = 1/54

\```

The probability of `X(1, 0, 0)` belonging to class 1 is:

\```

P(X(1, 0, 0)|Class 1) \* P(Class 1)


The probability of `X(1, 0, 0)` belonging to class 1 is the product of the probabilities of its three attributes being 0 or 1. The probability of the first attribute being 1 is `1/2`, since there are 2 possible values for the attribute and 1 of those values is 1. The probability of the second attribute being 0 is `1/2`, since there are 2 possible values for the attribute and 1 of those values is 0. The probability of the third attribute being 0 is `1/2`, since there are 2 possible values for the attribute and 1 of those values is 0. So the probability of `X(1, 0, 0)` belonging to class 1 is:

(1/2)^3 \* 5/9 = 2/54

Since the probability of `X(1, 0, 0)` belonging to class 0 is greater than the probability of it belonging to class 1, the Naive Bayesian classifier will classify `X(1, 0, 0)` as class 0. The probability of this classification is `1/54`.

Conclusion

The Naive Bayesian classifier is a simple but effective classifier that can be used for a variety of tasks. It is especially useful for text classification tasks, where the attributes of the data points are often independent of each other.

1. You have been assigned to run a linear regression model for each of 5,000 distinct districts, and all the data is currently stored in a PostgreSQL database. Which tool/ library would you use to produce these models with the least effort?

A. MADlib

B. HBase

C. Mahout

D. R

SUBMIT YOUR CHOICE

The correct answer is  A. MADlib .

MADlib is an open-source library for statistical and machine learning functions that can be used with PostgreSQL. It includes a number of functions for linear regression, including a function for running a linear regression model for each of 5,000 distinct districts.

HBase is a NoSQL database that is not designed for statistical analysis. Mahout is a machine learning library that can be used with Hadoop, but it is not as easy to use as MADlib. R is a programming language that is often used for statistical analysis, but it would require more effort to use R to run a linear regression model for each of 5,000 distinct districts than it would to use MADlib.

Here are some of the benefits of using MADlib to run linear regression models:

\* It is easy to use. MADlib provides a number of functions that can be used to run linear regression models, without the need to write any code.

\* It is efficient. MADlib can run linear regression models on large data sets quickly and efficiently.

\* It is scalable. MADlib can be used to run linear regression models on very large data sets.

1. What does the R code z <- <- f[1:10, ] do?

A. Assigns the 1st 10 columns to z

B. Assigns the 1st 10 columns of the 1st row of f to z

C. Assigns the first 10 rows of f to the vector z

D. Assigns a sequence of values from 1 to 10 to z

SUBMIT YOUR CHOICE

The R code `z <- <- f[1:10, ]`  assigns the first 10 rows of f to the vector z .

The `f[1:10, ]` part of the code selects the first 10 rows of the data frame f. The `z <- <-` part of the code assigns the selected rows to the vector z.

So the answer is  C. 

1. What is required in a presentation for project sponsors?

A. Line by line review of the developed code

B. Data warehouse design changes

C. The Big Picture takesaway for executive level stakeholders

D. Detailed statistical basis for the modeling approach used in the project

SUBMIT YOUR CHOICE

The correct answer is  C. The Big Picture takesaway for executive level stakeholders .

Project sponsors are typically not technical people, so they do not need to see a line-by-line review of the developed code or detailed statistical basis for the modeling approach used in the project. They need to see a high-level overview of the project, including the goals, the results, and the implications for the business.

Here are some of the things that should be included in a presentation for project sponsors:

\* A brief overview of the project, including the goals and objectives.

\* A summary of the results, including the key findings and recommendations.

\* The implications of the results for the business, including any potential risks or opportunities.

\* A call to action, outlining what the project sponsors need to do next.

The presentation should be clear, concise, and easy to understand. It should be tailored to the specific audience, and it should be focused on the key takeaways.

The other options are not as important for project sponsors.

\* Option A is not important because project sponsors do not need to see the code.

\* Option B is not important because project sponsors are not responsible for data warehouse design.

\* Option D is not important because project sponsors do not need to see the statistical basis for the modeling approach.

1. Which word or phrase completes the statement? Mahout is to Hadoop as MADlib is to\_

A. Excel

B. PostgreSQL

C. SAS

D. R

SUBMIT YOUR CHOICE

The answer is  PostgreSQL .

Mahout is a machine learning library that runs on Hadoop. It is used for tasks such as clustering, classification, and recommendation. MADlib is an open-source library for statistical and machine learning functions that can be used with PostgreSQL. It includes a number of functions for linear regression, logistic regression, and other statistical tasks.

Here is a table that summarizes the comparison between Mahout and MADlib:

| Feature | Mahout | MADlib |

\|---|---|---|

| Platform | Hadoop | PostgreSQL |

| Type | Machine learning library | Statistical and machine learning library |

| Tasks | Clustering, classification, recommendation | Linear regression, logistic regression, and other statistical tasks |

| Programming language | Java | SQL |

The analogy "Mahout is to Hadoop as MADlib is to PostgreSQL" is correct because both Mahout and MADlib are libraries that can be used for data analysis. Mahout is used for machine learning tasks on Hadoop, while MADlib is used for statistical tasks on PostgreSQL.

The other options are incorrect:

\* Excel is a spreadsheet program, not a machine learning library.

\* SAS is a commercial statistical software package, not an open-source library.

\* R is a programming language for statistical computing, not a database.

1. Which process in text analysis can be used to reduce dimensionality?

A. Digitizing

B. Parsing

C. Sorting

D. Stemming

SUBMIT YOUR CHOICE

The answer is  Stemming .

Stemming is a process in text analysis that reduces the number of words in a document by removing common prefixes and suffixes. This can be used to reduce dimensionality, which can improve the performance of machine learning algorithms.

For example, the words "running", "ran", and "runner" would all be stemmed to the word "run". This would reduce the number of unique words in the document from 3 to 1, which could improve the performance of a machine learning algorithm that is trying to classify the document.

The other options are incorrect:

\* Digitizing is the process of converting text into a digital format. This is not a process that can be used to reduce dimensionality.

\* Parsing is the process of breaking down a text document into its constituent parts, such as words, phrases, and sentences. This is not a process that can be used to reduce dimensionality.

\* Sorting is the process of arranging a set of data in a specific order. 

1. This is not a process that can be used to reduce dimensionality.

` `Consider these itemsets:

(hat, scarf, coat)

(hat, scarf, coat, gloves)

(hat, scarf, gloves)

(hat, gloves)

(scarf, coat, gloves)

What is the confidence of the rule (gloves -> hat)?

A. 66%

B. 75%

C. 60%

D. 80%

SUBMIT YOUR CHOICE

The correct answer is  C. 60% .

The confidence of a rule is the percentage of transactions that contain the consequent (hat) that also contain the antecedent (gloves). In this case, there are 5 transactions that contain gloves, and 3 of those transactions also contain hat. Therefore, the confidence of the rule (gloves -> hat) is 3/5 = 60%.

Here is a table that summarizes the confidence of each rule:

| Rule | Antecedent | Consequent | Confidence |

\|---|---|---|---|

| (gloves -> hat) | gloves | hat | 60% |

| (hat -> gloves) | hat | gloves | 80% |

| (scarf -> gloves) | scarf | gloves | 100% |

| (coat -> gloves) | coat | gloves | 100% |

The confidence of a rule can be calculated using the following formula:


confidence = (number of transactions that contain both the antecedent and the consequent) / (number of transactions that contain the antecedent)


In this case, there are 5 transactions that contain gloves, and 3 of those transactions also contain hat. Therefore, the confidence of the rule (gloves -> hat) is 3/5 = 60%.

1. Which characteristic applies mainly to Data Science as opposed to Business Intelligence?

A. Data dashboards

B. Robust reporting

C. Advanced analytical methods

D. Focus on structured data

SUBMIT YOUR CHOICE

The correct answer is  C. Advanced analytical methods .

Data science is a more advanced field of study than business intelligence. Data scientists use advanced analytical methods to extract insights from data, while business intelligence professionals focus on creating data dashboards and reports that are easy to understand for business users.

Here is a table that summarizes the differences between data science and business intelligence:

| Feature | Data Science | Business Intelligence |

\|---|---|---|

| Focus | Advanced analytical methods | Data dashboards and reports |

| Data types | Structured and unstructured data | Structured data |

| Tools | Python, R, Hadoop, Spark | Tableau, QlikView, Power BI |

| Skills | Mathematics, statistics, machine learning | Business acumen, data visualization |

Therefore, the characteristic that applies mainly to data science as opposed to business intelligence is advanced analytical methods.

1. Which data type value is used for the observed response variable in a logistic regression model?

A. A binary value

B. Anypositive real number

C. Any real number

D. Any integer

SUBMIT YOUR CHOICE

The correct answer is  A. A binary value .

Logistic regression is a type of regression that is used to predict a binary outcome, such as whether a customer will click on an ad or not. The observed response variable in a logistic regression model must be a binary value, such as 0 or 1.

Here is a table that summarizes the data types that can be used for the observed response variable in different types of regression models:

| Type of Regression Model | Data Type of Observed Response Variable |

\|---|---|

| Linear Regression | Any real number |

| Logistic Regression | Binary value |

| Poisson Regression | Non-negative real number |

| Multinomial Regression | Categorical value with more than two categories |

Therefore, the data type that applies to the observed response variable in a logistic regression model is a binary value.

1. A disk drive manufacturer has a defect rate of less than 1.0% with 98% confidence. A quality assurance team samples 1000 disk drives and finds 14 defective units. Which action should the team recommend?

A. A smaller sample size should be taken to determine if the plant is functioning properly 

B. The manufacturing process should be inspected for problems

C. The manufacturing process is functioning properly and no further action is required 

D. A larger sample size should be taken to determine if the plan is functioning properly

SUBMIT YOUR CHOICE

The correct answer is  B. The manufacturing process should be inspected for problems .

The defect rate of 14 defective units in 1000 disk drives is higher than the manufacturer's stated defect rate of less than 1.0%. This suggests that there may be a problem with the manufacturing process. The quality assurance team should inspect the manufacturing process to look for problems that may be causing the higher defect rate.

Here is a calculation of the defect rate:

\```

defect rate = (number of defective units / total number of units)

= (14 / 1000)

= 0.14%

\```

The defect rate of 0.14% is higher than the manufacturer's stated defect rate of less than 1.0%. This suggests that there may be a problem with the manufacturing process. The quality assurance team should inspect the manufacturing process to look for problems that may be causing the higher defect rate.

The other options are not appropriate.

\* Option A is not appropriate because the sample size of 1000 is already large enough to be statistically significant.

\* Option C is not appropriate because the defect rate of 0.14% is higher than the manufacturer's stated defect rate.

\* Option D is not appropriate because a larger sample size would not be necessary to determine if the manufacturing process is functioning properly.

1. You are performing a market basket analysis using the Apriori algorithm. Which measure is a ratio describing the how many more times two items are present together than would be expected if those two items are statistically independent?

A. Support

B. Leverage

C. Lift

D. Confidence

SUBMIT YOUR CHOICE

The correct answer is  C. Lift .

Lift is a measure of how many more times two items are present together than would be expected if those two items are statistically independent. It is calculated as follows:

\```

lift = (frequency of itemset in transactions / expected frequency of itemset in transactions)

\```

where:

\* frequency of itemset in transactions is the number of times the itemset appears in the transactions

\* expected frequency of itemset in transactions is the number of times the itemset would be expected to appear in the transactions if the items were statistically independent

For example, if the lift for the itemset {bread, milk} is 2, then this means that bread and milk are twice as likely to appear together in the transactions than would be expected if they were statistically independent.

The other options are incorrect:

\* Support is the number of transactions that contain the itemset.

\* Leverage is a measure of how much the presence of one item increases the probability of the presence of another item.

\* Confidence is the probability that the consequent will occur given that the antecedent has occurred. 

1. A data scientist is given an R data frame, empdata, with the columns Age, Salary, Occupation, Education, and Gender. The data scientist would like to examine only the Salary and Occupation columns for ages greater than 40. 

Which command extracts the appropriate rows and columns from the data frame?

A. empdata[,c(Salary,Occupation)]$Age > 40

B. empdata[c(Salary,Occupation), empdata$Age > 40]

C. empdata[Age > 40,(Salary,Occupation)] 

D. empdata[empdata$Age > 40, c(Salary,Occupation)]

SUBMIT YOUR CHOICE

The correct answer is  D. empdata[empdata$Age > 40, c(Salary,Occupation)] .

The command `empdata[empdata$Age > 40, c(Salary,Occupation)]` first selects the rows in the data frame where the Age column is greater than 40. Then, it selects only the Salary and Occupation columns from the selected rows.

The other options are incorrect:

\* Option A is incorrect because it uses the dollar sign ($) to refer to the column names. In R, you do not need to use the dollar sign to refer to column names.

\* Option B is incorrect because it uses the comma (,) to separate the column names. In R, you need to use the pipe (|) to separate the column names.

\* Option C is incorrect because it does not select the rows where the Age column is greater than 40.

1. In data visualization, which type of chart is recommended to represent frequency data?

A. Scatterplot

B. Line chart

C. Histogram

D. Q Q chart

SUBMIT YOUR CHOICE

The correct answer is  C. Histogram .

A histogram is a type of chart that shows the frequency distribution of a quantitative variable. It is a good choice for representing frequency data because it shows the number of times each value of the variable occurs. This can be helpful for understanding the distribution of the data and identifying any patterns.

A scatterplot is a type of chart that shows the relationship between two variables. It is not a good choice for representing frequency data because it does not show the frequency of each value of the variable.

A line chart is a type of chart that shows the change in a variable over time. It is not a good choice for representing frequency data because it does not show the frequency of each value of the variable.

A Q Q chart is a type of chart that is used to identify outliers in a data set. It is not a good choice for representing frequency data.

Therefore, the best type of chart to represent frequency data is a histogram.

1. In linear regression modeling, which action can be taken to improve the linearity of the relationship between the dependent and independent variables?

A. Use a different statistical package

B. Calculate the R Squared value

C. Apply a transformation to a variable

D. Change the units of measurement on the independent variable

SUBMIT YOUR CHOICE

The correct answer is  C. Apply a transformation to a variable .

In linear regression modeling, a transformation is a mathematical operation that is applied to a variable to change its distribution. This can be done to improve the linearity of the relationship between the dependent and independent variables.

For example, if the distribution of the independent variable is skewed, you can apply a logarithmic transformation to the variable. This will make the distribution more symmetrical, which can improve the linearity of the relationship.

Here are some other transformations that can be used to improve the linearity of the relationship between the dependent and independent variables:

\* Square root transformation

\* Exponential transformation

\* Logarithmic transformation

\* Box-Cox transformation

The choice of transformation will depend on the specific data set and the relationship between the dependent and independent variables.

The other options are incorrect:

\* Option A is incorrect because using a different statistical package will not change the linearity of the relationship between the dependent and independent variables.

\* Option B is incorrect because the R Squared value is a measure of the goodness of fit of the model, not the linearity of the relationship.

\* Option D is incorrect because changing the units of measurement on the independent variable will not change the linearity of the relationship.

1. What is required in a presentation for business analysts?

A. Detailed statistical explanation of the applicable modeling theory

B. The presentation authors credentials

C. Operational process changes

D. Budgetary considerations and requests

SUBMIT YOUR CHOICE

The correct answer is  C. Operational process changes .

Business analysts are responsible for understanding the business needs of an organization and using data to improve those processes. Therefore, a presentation for business analysts should focus on the operational process changes that can be made as a result of the analysis.

The presentation should include a clear explanation of the problem that the analysis is trying to solve, as well as the results of the analysis. The presentation should also be tailored to the specific audience of business analysts, so it should use non-technical language and avoid jargon.

The other options are not as important for a presentation for business analysts:

\* Option A is not important because business analysts are not typically concerned with the statistical details of the modeling theory.

\* Option B is not important because the presentation authors' credentials are not relevant to the business analysts.

\* Option D is not important because budgetary considerations are typically handled by a different team.

1. Which characteristic applies only to Business Intelligence as opposed to Data Science?

A. Uses predictive modeling techniques

B. Uses large data sets

C. Supports solving what if scenarios

D. Uses only structured data

SUBMIT YOUR CHOICE

The answer is  C. Supports solving what if scenarios .

Business intelligence (BI) is the use of data analytics to help businesses make decisions. BI tools and technologies can be used to analyze historical data, identify trends, and create reports and dashboards that help businesses understand their operations. BI can also be used to support what-if scenarios, which are simulations that allow businesses to see how different decisions might impact their results.

Data science is a more technical field that uses advanced analytics and machine learning techniques to extract insights from data. Data scientists often use BI tools, but they also develop their own tools and techniques to solve specific problems. Data science is not typically used to support what-if scenarios, as this is more of a business-facing need.

Here is a table that summarizes the differences between BI and data science:

| Feature | Business Intelligence | Data Science |

\|---|---|---|

| Focus | Making decisions | Extracting insights |

| Data types | Structured data | Structured and unstructured data |

| Tools | BI tools, dashboards, reports | Programming languages, machine learning libraries |

| Skills | Business acumen, data visualization | Mathematics, statistics, machine learning |

Therefore, the characteristic that applies only to Business Intelligence as opposed to Data Science is supports solving what if scenarios.

1. What is the format of the output from the Map function of MapReduce?

A. Unique key record and seperate records of all possible values

B. Key value pairs

C. Binary representation of keys concatenated with structured data

D. Compressed index

SUBMIT YOUR CHOICE

The correct answer is  B. Key value pairs .

The Map function in MapReduce is responsible for breaking down the input data into key-value pairs. The key is typically a unique identifier for the data, and the value is the data itself. The Map function then outputs these key-value pairs to the Hadoop Distributed File System (HDFS).

The Reduce function in MapReduce is responsible for grouping the key-value pairs and performing an aggregation operation on them. The aggregation operation can be a sum, a count, or any other operation that you want to perform on the data.

Here is an example of the output from the Map function of MapReduce:

\```

(key1, value1)

(key2, value2)

(key3, value3)

\```

The key-value pairs can be stored in any format, but they are typically stored in a text format. The key and value can be separated by a delimiter, such as a comma or a tab character.

The other options are incorrect:

\* Option A is incorrect because the Map function does not output unique key records and separate records of all possible values.

\* Option C is incorrect because the Map function does not output binary representations of keys concatenated with structured data.

\* Option D is incorrect because the Map function does not output compressed indexes.

1. A data scientist wants to predict the probability of death from heart disease based on three risk factors: age, gender, and blood cholesterol level. What is the most appropriate method for this project?

A. Logistic regression

B. Linear regression

C. K means clustering

D. Apriori algorithm

SUBMIT YOUR CHOICE

The correct answer is  A. Logistic regression .

Logistic regression is a statistical model that is used to predict the probability of a binary outcome, such as whether a person will die from heart disease or not. The three risk factors that the data scientist wants to use are all categorical variables, so logistic regression is a good choice for this project.

Linear regression is a statistical model that is used to predict a continuous outcome, such as a person's blood pressure. K means clustering is a clustering algorithm that is used to group data points into clusters. Apriori algorithm is an association rule learning algorithm that is used to find patterns in data.

Here is a table that summarizes the differences between the four methods:

| Method | Description | Appropriate for |

\|---|---|---|

| Logistic regression | A statistical model that is used to predict the probability of a binary outcome | Predicting the probability of death from heart disease |

| Linear regression | A statistical model that is used to predict a continuous outcome | Predicting a person's blood pressure |

| K means clustering | A clustering algorithm that is used to group data points into clusters | Finding patterns in customer behavior |

| Apriori algorithm | An association rule learning algorithm that is used to find patterns in data | Finding patterns in product purchases |

1. What is an appropriate data visualization to use in a presentation for a project sponsor?

A. Pie chart

B. Box and Whisker plot

C. Bar chart

D. Density plot

SUBMIT YOUR CHOICE

The answer is  C. Bar chart .

A bar chart is a good choice for a data visualization to use in a presentation for a project sponsor because it is easy to understand and interpret. It is also a versatile visualization that can be used to show a variety of different data sets.

For example, you could use a bar chart to show the results of a survey, the performance of different products, or the costs of different projects.

Here are some other reasons why bar charts are a good choice for presentations:

\* They are easy to read and understand, even for people who are not familiar with data visualization.

\* They can be used to show a variety of different data sets.

\* They can be customized to fit the specific needs of the presentation.

\* They can be used to compare different data sets.

The other options are not as appropriate for presentations:

\* Pie charts are not as easy to read and understand as bar charts.

\* Box and whisker plots are more technical and may not be appropriate for a presentation to a project sponsor.

\* Density plots are also more technical and may not be appropriate for a presentation to a project sponsor.

1. Which SQL OLAP extension provides all possible grouping combinations?

A. CROSS JOIN

B. ROLLUP

C. CUBE

D. UNION ALL

SUBMIT YOUR CHOICE

The answer is  C. CUBE .

CUBE is an SQL OLAP extension that provides all possible grouping combinations for a given set of dimensions. It is a more powerful than ROLLUP, which only provides the immediate parent-child groupings.

1. Here is an example of how CUBE can be used to get all possible groupings for the dimensions `product` and `color`:

\```sql

SELECT

`  `product,

`  `color,

`  `SUM(quantity) AS total\_quantity

FROM

`  `orders

GROUP BY

`  `CUBE(product, color)

\```

This query will return the following results:

| product | color | total\_quantity |

\|---|---|---|

| A | Red | 100 |

| A | Green | 200 |

| B | Red | 300 |

| B | Green | 400 |

| C | Red | 500 |

| C | Green | 600 |

As you can see, the CUBE function provides all possible combinations of the `product` and `color` dimensions. This can be useful for getting a complete overview of the data.

The other options are incorrect:

\* CROSS JOIN will return all possible combinations of rows in a table, regardless of the dimensions.

\* ROLLUP will only return the immediate parent-child groupings for a given set of dimensions.

\* UNION ALL will return the union of two or more queries, but it does not provide any grouping.

1. In a Students t test, what is the meaning of the p value?

A. it is the power of the student t test

B. it is the area under the appropriate tails of students distribution

C. it is the mean of the distribution for the alternate hypothesis

D. it is the mean of the distribution for the nul hypothesis

SUBMIT YOUR CHOICE

The correct answer is  B. it is the area under the appropriate tails of students distribution .

In a Student's t-test, the p-value is the probability of obtaining a test statistic at least as extreme as the one that was actually observed, assuming that the null hypothesis is true. The p-value is calculated by finding the area under the appropriate tail(s) of the Student's t-distribution.

The Student's t-distribution is a probability distribution that is used to calculate the p-value for a Student's t-test. The Student's t-distribution is a bell-shaped curve, but it is wider than the normal distribution. This is because the Student's t-distribution takes into account the uncertainty that is introduced when the sample size is small.

The p-value is used to determine whether to reject the null hypothesis. If the p-value is less than a pre-specified significance level, such as 0.05, then the null hypothesis is rejected. This means that there is sufficient evidence to conclude that the alternative hypothesis is true.

The other options are incorrect:

\* Option A is incorrect because the power of a test is the probability of rejecting the null hypothesis when it is false.

\* Option C is incorrect because the mean of the distribution for the alternate hypothesis is not equal to the mean of the distribution for the null hypothesis.

\* Option D is incorrect because the mean of the distribution for the null hypothesis is equal to 0.On analyzing your time series data you suspect that the data represented as |y1, y2, y3, ..., yn-1, yn may have a trend component that is quadratic in nature. 

1. Which pattern of data will indicate that the trend in the time series data is quadratic in nature?

A. (y2-y1)=(y3-y2)=.....=(yn-yn-1)

B. ((y2-y1)/y1) \* 100% =.....( ..((yn-yn-1)/yn-1)\* 100%

C. (y3-y2)-(y2-y1)=......=(yn-yn-1)-(yn-1-yn-2)

D. (y4-y2)-(y3-y1)=......=(yn-yn-2)-(yn-1-yn-3)

SUBMIT YOUR CHOICE

The correct answer is  C. (y3-y2)-(y2-y1)=......=(yn-yn-1)-(yn-1-yn-2) .

A quadratic trend in time series data is a trend that increases or decreases at an increasing rate. This can be seen in the pattern of data in option C. The difference between consecutive values in the time series is increasing over time.

For example, if the first value in the time series is 10, the second value is 12, and the third value is 15, then the difference between consecutive values is increasing. This pattern of data indicates that the trend in the time series is quadratic in nature.

The other options are incorrect:

\* Option A is incorrect because it indicates a linear trend, not a quadratic trend.

\* Option B is incorrect because it indicates a percentage change, not a difference between consecutive values.

\* Option D is incorrect because it indicates a difference between consecutive values, but the difference is not increasing over time.On analyzing your time series data you suspect that the data represented as |y1, y2, y3, ..., yn-1, yn may have a trend component that is quadratic in nature. 

1. Which pattern of data will indicate that the trend in the time series data is quadratic in nature?

A. (y2-y1)=(y3-y2)=.....=(yn-yn-1)

B. ((y2-y1)/y1) \* 100% =.....( ..((yn-yn-1)/yn-1)\* 100%

C. (y3-y2)-(y2-y1)=......=(yn-yn-1)-(yn-1-yn-2)

D. (y4-y2)-(y3-y1)=......=(yn-yn-2)-(yn-1-yn-3)

SUBMIT YOUR CHOICE

The correct answer is  C. (y3-y2)-(y2-y1)=......=(yn-yn-1)-(yn-1-yn-2) .

A quadratic trend in time series data is a trend that increases or decreases at an increasing rate. This can be seen in the pattern of data in option C. The difference between consecutive values in the time series is increasing over time.

For example, if the first value in the time series is 10, the second value is 12, and the third value is 15, then the difference between consecutive values is increasing. This pattern of data indicates that the trend in the time series is quadratic in nature.

The other options are incorrect:

\* Option A is incorrect because it indicates a linear trend, not a quadratic trend.

\* Option B is incorrect because it indicates a percentage change, not a difference between consecutive values.

\* Option D is incorrect because it indicates a difference between consecutive values, but the difference is not increasing over time.

1. You do a Student's t test to compare the average test scores of sample groups from populations A and B. Group A averaged 10 points higher than group B. You find that this difference is significant, with a p value of 0.03. What does that mean?

A. There is a 97% chance that a sample group from population A will score 10 points higher that a sample group from population B.

B. There difference in score between a sample from population A and a sample from population B will tend to be within 3% of 10 points

C. There is a 3% chance that a sample group from population A will score 10 points higher that a sample group from population B.

D. There is a 3% chance that you have identified a

O difference between the populations when in

reality there is none.

SUBMIT YOUR CHOICE

The correct answer is  D. There is a 3% chance that you have identified a difference between the populations when in reality there is none. 

A p-value of 0.03 means that there is a 3% chance that the difference in average test scores between the two populations is due to chance. In other words, there is a 97% chance that the difference in average test scores is real and not due to chance.

So, the interpretation of the p-value is that there is a 3% chance that you have identified a difference between the populations when in reality there is none.

The other options are incorrect. Option A is incorrect because it states that there is a 97% chance that a sample group from population A will score 10 points higher than a sample group from population B. This is not what the p-value means. The p-value only tells us the probability that the difference in average test scores is due to chance. It does not tell us the probability that a particular sample group will score 10 points higher.

Option B is incorrect because it states that the difference in score between a sample from population A and a sample from population B will tend to be within 3% of 10 points. This is not what the p-value means. The p-value only tells us the probability that the difference in average test scores is due to chance. It does not tell us anything about the distribution of the scores in the two populations.

Option C is incorrect because it states that there is a 3% chance that a sample group from population A will score 10 points higher than a sample group from population B. This is the same as option A, and it is also incorrect.

1. Which analytical method is considered unsupervised?

A. K means clustering

B. Decision tree

C. Native Bayesian classifier

D. Linear regression

SUBMIT YOUR CHOICE

The answer is  A. K means clustering .

Unsupervised learning is a type of machine learning where the algorithm is not given any labeled data. The algorithm must learn on its own by finding patterns in the data.

K means clustering is an unsupervised learning algorithm that is used to group data points into clusters. The algorithm starts by randomly assigning the data points to clusters. Then, it iteratively optimizes the clusters by moving data points from one cluster to another until the clusters are well-separated.

Decision trees, native Bayesian classifiers, and linear regression are all supervised learning algorithms. Supervised learning algorithms require labeled data to learn on.

Here is a table that summarizes the different analytical methods and whether they are supervised or unsupervised:

| Analytical Method | Supervised or Unsupervised |

\|---|---|

| K means clustering | Unsupervised |

| Decision tree | Supervised |

| Native Bayesian classifier | Supervised |

| Linear regression | Supervised |

1. The average purchase size from your online sales site is $17,200. The customer experience team believes a certain adjustment of the website will increase sales. A pilot study on a few hundred customers showed an increase in average purchase size of $1.47, with a significance level of p=0.1. The team runs a larger study, of a few thousand customers. The second study shows an increased average purchase size of $0.74, with a significance level of 0.03. What is your assessment of this study?

A. The change in purchase size is small, but may aggregate up to a large increase in profit over the entire customer base

B. The difference in the change in purchase size between the two studies is troubling; The team should run another, larger study.

C. The p value of the second study shows a statistically significant change in purchase size. The new website is an improvement.

D. The change in purchase size is not practically important, and the good p value of the second study is probably a result of the large study size.

SUBMIT YOUR CHOICE

The answer is  B. The difference in the change in purchase size between the two studies is troubling; The team should run another, larger study. 

The p-value of the second study is statistically significant, which means that there is a 97% chance that the increase in average purchase size is not due to chance. However, the increase in average purchase size is only $0.74, which is a relatively small amount. It is possible that this increase is not practically important, and that the good p value of the second study is probably a result of the large study size.

The difference in the change in purchase size between the two studies is also troubling. The pilot study showed an increase in average purchase size of $1.47, while the larger study showed an increase in average purchase size of only $0.74. This difference could be due to chance, but it could also be due to other factors, such as the different sample sizes of the two studies.

It is important to note that the significance level of a study is not the only factor to consider when assessing the results of a study. The practical importance of the results is also important. In this case, the increase in average purchase size is relatively small, and it is not clear whether this increase is practically important.

The team should run another, larger study to confirm the results of the second study. The new study should also try to identify the factors that are driving the change in purchase size. This information can be used to improve the website and increase sales.

1. Consider the example of an analysis for fraud detection on credit card usage. You will need to ensure higher-risk transactions that may indicate fraudulent credit card activity are retained in your data for analysis, and not dropped as outliers during pre-processing. What will be your approach for loading data into the analytical sandbox for this analysis?

A. ETL

B. OLTP

C. EDW

D. ETL

SUBMIT YOUR CHOICE

The correct answer is  A. ETL .

ETL stands for extract, transform, and load. It is a process for loading data from a source system into a data warehouse or data mart. The ETL process typically involves the following steps:

1\. Extracting the data from the source system.

2\. Transforming the data into a format that is compatible with the target system.

3\. Loading the data into the target system.

In the case of fraud detection, it is important to use ETL to ensure that higher-risk transactions are not dropped as outliers during pre-processing. This can be done by configuring the ETL process to retain all transactions, regardless of their value or frequency.

OLTP stands for online transaction processing. It is a type of system that is used to process transactions in real time. OLTP systems are not typically used for data analysis, as they are not designed to handle large volumes of data.

EDW stands for enterprise data warehouse. It is a centralized repository for data from different sources. EDWs are typically used for data analysis, but they can also be used for ETL.

In this case, the best approach for loading data into the analytical sandbox is to use ETL. This will ensure that all transactions are retained, including higher-risk transactions that may indicate fraudulent credit card activity.

1. You have two tables of customers in your database. Customers in cust\_table\_1 were sent an email promotion last year, and customers in cust\_table\_2 received a newsletter last year. Customers can only be entered in once per table. You want to create a table that includes all customers, and any of the communications they received last year. Which type of join would you use for this table?

A. inner join

B. full outer join

C. left outer join

D. cross join

SUBMIT YOUR CHOICE

The answer is  B. full outer join .

A full outer join will return all rows from both tables, even if there is no match on the join key. This is the best option for creating a table that includes all customers, and any of the communications they received last year.

An inner join will only return rows where there is a match on the join key. This would not be a good option in this case, as it would not return all customers.

A left outer join will return all rows from the left table, even if there is no match on the join key. This would also not be a good option in this case, as it would not return all communications that customers received.

A cross join will return the Cartesian product of the two tables. This would return all possible combinations of rows from the two tables, which would be a very large table.

1. Here is an example of the output of a full outer join for the two tables:

| customer\_id | email\_promotion | newsletter |

\|---|---|---|

| 1 | Yes | No |

| 2 | No | Yes |

| 3 | Yes | Yes |

As you can see, the table includes all customers, even if they did not receive both communications. This is the desired outcome.In which lifecycle stage are initial hypotheses formed?

A. Discovery

B. Data preparation

C. Model building

D. Model planning

SUBMIT YOUR CHOICE

The correct answer is  A. Discovery .

In the discovery stage of the data science lifecycle, the data scientist partners with the business stakeholders to understand the problem that they are trying to solve. The data scientist also gathers data and performs exploratory data analysis (EDA) to gain insights into the data.

During the discovery stage, the data scientist will form initial hypotheses about the data. These hypotheses will be tested in the next stage of the lifecycle, which is data preparation.

Data preparation is the process of cleaning and transforming the data so that it is ready to be modeled. During data preparation, the data scientist will also verify the initial hypotheses that were formed in the discovery stage.

Model building is the process of creating a model that can be used to predict or make decisions. The model building stage is informed by the data preparation stage, as the data scientist will use the prepared data to train the model.

Model planning is the process of deploying the model into production and monitoring its performance. The model planning stage is informed by the model building stage, as the data scientist will use the model to make predictions or decisions.

In summary, the initial hypotheses are formed in the discovery stage of the data science lifecycle.

1. Trend, seasonal, and cyclical are components of a time series. What is another component?

A. Quadratic

B. Linear

C. Exponential

D. Irregular

SUBMIT YOUR CHOICE

The answer is  D. Irregular .

Time series data is typically made up of four components: trend, seasonal, cyclical, and irregular.

Trend is the long-term direction of the data. For example, the price of a stock may be trending upwards over time.

Seasonal is the repeating pattern of the data over a short period of time. For example, the number of ice cream sales may be higher in the summer than in the winter.

Cyclical is the long-term fluctuations in the data that are not caused by trend or seasonality. For example, the economy may go through periods of growth and recession.

Irregular is the random variation in the data that cannot be explained by any of the other components.

In this case, the irregular component is the random variation in the data that cannot be explained by trend, seasonal, or cyclical components.

1. In which phase of the data analytics lifecycle do Data Scientists spend the most time in a project?

A. Model Building

B. Discovery

C. Communicate Result

D. Data Preparation

SUBMIT YOUR CHOICE

Data scientists typically spend the most time in the  Data Preparation phase of the data analytics lifecycle.

Data Preparation is the process of cleaning and transforming data so that it is ready to be modeled. This can be a very time-consuming process, as it often involves identifying and correcting errors in the data, removing outliers, and transforming the data into a format that is compatible with the modeling software.

The other phases of the data analytics lifecycle, such as Discovery, Model Building, and Communicate Results, are typically less time-consuming.

Here is a table that shows the typical amount of time that data scientists spend in each phase of the data analytics lifecycle:

| Phase | Typical Time Spent |

\|---|---|

| Discovery | 10-20% |

| Data Preparation | 50-60% |

| Model Building | 20-30% |

| Communicate Results | 10% |

It is important to note that the amount of time that data scientists spend in each phase of the lifecycle can vary depending on the specific project. For example, a project that involves a lot of data cleaning and transformation may require more time in the Data Preparation phase.

1. What does R code nv <- <- v[v < 1000] do?

A. Removes elements of vector v less than 1000 and assigns the elements >= 1000 to nv

B. Set nv to TRUE or FALSE depending on whether all elements of vector v are less than 1000

C. Selects values of vector v less than 1000, modifies v, and makes a copy to nv

D. Select the values in vector v than are less than 1000 and assigns them to the vector nv

SUBMIT YOUR CHOICE

The R code nv <- <- v[v < 1000]  selects the values in vector v that are less than 1000 and assigns them to the vector nv .

The `<-` operator in R is used to assign a value to a variable. In this case, the value of the vector v that are less than 1000 are assigned to the variable nv.

The `[]` operator in R is used to extract elements from a vector. In this case, the `v[v < 1000]` expression extracts the elements of vector v that are less than 1000.

So, the overall effect of the code is to select the values in vector v that are less than 1000 and assign them to the vector nv.

Here is an example of how the code would work:

\```

v <- c(1, 2, 3, 4, 5, 6, 7, 8, 9, 10)

nv <- v[v < 1000]

print(nv)

\```

1. This code would create a vector v that contains the numbers 1, 2, 3, 4, 5, and 6. The code would then assign the values in vector v that are less than 1000 to the vector nv. The value of nv would then be `[1, 2, 3, 4, 5]`. You have used k-means clustering to classify behavior of 100, 000 customers for a retail store. You decide to use household income, age, gender and yearly purchase amount as measures. You have chosen to use 8 clusters and notice that 2 clusters only have 3 customers assigned. What should you do?

A. Decrease the number of clusters

B. Increase the number of clusters

C. Identify additional measures to add to the analysis

D. Decrease the number of measures used

SUBMIT YOUR CHOICE

The correct answer is  A. Decrease the number of clusters .

When using k-means clustering, it is important to have a sufficient number of clusters to capture the different customer behaviors. However, if there are too many clusters, then the clusters will be too small and will not be meaningful.

In this case, the 2 clusters with only 3 customers assigned are too small to be meaningful. This suggests that there are not enough customers with similar behaviors to form these clusters.

The best course of action is to decrease the number of clusters to 6 or 7. This will still allow for a reasonable number of clusters, while also ensuring that the clusters are large enough to be meaningful.

It is also possible to identify additional measures to add to the analysis. This could help to create more distinct clusters. However, it is important to be careful not to add too many measures, as this could make the clustering algorithm less stable.

1. Decreasing the number of measures used is not a good option in this case. The measures that are already being used are likely to be the most important ones for clustering customer behavior. Removing any of these measures could make it more difficult to create meaningful clusters.Which word or phrase completes the statement? Business Intelligence is to monitoring trends as Data Science is to trends.

A. Driving

B. Discarding

C. Predicting

D. Optimizing

SUBMIT YOUR CHOICE

The correct answer is  C. Predicting .

Business intelligence is a broad term that encompasses the collection, analysis, and presentation of data. It is used to monitor trends and identify patterns in data. Data science is a more specialized field that uses statistical and machine learning techniques to extract insights from data. It is used to predict future trends and optimize business decisions.

In the statement, Business Intelligence is to monitoring trends as Data Science is to predicting. This is because Business Intelligence is used to identify and track trends in data, while Data Science is used to predict future trends based on historical data.

For example, a Business Intelligence (BI) analyst might use data to track the sales of a product over time. They might notice that sales tend to increase in the summer and decrease in the winter. This is a trend that can be monitored by the BI analyst.

A Data Scientist might use the same data to predict future sales of the product. They might use historical data to train a machine learning model that can predict future sales. This is an example of how Data Science can be used to predict trends.

The other options are incorrect:

Driving is not a good fit for the statement because Business Intelligence does not drive trends. It simply monitors and identifies trends.

Discarding is not a good fit for the statement because Business Intelligence does not discard trends. It simply monitors and identifies trends.

Optimizing is not a good fit for the statement because Business Intelligence does not optimize trends. It simply monitors and identifies trends.

1. What is the purpose of the process step parsing in text analysis?

A. imposes a structure on the unstructured/semi structured text for downstream analysis

B. performs the search and//or retrievel in finding a specific topic or an entity in a document

C. executes the clustering and classification to organize the contents

D. computes the TF IDF values for all keywords and indices

SUBMIT YOUR CHOICE

The correct answer is  A. imposes a structure on the unstructured/semi structured text for downstream analysis .

Parsing is the process of breaking down a string of text into its component parts, such as words, phrases, and sentences. In text analysis, parsing is used to impose a structure on unstructured or semi-structured text. This structure can then be used for downstream analysis tasks, such as searching, clustering, and classification.

For example, if you have a document that is full of unstructured text, you can use parsing to break the document down into its component words and phrases. You can then use these words and phrases to create a search index, which can be used to find specific topics or entities in the document.

Parsing can also be used to cluster documents together based on their content. For example, you can use parsing to cluster documents together that are about the same topic. This can be helpful for organizing large collections of documents.

Finally, parsing can be used to classify documents into different categories. For example, you can use parsing to classify documents as spam or not spam.

Therefore, the purpose of the process step parsing in text analysis is to impose a structure on the unstructured/semi structured text for downstream analysis.

1. You are testing two new weight-gain formulas for puppies. The test gives the results: Control group: 1% weight gain Formula A. 3% weight gain Formula B. 4% weight gain A one-way ANOVA returns a |p-value = 0.027 What can you conclude?

A. Formula A and Formula B are about equally effective at promoting weight gain

B. Formula B is more effective at promoting weight gain than Formula A.

C. Either Formula A or Formula B is effective at promoting weight gain

D. Formula A and Formula B are both effective at promoting weight gain

SUBMIT YOUR CHOICE

The correct answer is  B. Formula B is more effective at promoting weight gain than Formula A. 

The p-value of 0.027 is less than the significance level of 0.05, which means that there is a statistically significant difference between the weight gain of the puppies in the three groups.

The control group had a weight gain of 1%, Formula A had a weight gain of 3%, and Formula B had a weight gain of 4%. This suggests that Formula B is more effective at promoting weight gain than Formula A.

It is important to note that this is just one study, and more research is needed to confirm the findings. However, the results of this study suggest that Formula B may be a more effective weight-gain formula for puppies than Formula A.

The other options are incorrect:

A. Formula A and Formula B are about equally effective at promoting weight gain. This is not supported by the data, as Formula B had a higher weight gain than Formula A.

C. Either Formula A or Formula B is effective at promoting weight gain. This is true, but it is not as specific as the conclusion that Formula B is more effective at promoting weight gain than Formula A.

D. Formula A and Formula B are both effective at promoting weight gain. This is not supported by the data, as Formula B had a higher weight gain than Formula A.

1. A call center for a large electronics company handles an average of 35, 000 support calls a day. The head of the call center would like to optimize the staffing of the call center during the rollout of a new product due to recent customer complaints of long wait times. You have been asked to create a model to optimize call center costs and customer wait times. The goals for this project include: 1. Relative to the release of a product, how does the call volume change over time? 2. How to best optimize staffing based on the call volume for the newly released product, relative to old products. 3. Historically, what time of day does the call center need to be most heavily staffed? 4. Determine the |frequency of calls by both product type and customer language. Which goals are suitable to be completed with MapReduce?

A. Goal 1 and 3

B. Goal 2 and 4

C. Goal 2,3,4

D. Goal 1,2,3,4

SUBMIT YOUR ANSWER

The answer is  B. Goal 2 and 4 .

MapReduce is a programming model and an associated implementation for processing and generating large data sets. It is designed to scale up from single machines to thousands of machines.

Goal 2 and 4 are suitable to be completed with MapReduce because they involve processing large data sets. Goal 2 involves determining how to optimize staffing based on the call volume for the newly released product, relative to old products. This can be done by processing the call data for all products and identifying the product with the highest call volume. Goal 4 involves determining the frequency of calls by both product type and customer language. This can be done by processing the call data and grouping the calls by product type and customer language.

Goal 1 and 3 are not suitable to be completed with MapReduce because they do not involve processing large data sets. Goal 1 involves determining how the call volume changes over time relative to the release of a product. This can be done by plotting the call volume data over time. Goal 3 involves determining what time of day the call center needs to be most heavily staffed. This can be done by analyzing the call volume data by hour of the day.

1. Here is a table that summarizes which goals are suitable to be completed with MapReduce:

| Goal | Suitable for MapReduce? |

\|---|---|

| 1. Relative to the release of a product, how does the call volume change over time? | No |

| 2. How to best optimize staffing based on the call volume for the newly released product, relative to old products. | Yes |

| 3. Historically, what time of day does the call center need to be most heavily staffed? | No |

| 4. Determine the frequency of calls by both product type and customer language. | Yes |What is one modeling or descriptive statistical function in MADlib that is typically not provided in a standard relational database?

A. Expected value

B. Variance

C. Quantiles

D. Linear regression

SUBMIT YOUR CHOICE

The answer is  C. Quantiles .

Quantiles are not typically provided in a standard relational database. They are a type of descriptive statistic that divides a data set into equal parts. For example, the 25th percentile is the value below which 25% of the data points in the data set fall.

MADlib provides a number of functions for calculating quantiles, including:

\* `approx\_quantile()`: This function calculates approximate quantiles using a specified number of bins.

\* `exact\_quantile()`: This function calculates exact quantiles using a divide-and-conquer algorithm.

\* `sample\_quantile()`: This function calculates quantiles on a sample of the data set.

These functions can be used to gain insights into the distribution of data and to identify outliers.

The other options are provided in a standard relational database:

\* Expected value: The expected value of a random variable is the average of all possible values.

\* Variance: The variance of a random variable is a measure of how spread out the values are.

\* Linear regression: Linear regression is a statistical technique for predicting a dependent variable from one or more independent variables.

1. Which activity is performed in the Operationalize phase of the Data Analytics Lifecycle?

A. Transform existing variables

B. Try different analytical techniques

C. Define the process to maintain the model

D. Try different variables

SUBMIT YOUR CHOICE

The correct answer is  C. Define the process to maintain the model .

The operationalize phase of the data analytics lifecycle is the process of putting the model into production and making it available to users. This phase includes activities such as:

\* Deploying the model to a production environment

\* Defining the process to maintain the model

\* Monitoring the model for performance

\* Ensuring that the model is compliant with all relevant regulations

The process to maintain the model is important because it ensures that the model remains accurate and reliable over time. This process should include activities such as:

\* Regularly retraining the model on new data

\* Monitoring the model for performance degradation

\* Updating the model to reflect changes in the data

By defining a process to maintain the model, organizations can ensure that their models remain accurate and reliable, and that they continue to provide value to users.

The other options are not performed in the operationalize phase of the data analytics lifecycle:

\* Transform existing variables: This is an activity that is performed in the data preparation phase.

\* Try different analytical techniques: This is an activity that is performed in the model building phase.

\* Try different variables: This is an activity that is performed in the data exploration phase.

1. Which word or phrase completes the statement? Unix is to bash as Hadoop is to:

A. HDFS

B. Sqoop

C. Pig

D. NameNode

SUBMIT YOUR CHOICE

The answer is  C. Pig .

Unix is an operating system and bash is a command-line interpreter. Hadoop is a distributed computing framework and Pig is a high-level programming language for Hadoop.

Bash is used to interact with Unix and to execute commands. Pig is used to write programs that can be executed on Hadoop.

The analogy is that Unix is to bash as Hadoop is to Pig.

The other options are incorrect:

\* HDFS: HDFS is a distributed file system that is used by Hadoop. It is not a programming language.

\* Sqoop: Sqoop is a tool that is used to transfer data between Hadoop and relational databases. It is not a programming language.

\* NameNode: NameNode is a daemon in Hadoop that manages the filesystem namespace. It is not a programming language.

1. When creating a project sponsor presentation, what is the main objective?

A. Show how well the model will meet the SLA(service level agreement)

B. Show that you met the project goals

C. Clearly describe the methods and techniques used

D. Show how you met the project goals

SUBMIT YOUR CHOICE

The main objective of a project sponsor presentation is to  show how you met the project goals .

The project sponsor is the person who is responsible for overseeing the project and ensuring that it meets its goals. The project sponsor presentation is an opportunity for you to show the project sponsor that you have met the project goals and that the project was a success.

The presentation should include the following:

\* An overview of the project goals

\* A summary of the project's deliverables

\* An explanation of how the project met the project goals

\* A discussion of the challenges that were encountered and how they were overcome

\* A presentation of the project's findings and recommendations

The presentation should be clear, concise, and easy to understand. It should be tailored to the specific needs of the project sponsor.

Here are some additional tips for creating a successful project sponsor presentation:

\* Start by clearly defining the project goals. What did you want to achieve with the project?

\* Highlight the project's deliverables. What tangible products or services did you produce?

\* Explain how the project met the project goals. Use data and metrics to support your claims.

\* Discuss the challenges that were encountered and how they were overcome. This shows the project sponsor that you were able to think critically and solve problems.

\* Present the project's findings and recommendations. This is the most important part of the presentation. Make sure that your findings are clear and actionable.

\* Practice your presentation beforehand. This will help you to deliver it smoothly and confidently.

By following these tips, you can create a project sponsor presentation that will show how you met the project goals and that the project was a success.

1. For which class of problem is MapReduce most suitable?

A. Minimal result data

B. Simple marginalization tasks

C. Non overlapping queries

D. Embarrassingly parallel

SUBMIT YOUR CHOICE

The answer is  D. Embarrassingly parallel .

Embarrassingly parallel problems are those that can be easily split into independent tasks that can be executed in parallel. MapReduce is a good fit for embarrassingly parallel problems because it is designed to distribute tasks across a cluster of machines.

Simple marginalization tasks and non overlapping queries are also good fits for MapReduce, but they are not as good of a fit as embarrassingly parallel problems.

Minimal result data is not a good fit for MapReduce because MapReduce is designed to process large data sets.

Here are some examples of embarrassingly parallel problems that are good fits for MapReduce:

\* Counting the number of words in a document

\* Finding the top 10 most frequent words in a document

\* Calculating the average value of a set of numbers

MapReduce is a powerful tool for solving embarrassingly parallel problems. It is easy to use and can be scaled to handle large data sets. If you have a problem that is embarrassingly parallel, MapReduce is a good option to consider.

1. In which phase of the analytic lifecycle would you expect to spend most of the project time?

A. Operationalize

B. Communicate Results

C. Data preparation

D. Discovery

SUBMIT YOUR CHOICE

The answer is  C. Data preparation .

Data preparation is the most time-consuming phase of the analytic lifecycle. It is the process of cleaning, transforming, and formatting data so that it is ready to be analyzed.

Data preparation can be a very challenging task, especially if the data is dirty or incomplete. Data scientists often spend a significant amount of time cleaning and transforming data before they can even begin to analyze it.

Here are some of the tasks that are typically performed in the data preparation phase:

\* Cleaning data: This involves removing errors, duplicates, and outliers from the data.

\* Transforming data: This involves converting the data into a format that is compatible with the analysis tools that will be used.

\* Formatting data: This involves ensuring that the data is presented in a way that is easy to understand and interpret.

Data preparation is a critical phase of the analytic lifecycle. It is important to spend enough time on data preparation to ensure that the analysis is accurate and reliable.

The other phases of the analytic lifecycle are:

\* Discovery: This is the phase where the data scientist explores the data and identifies patterns and trends.

\* Model building: This is the phase where the data scientist builds a model to predict or explain the data.

\* Evaluate model: This is the phase where the data scientist evaluates the model to determine its accuracy and reliability.

\* Communicate results: This is the phase where the data scientist communicates the results of the analysis to stakeholders.

The operationalize and communicate results phases are typically less time-consuming than the data preparation phase.

1. Which functionality do regular expressions provide?

A. increased numerical precision

B. decreased processing complexity

C. text pattern matching

D. underflow prevention

SUBMIT YOUR CHOICE

The correct answer is  C. text pattern matching .

Regular expressions are a powerful tool for text pattern matching. They can be used to search for specific patterns in text, and to replace or extract text that matches a pattern.

Regular expressions are used in a variety of applications, including:

\* Data validation: Regular expressions can be used to validate data input, such as ensuring that email addresses are in the correct format.

\* Text search: Regular expressions can be used to search for specific patterns in text documents, such as finding all instances of a particular word or phrase.

\* Text processing: Regular expressions can be used to manipulate text, such as extracting phone numbers or email addresses from a document.

Regular expressions are not used for increased numerical precision, decreased processing complexity, or underflow prevention.

1. Since R factors are categorical variables, they are most closely related to which data classification level?

A. ratio

B. interval

C. ordinal

D. nominal

SUBMIT YOUR CHOICE

The correct answer is D. nominal 

R factors are categorical variables, which means that they can be divided into categories but not ordered. For example, the variable "color" can be divided into the categories "red", "blue", "green", etc., but there is no natural ordering to these categories.

The other data classification levels are:

` `Interval: Interval variables can be ordered and the difference between any two values is meaningful. For example, the variable "temperature" can be measured in degrees Celsius or Fahrenheit, and the difference between 20 degrees Celsius and 30 degrees Celsius is the same as the difference between 68 degrees Fahrenheit and 86 degrees Fahrenheit.

` `Ordinal: Ordinal variables can be ordered, but the difference between any two values is not meaningful. For example, the variable "rating" can be divided into the categories "good", "bad", and "average", but there is no natural way to quantify the difference between "good" and "bad".

` `Ratio: Ratio variables are like interval variables, but they have a true zero value. For example, the variable "weight" can be measured in pounds or kilograms, and 0 pounds or 0 kilograms is a true zero value.

Since R factors are categorical variables, they are most closely related to the nominal data classification level.

1. Which activity might be performed in the Operationalize phase of the Data Analytics Lifecycle?

A. Transform existing variables

B. Try different variables

C. Try different analytical techniques

D. Run a pilot

SUBMIT YOUR CHOICE

The correct answer is  D. Run a pilot .

The operationalize phase of the data analytics lifecycle is the phase where the data analytics solution is deployed into production and made available to users. This phase includes activities such as:

Deploying the data analytics solution to a production environment. 

Making the data analytics solution available to users. 

Monitoring the performance of the data analytics solution. 

Making changes to the data analytics solution as needed. 

Running a pilot is a common activity that is performed in the operationalize phase. A pilot is a small-scale deployment of the data analytics solution to a limited number of users. This allows the data analytics team to test the solution in a real-world environment and make sure that it is working as expected.

The other options are not typically performed in the operationalize phase. Option A, transforming existing variables, is typically performed in the data preparation phase. Option B, trying different variables, is typically performed in the model building phase. Option C, trying different analytical techniques, is typically performed in the model selection phase.

Therefore, the activity that might be performed in the operationalize phase of the Data Analytics Lifecycle is to run a pilot.

1. Since R factors are categorical variables, they are most closely related to which data classification level?

A. ratio

B. interval

C. ordinal

D. nominal

SUBMIT YOUR CHOICE

The correct answer is  D. nominal .

In R, factors are categorical variables that can take on a finite number of values. These values are often represented as strings, but they can also be represented as numbers.

Nominal variables are categorical variables that have no inherent order. For example, the color of a car is a nominal variable. It can take on a finite number of values, such as red, blue, and green. However, there is no inherent order to these values.

R factors are most closely related to nominal variables because they both have no inherent order. Interval and ratio variables have an inherent order, and ordinal variables have an order that is meaningful to the data.

Here is a table that summarizes the different data classification levels:

| Data Classification Level | Description |

\|---|---|

| Nominal | Categorical variables that have no inherent order. |

| Ordinal | Categorical variables that have an order that is meaningful to the data. |

| Interval | Numerical variables that have no natural zero point. |

| Ratio | Numerical variables that have a natural zero point. |

1. Which R data structure allows elements to have different data types?

A. List

B. Matrix

C. Array

D. Vector

SUBMIT YOUR CHOICE

The correct answer is  A. List .

In R, a list is a data structure that can hold elements of different data types. This means that a list can contain numbers, strings, factors, and even other lists.

Matrices, arrays, and vectors all have the same data type for all elements.

Here is an example of a list in R:

\```

list = list(1, "two", "three", c(4, 5, 6))

\```

This list contains four elements:

\* The first element is the number 1.

\* The second element is the string "two".

\* The third element is the factor "three".

\* The fourth element is the vector c(4, 5, 6).

1. Which R data structure allows elements to have different data types?

A. List

B. Matrix

C. Array

D. Vector

SUBMIT YOUR CHOICE

The correct answer is  A. List .

In R, a list is a data structure that can hold elements of  different data types . This means that a list can contain numbers, strings, factors, and even other lists.

Matrices, arrays, and vectors all have the same data type for all elements.

Here is an example of a list in R:

\```

list = list(1, "two", "three", c(4, 5, 6))

\```

This list contains four elements:

\* The first element is the number 1.

\* The second element is the string "two".

\* The third element is the factor "three".

\* The fourth element is the vector c(4, 5, 6).

Matrices, arrays, and vectors cannot contain elements of different data types. Matrices can only contain elements of the same data type, and arrays can only contain elements of the same data type in each dimension. Vectors can only contain elements of the same data type.

1. You are given 10, 000, 000 user profile pages of an online dating site in XML files, and they are stored in HDFS. You are assigned to divide the users into groups based on the content of their profiles. You have been instructed to try K-means clustering on this data. How should you proceed?

A. Divide the data into sets of 1,000 user profiles, and run K means clustering in RHadoop

iteratively.

B. Run Mapreduce to transform the data, and find relevant key value pairs

C. Partition the data by XML file size, and run K means clustering in each partition.

D. Run a Naive Bayes classification as a pre-processing step in HDFS

SUBMIT YOUR CHOICE

The correct answer is  A. Divide the data into sets of 1,000 user profiles, and run K means clustering in RHadoop iteratively. 

K-means clustering is an iterative algorithm that requires all of the data to be in memory at once. Since the data in this case is very large, it is not possible to load all of the data into memory at once.

The best way to proceed is to divide the data into sets of 1,000 user profiles, and run K-means clustering on each set iteratively. This will allow us to process the data in smaller chunks, and it will also allow us to parallelize the processing across multiple machines.

Here are the steps involved in this approach:

1\. Divide the data into sets of 1,000 user profiles.

2\. Load each set of data into memory.

3\. Run K-means clustering on each set of data.

4\. Repeat steps 2 and 3 until the clustering converges.

5\. Combine the results of the clustering from each set of data.

This approach will allow us to process the data in a reasonable amount of time, and it will also allow us to parallelize the processing across multiple machines.

The other options are not as efficient or scalable. Option B would require us to transform the data into key value pairs, which would be a time-consuming process. Option C would require us to partition the data by XML file size, which would not be efficient if the XML files are not of equal size. Option D would require us to run a Naive Bayes classification as a pre-processing step, which would also be a time-consuming process.

1. Data visualization is used in the final presentation of an analytics project. For what else is this technique commonly used?

A. ETLT

B. Model selection

C. Descriptive statistics

D. Data exploration

SUBMIT YOUR CHOICE

The correct answer is  D. Data exploration .

Data visualization is a powerful tool for exploring data. It can be used to identify patterns and trends in data, and to gain insights into the data. Data visualization is commonly used in the data exploration phase of an analytics project.

Data visualization can also be used in the final presentation of an analytics project. It can be used to communicate the results of the analysis to stakeholders in a way that is easy to understand and interpret.

However, data visualization is not used in ETLT, model selection, or descriptive statistics.

ETLT stands for Extract, Transform, Load and Model selection is the process of choosing the best model for a particular problem. Descriptive statistics is the process of summarizing data using numerical measures.

These techniques are not used to explore data. They are used to prepare data for analysis, to choose the best model for a particular problem, and to summarize data.

1. Data visualization is a powerful tool that can be used in a variety of ways. It is a valuable tool for data exploration, and it can also be used to communicate the results of the analysis to stakeholders. You are building a logistic regression model to predict whether a tax filer will be audited within the next two years. Your training set population is 1000 filers. The audit rate in your training data is 4.2%. What is the sum of the probabilities that the model assigns to all the filers in your training set that have been audited?

A. 42.0

B. 4.2

C. 0.42

D. 0.042

SUBMIT YOUR CHOICE

The correct answer is  D. 0.042 .

The sum of the probabilities that the model assigns to all the filers in your training set that have been audited is equal to the audit rate in your training data, which is 4.2%.

If there are 1000 filers in your training set and the audit rate is 4.2%, then 42 filers in your training set will be audited. The sum of the probabilities that the model assigns to these 42 filers is 0.042.

Here is the calculation:

\```

Number of audited filers = 1000 \* 0.042 = 42

Sum of probabilities = 0.042 \* 42 = 0.042

\```

The other options are incorrect. Option A is the total number of audited filers in the training set. Option B is the audit rate in the training set. Option C is the probability that a randomly selected filer in the training set will be audited.

1. Which word or phrase completes the statement? A Data Scientist would consider that a RDBMS is to a Table as R is to a

A. List

B. Data frame

C. Matrix

D. Array

SUBMIT YOUR CHOICE

The correct answer is  B. Data frame .

A RDBMS (Relational Database Management System) is a system for storing and managing data in tables. A table is a collection of related data organized into rows and columns.

R is a statistical programming language that is often used for data analysis. A data frame is a data structure in R that is similar to a table in a RDBMS. A data frame can store data in rows and columns, and it can be used to perform statistical analysis on data.

Here is a table of the similarities between a RDBMS table and an R data frame:

| Feature | RDBMS Table | R Data Frame |

\|---|---|---|

| Data structure | A collection of related data organized into rows and columns | A collection of related data organized into rows and columns |

| Data types | Can store data of different types | Can store data of different types |

| Indexing | Can be indexed by row and column | Can be indexed by row and column |

| Operations | Can perform basic operations on data, such as filtering, sorting, and grouping | Can perform basic operations on data, such as filtering, sorting, and grouping |

| Statistical analysis | Can be used to perform statistical analysis on data | Can be used to perform statistical analysis on data |

The other options are incorrect. A list, matrix, and array are all data structures in R, but they are not as similar to a table in a RDBMS as a data frame is.

1. Which key role for a successful analytic project can provide business domain expertise with a deep understanding of the data and key performance indicators?

A. Project Sponsor

B. Business Intelligence Analyst

C. Project Manager

D. Business User

SUBMIT YOUR CHOICE

The answer is  D. Business User .

Business users are the people who use the data and key performance indicators (KPIs) on a daily basis. They have a deep understanding of the business domain and the data that is used to measure performance.

Business users can provide valuable insights into the data and help to ensure that the analytics project is aligned with the business goals. They can also help to interpret the results of the analysis and communicate them to other stakeholders.

The other options are incorrect.

\* Project sponsors are responsible for providing funding and resources for the project. They do not have a deep understanding of the data or KPIs.

\* Business intelligence analysts are responsible for collecting, cleaning, and analyzing data. They do not have the same level of business domain expertise as business users.

\* Project managers are responsible for overseeing the project and ensuring that it is completed on time and within budget. They do not have a deep understanding of the data or KPIs.

Here are some of the responsibilities of a business user in an analytic project:

\* Provide business domain expertise and help to define the problem that the project is trying to solve.

\* Identify the data and KPIs that are needed to solve the problem.

\* Work with the business intelligence analyst to collect and clean the data.

\* Review the results of the analysis and provide feedback.

\* Communicate the results of the analysis to other stakeholders.

1. Consider a scale that has five (5) values that range from "not important" to "very important". Which data classification best describes this data?

A. Real

B. Ratio

C. Ordinal

D. Nominal

SUBMIT YOUR CHOICE

The correct answer is  C. Ordinal .

A scale that has five values that range from "not important" to "very important" is an ordinal scale. Ordinal scales are data classifications that have a natural order, but the difference between each value is not meaningful.

In this case, the values "not important", "somewhat important", "important", "very important", and "extremely important" are ordered from least important to most important. However, the difference between each value is not meaningful. For example, the difference between "important" and "very important" is not the same as the difference between "somewhat important" and "important".

The other options are incorrect.

\* Real scales are data classifications that have a natural order and the difference between each value is meaningful. For example, the temperature scale is a real scale.

\* Ratio scales are data classifications that have a natural order, the difference between each value is meaningful, and there is a true zero point. For example, the distance scale is a ratio scale.

\* Nominal scales are data classifications that do not have a natural order. For example, the color of a car is a nominal scale.

1. You are studying the behavior of a population, and you are provided with multidimensional data at the individual level. You have identified four specific individuals who are valuable to your study, and would like to find all users who are most similar to each individual. Which algorithm is the most appropriate for this study?

A. Association rules

B. Decision trees

C. Linear regression

D. K means clustering

SUBMIT YOUR CHOICE

The answer is  D. K means clustering .

K means clustering is a unsupervised learning algorithm that can be used to group similar data points together. In this case, you are given multidimensional data at the individual level, and you want to find all users who are most similar to each individual. This is a perfect use case for k means clustering.

K means clustering works by first choosing a random set of k points in the data set. These points are called centroids. The algorithm then assigns each data point to the closest centroid. The centroids are then updated, and the process is repeated until the centroids no longer change.

In this case, you can choose k to be equal to the number of individuals you have identified as valuable to your study. The algorithm will then find k clusters, and each cluster will contain users who are most similar to one of the individuals you have identified.

The other options are not as appropriate for this study.

\* Association rules are used to find relationships between items in a data set. This is not what you are trying to do in this case. You are trying to find users who are similar to each other.

\* Decision trees are used to make predictions based on data. This is not what you are trying to do in this case. You are simply trying to find users who are similar to each other.

\* Linear regression is used to predict a continuous value based on a set of independent variables. This is not what you are trying to do in this case. You are simply trying to find users who are similar to each other.

1. You have been assigned to do a study of the daily revenue effect of a pricing model of online transactions. When have you completed the analytics lifecycle?

A. You have a completely developed model

O based on both a sample of the data and the entire set of data available

B. You have a completely developed model and the result have shown statistically acceptable result

C. You have presented the results of the model to both the internal analytics team and the business owner of the project

D. None

E. You have written documentation and the code has been handed off to the Data Base Administrator and business operations

SUBMIT YOUR CHOICE

The correct answer is  C. You have presented the results of the model to both the internal analytics team and the business owner of the project .

The analytics lifecycle is a process that data analysts use to go from understanding the business problem to delivering insights that can be used to make decisions. The lifecycle typically includes the following phases:

1\.  Define the problem. The first step is to define the business problem that you are trying to solve. This involves understanding the current state of the business, identifying the key performance indicators (KPIs) that you want to improve, and defining the target audience for your insights.

2\.  Gather data. Once you have defined the problem, you need to gather the data that you need to solve it. This data can come from a variety of sources, such as transactional data, customer surveys, and social media data.

3\.  Clean and prepare the data. Once you have gathered the data, you need to clean and prepare it for analysis. This involves removing any errors or outliers from the data, and transforming the data into a format that can be used by your analytics tools.

4\.  Build the model. The next step is to build the model that will be used to analyze the data. This model can be a statistical model, a machine learning model, or a combination of both.

5\.  Evaluate the model. Once you have built the model, you need to evaluate it to make sure that it is accurate and reliable. This involves testing the model on a sample of the data and comparing the results to the actual results.

6\.  Deploy the model. Once you are satisfied with the model, you can deploy it to production. This means making the model available to users so that they can use it to make decisions.

7\.  Communicate the results. The final step is to communicate the results of the model to the business stakeholders. This involves explaining the model, the results, and the implications of the results.

In the case of the pricing model study, the analytics lifecycle would be completed when the results of the model have been presented to both the internal analytics team and the business owner of the project. This is because the business owner is the ultimate decision-maker and they need to be confident in the results of the model before it can be deployed to production.

The other options are incorrect because:

\* Option A is incorrect because the model is not complete until it has been evaluated and deployed to production.

\* Option B is incorrect because the results of the model need to be communicated to the business stakeholders before the analytics lifecycle is complete.

\* Option D is incorrect because the analytics lifecycle is not complete until the results of the model have been communicated to the business stakeholders.

\* Option E is incorrect because the code is not the only deliverable of the analytics lifecycle. The results of the model also need to be communicated to the business stakeholders.The Marketing department of your company wishes to track opinion on a new product that was recently introduced. Marketing would like to know how many positive and negative reviews are appearing over a given period and potentially retrieve each review for more in depth insight. They have identified several popular product review blogs that historically have published thousands of user reviews of your companys products. 

1. You have been asked to provide the desired analysis. You examine the RSS feeds for each blog and determine which fields are relevant. You then craft a regular expression to match your new products name and extract the relevant text from each matching review. What is the next step you should take?

A. Read the extracted text for each review and manually tabulate the results

B. Use the extracted text and your regular expression to perform a sentiment analysis based on mentions of the new product

C. Convert the extracted text into a suitable document representation and index into a review corpus

D. Group the reviews using Naive Bayesian classification

SUBMIT YOUR CHOICE

The next step you should take is to  use the extracted text and your regular expression to perform a sentiment analysis based on mentions of the new product .

Sentiment analysis is the process of determining the emotional tone of a piece of text. In this case, you would use sentiment analysis to determine if the reviews of your new product are positive or negative.

You can use your regular expression to extract the relevant text from each review. This text will include any mentions of your new product. You can then use a sentiment analysis tool to determine the sentiment of the text.

This will allow you to determine how many positive and negative reviews are appearing over a given period. You can also retrieve each review for more in depth insight.

The other options are not as appropriate in this case.

\* Reading the extracted text for each review and manually tabulating the results would be a very time-consuming and error-prone process.

\* Converting the extracted text into a suitable document representation and indexing into a review corpus would be useful for further analysis, but it is not the next step in this process.

\* Group the reviews using Naive Bayesian classification is a more advanced approach to sentiment analysis, but it is not necessary in this case.

1. In the MapReduce framework, what is the purpose of the Reduce function?

A. it breaks the input into smaller components and distributes to other nodes in the cluster 

B. It aggregates the result of the Map function and generates processed output

C. It writes the output of the Map function to storage

D. It distributes the input to multiple nodes for processing

SUBMIT YOUR CHOICE

The correct answer is  B. It aggregates the result of the Map function and generates processed output .

The MapReduce framework is a programming model and an associated implementation for processing and generating large data sets. It is designed to scale up from single servers to thousands of machines, each of which can have multiple processors.

The MapReduce framework works by dividing the input data into smaller pieces, called \*splits\*. These splits are then distributed to different nodes in the cluster, where they are processed by the \*Map\* function. The Map function takes a split as input and produces a set of intermediate key-value pairs as output.

The intermediate key-value pairs are then shuffled and grouped together based on their keys. The Reduce function then takes a set of intermediate key-value pairs as input and produces a single output value for each key.

The Reduce function is responsible for aggregating the results of the Map function and generating processed output. This output can then be written to a file or stored in a database.

The other options are incorrect.

\* Option A is the purpose of the \*Shuffle\* phase.

\* Option C is the purpose of the \*Output\* phase.

\* Option D is the purpose of the \*Input\* phase.

1. You have been assigned to run a logistic regression model for each of 100

countries, and all the data is currently stored in a PostgreSQL database. Which tool/library would you use to produce these models with the least effort?

A. Mahout

B. HBase

C. Rstudio

D. MADlib

SUBMIT YOUR CHOICE

The correct answer is  D. MADlib .

MADlib is an open-source library for statistical modeling in PostgreSQL. It provides a variety of statistical functions, including logistic regression.

MADlib is designed to be easy to use, and it can be used to run logistic regression models for each of 100 countries with minimal effort.

The other options are not as appropriate for this task.

\* Mahout is a machine learning library that can be used to run logistic regression models. However, it is not as easy to use as MADlib, and it would require more effort to run logistic regression models for each of 100 countries.

\* HBase is a NoSQL database that can be used to store large amounts of data. However, it is not a statistical database, and it would not be appropriate for running logistic regression models.

\* Rstudio is an IDE for R, a statistical programming language. However, Rstudio would not be the most efficient way to run logistic regression models for each of 100 countries.

1. You have been assigned to do a study of the daily revenue effect of a pricing model of online transactions. You have tested all the theoretical models in the previous model planning stage, and all tests have yielded statistically insignificant results. What is your next step?

A. Modify samples used by the models and iterate until a significant result occurs

B. Move forward on the model with the highest significance scores relative to the others

C. Report that the results are insignificant, and reevaluate the original business question 

D. Run all the models again against a larger sample leveraging more historical data.

SUBMIT YOUR CHOICE

The correct answer is  C. Report that the results are insignificant, and reevaluate the original business question .

If all the models have yielded statistically insignificant results, then it means that there is not enough evidence to support the claim that the pricing model has a significant effect on daily revenue. In this case, the next step should be to report the results to the stakeholders and reevaluate the original business question.

It is possible that the original business question was flawed, or that the data was not sufficient to answer the question. It is also possible that the models were not correctly specified or that the data was not properly cleaned.

Once the results have been reported and the original business question has been reevaluated, the next step may be to collect more data or to use a different set of models. It is also possible that the business question can be answered with a different type of analysis.

The other options are not as appropriate in this case.

\* Option A would be a waste of time and resources. If all the models have yielded statistically insignificant results, then there is no point in modifying the samples and iterating until a significant result occurs.

\* Option B would be premature. There is no need to move forward with a model that has not been shown to be statistically significant.

\* Option D would be a good option if the data set is small. However, if the data set is large enough, then it is more efficient to run the models once with a large sample than to run them multiple times with smaller samples.

1. Your organization has a website where visitors randomly receive one of two coupons. It is also possible that visitors to the website will not receive a coupon. You have been asked to determine if offering a coupon to visitors to your website has any impact on their purchase decision. Which analysis method should you use?

A. Association rules

B. One way ANOVA

C. Student T Test

D. K means clustering

SUBMIT YOUR CHOICE

The correct answer is  C. Student T Test .

A Student T Test is a statistical test that is used to compare the means of two groups. In this case, you have two groups of visitors to your website: those who received a coupon and those who did not receive a coupon. You want to know if there is a statistically significant difference in the purchase decision between these two groups.

A One way ANOVA could also be used to answer this question. However, a Student T Test is more appropriate because you only have two groups. A One way ANOVA is used to compare the means of three or more groups.

Association rules and K means clustering are not appropriate for this question. Association rules are used to find relationships between items in a data set. K means clustering is used to group similar data points together. Neither of these methods is appropriate for comparing the means of two groups.

1. You have completed your model and are handing it off to be deployed in production. What should you deliver to the production team, along with your commented code?

A. The production team are technical and they need to understand how the processes that they support work so give them the same presentation that you prepared for the analyst 

B. The production team supports the processes that run the organization, and they need context to understand how you model interacts with the processes they already support. Give them the executive summary.

C. The production team needs to understand how you model with interact with the process they already support. Give them documentation on expected model inputs and outputs and guidance on error handling

D. The production team supports the processes that run the organization and they need context to understand how your model interacts with the processes they alredy support. Give them the same presentation that you prepared for the project sponsor.

SUBMIT YOUR CHOICE

The correct answer is  C. The production team needs to understand how your model will interact with the process they already support. Give them documentation on expected model inputs and outputs and guidance on error handling .

The production team is responsible for deploying and maintaining your model in production. They need to understand how your model will interact with the existing processes in the organization. This includes understanding the expected model inputs and outputs, as well as how to handle errors.

You should provide the production team with documentation that explains these things in detail. The documentation should be clear and concise, and it should be easy for the production team to understand.

You should also provide the production team with your commented code. This will allow them to understand how your model works in detail. However, you should not expect the production team to read and understand your code. The documentation is more important for them.

The executive summary and the presentation that you prepared for the project sponsor are not as important for the production team. These documents are more high-level and they do not provide the detail that the production team needs.

Here is a list of the things that you should deliver to the production team:

\* Documentation on expected model inputs and outputs

\* Guidance on error handling

\* Your commented code

1. You should also be available to answer questions from the production team. They may have questions about your model or about the documentation that you have provided. It is important to be responsive to their questions so that they can deploy your model in production successfully.Consider these itemsets:

(hat, scarf, coat)

(hat, scarf, coat, gloves)

(hat, scarf, gloves)

(hat, gloves)

(scarf, coat, gloves)

What is the confidence of the rule (hat, scarf) -> gloves?

A. 66%

B. 60%

C. 40%

D. 50%e

SUBMIT YOUR CHOICE

The correct answer is  C. 40% .

The confidence of a rule is the percentage of times that the consequent of the rule is true, given that the antecedent of the rule is true. In this case, the antecedent of the rule is (hat, scarf) and the consequent of the rule is gloves.

There are 4 itemsets that contain (hat, scarf) and 1 of these itemsets also contains gloves. So, the confidence of the rule is 1/4 = 40%.

Here is a table that shows the itemsets and the number of times that they appear in the data set:

Itemset | Count

\------- | --------

(hat, scarf, coat) | 1

(hat, scarf, coat, gloves) | 1

(hat, scarf, gloves) | 1

(hat, gloves) | 1

(scarf, coat, gloves) | 1

1. The confidence of the rule (hat, scarf) -> gloves is 1/4 = 40%.You are asked to create a model to predict the total number of monthly subscribers for a specific magazine. You are provided with 1 years worth of subscription and payment data, user demographic data, and 10 years worth of content of the magazine (articles and pictures). Which algorithm is the most appropriate for building a predictive model for subscribers?

A. Linear regression

B. Decision trees

C. TF IDF

D. Logistic regression

SUBMIT YOUR CHOICE

The most appropriate algorithm for building a predictive model for subscribers is  Linear regression .

Linear regression is a statistical model that predicts a continuous value based on a set of independent variables. In this case, the independent variables would be the subscription and payment data, user demographic data, and the content of the magazine. The dependent variable would be the number of monthly subscribers.

Linear regression is a good choice for this problem because it is a simple and relatively easy to understand model. It is also a very versatile model that can be used to predict a wide variety of continuous values.

Decision trees and logistic regression are also good choices for this problem. However, they are more complex than linear regression and they may not be necessary for this problem.

TF-IDF is a text mining technique that is used to find the most important terms in a document. It is not a good choice for this problem because it is not designed to predict continuous values.

Here is a table that summarizes the pros and cons of each algorithm:

Algorithm | Pros | Cons

\------- | -------- | --------

Linear regression | Simple, easy to understand, versatile | Not as accurate as decision trees or logistic regression

Decision trees | Accurate, can handle complex relationships | Complex, difficult to interpret

Logistic regression | Accurate, can handle binary data | Not as versatile as linear regression

TF-IDF | Fast, easy to implement | Not designed for predicting continuous values

1. While having a discussion with your colleague, this person mentions that they want to perform Kmeans clustering on text file data stored in HDFS. Which tool would you recommend to this colleague?

A. Sqoop

B. HBase

C. Mahout

D. Scribe

SUBMIT YOUR CHOICE

The tool that I would recommend to my colleague is  Mahout .

Mahout is an open-source machine learning library for Hadoop. It includes a variety of clustering algorithms, including kmeans. Mahout is designed to be scalable and efficient, making it a good choice for clustering large datasets.

Sqoop is a tool for transferring data between Hadoop and relational databases. It is not a good choice for clustering text file data because it is not designed for machine learning tasks.

HBase is a NoSQL database that is designed for storing large amounts of structured data. It is not a good choice for clustering text file data because it is not designed for machine learning tasks.

Scribe is a log aggregation system that is designed to collect and store log data. It is not a good choice for clustering text file data because it is not designed for machine learning tasks.

Here is a table that summarizes the pros and cons of each tool:

Tool | Pros | Cons

\------- | -------- | --------

Mahout | Scalable, efficient, includes kmeans clustering algorithm | Can be complex to use

Sqoop | Transfers data between Hadoop and relational databases | Not designed for machine learning tasks

HBase | Stores large amounts of structured data | Not designed for machine learning tasks

Scribe | Collects and stores log data | Not designed for machine learning tasks

1. Which word or phrase completes the statement? Emphasis color is to standard color as

A. Main message is to context

B. Pie chart is to proportions

C. Main message is to key findings

D. Frequent item set is to item

SUBMIT YOUR CHOICE

The answer should be the pair of words that has the same relationship as emphasis color and standard color.

Of the above choices, only  main message is to context has the same relationship as emphasis color and standard color.

\* Emphasis color is used to highlight the most important information in a visualization.

\* Standard color is used for the rest of the information in the visualization.

\* Main message is the most important information in a visualization.

\* Context is the rest of the information in the visualization.

Therefore, the answer is  main message is to context .

1. You are analyzing data in order to build a classifier model. You discover non-linear data and discontinuities that will affect the model. Which analytical method would you recommend?

A. Decision Tree

B. Logistic Regression

C. Linear Regression

D. ARIMA

SUBMIT YOUR CHOICE

The correct answer is  A. Decision Tree .

Decision trees are a type of supervised machine learning algorithm that can be used for classification and regression tasks. They are particularly well-suited for data that is non-linear and has discontinuities.

Linear regression and logistic regression are also supervised machine learning algorithms, but they are not as well-suited for data that is non-linear and has discontinuities. ARIMA is a time series forecasting algorithm that is not used for classification tasks.

Here is a brief overview of how decision trees work:

1\. The decision tree starts with a root node, which represents the entire dataset.

2\. The root node is then split into two child nodes, based on a decision rule.

3\. This process is repeated recursively for each child node, until the entire dataset is classified.

4\. The decision rules are created by finding the best way to split the data into two groups, such that the groups are as homogeneous as possible.

Decision trees are a powerful tool for classification tasks, especially when the data is non-linear and has discontinuities. They are also relatively easy to understand and interpret, which makes them a good choice for business applications.

1. Imagine you are trying to hire a Data Scientist for your team. In addition to technical ability and quantitative background, which additional essential trait would you look for in people applying for this position?

A. Well Organized

B. Scientific background

C. Domain expertise

D. Communication skill

SUBMIT YOUR CHOICE

The answer is  D. Communication skill .

In addition to technical ability and quantitative background, communication skill is an essential trait for a Data Scientist. Data Scientists need to be able to communicate their findings to a variety of stakeholders, including business leaders, technical staff, and the general public. They need to be able to explain complex concepts in a clear and concise way, and they need to be able to answer questions about their work.

Well-organized and scientific background are also important traits for a Data Scientist, but they are not as essential as communication skill. A Data Scientist can be well-organized and have a scientific background, but if they cannot communicate their findings effectively, they will not be able to be successful in their role.

Domain expertise is also a valuable trait for a Data Scientist, but it is not essential. A Data Scientist can learn domain expertise on the job, but they need to have strong communication skills from the start.

Here are some reasons why communication skill is an essential trait for a Data Scientist:

\* Data Scientists need to be able to communicate their findings to a variety of stakeholders, including business leaders, technical staff, and the general public.

\* They need to be able to explain complex concepts in a clear and concise way, and they need to be able to answer questions about their work.

\* Data Scientists need to be able to collaborate with other team members, including engineers, product managers, and marketing professionals.

\* They need to be able to communicate the value of data science to stakeholders and convince them to adopt data-driven decision making.

1. In the MapReduce framework, what is the purpose of the Map Function?

A. It sorts the results of the Reduce function

B. It breaks the input into smaller components and distributes to other nodes in the cluster

C. It processes the input and generates key value pairs

D. It collects the output of the Reduce function

SUBMIT YOUR CHOICE

The purpose of the Map Function in the MapReduce framework is to  process the input and generate key value pairs . The Map Function is responsible for reading the input data, splitting it into smaller pieces, and then processing each piece of data. For each piece of data, the Map Function will generate a key value pair. The key will be a unique identifier for the piece of data, and the value will be the result of processing the data.

The Map Function is a very powerful tool that can be used to process large amounts of data. It is used in a variety of data science applications, including web analytics, social media analysis, and machine learning.

Here are some of the benefits of using the Map Function:

\* It is very scalable. The Map Function can be used to process large amounts of data in parallel.

\* It is very efficient. The Map Function can be used to process data quickly and efficiently.

\* It is very flexible. The Map Function can be used to process a variety of data types.

1. What describes a true limitation of Logistic Regression method?

A. It does not handle redundant variables well

B. It does not handle correlated variables well.

C. It does not have explanatory values

D. It does not handle missing values well.

SUBMIT YOUR CHOICE

The answer is  B. It does not handle correlated variables well. 

Logistic regression is a statistical model that is used to predict a binary outcome. It is a very powerful tool, but it has some limitations. One of its limitations is that it does not handle correlated variables well.

When two or more variables are correlated, it means that they are related to each other. This can cause problems for logistic regression because it can make the model unstable. The model may not be able to predict the outcome accurately if the variables are correlated.

Here are some other limitations of logistic regression:

\* It does not handle missing values well.

\* It does not handle outliers well.

\* It can be sensitive to the choice of hyperparameters.

\* It can be difficult to interpret.

Despite these limitations, logistic regression is a powerful tool that can be used to solve a variety of problems. It is important to be aware of its limitations, but it can still be a valuable tool for data scientists.

1. Which of the following is an example of quasi-structured data?

A. OLTP

B. Customer record table

C. OLAP

D. Clickstream data

SUBMIT YOUR CHOICE

The answer is  D. Clickstream data .

Quasi-structured data is a type of data that has some structure, but not as much as structured data. It is often found in log files and other types of data that are generated by applications. Clickstream data is a good example of quasi-structured data because it contains information about the user's actions on a website, but it is not in a fixed format.

OLTP (Online Transaction Processing) data is a type of structured data that is used to store data about transactions. Customer record tables are a type of structured data that is used to store information about customers. OLAP (Online Analytical Processing) data is a type of structured data that is used to analyze data.

Here are some of the characteristics of quasi-structured data:

\* It may have a fixed schema, but the schema may not be enforced.

\* It may contain missing values.

\* It may contain duplicate data.

\* It may be in a variety of formats, such as XML, JSON, or CSV.

Quasi-structured data can be difficult to process and analyze, but it can be very valuable for understanding user behavior and making business decisions.

1. While having a discussion with your colleague, this person mentions that they want to perform Kmeans clustering on text file data stored in HDFS. Which tool would you recommend to this colleague?

A. HBase

B. Scribe

C. Sqoop

D. Mahout

SUBMIT YOUR CHOICE

I would recommend  Mahout to my colleague.

Mahout is an open-source machine learning library for Hadoop. It includes a variety of clustering algorithms, including kmeans. Mahout is designed to be scalable and efficient, making it a good choice for clustering large datasets.

HBase is a NoSQL database that is designed for storing large amounts of structured data. It is not a good choice for clustering text file data because it is not designed for machine learning tasks.

Scribe is a log aggregation system that is designed to collect and store log data. It is not a good choice for clustering text file data because it is not designed for machine learning tasks.

Sqoop is a tool for transferring data between Hadoop and relational databases. It is not a good choice for clustering text file data because it is not designed for machine learning tasks.

Here is a table that summarizes the pros and cons of each tool:

Tool | Pros | Cons

\------- | -------- | --------

Mahout | Scalable, efficient, includes kmeans clustering algorithm | Can be complex to use

HBase | Stores large amounts of structured data | Not designed for machine learning tasks

Scribe | Collects and stores log data | Not designed for machine learning tasks

Sqoop | Transfers data between Hadoop and relational databases | Not designed for machine learning tasks

1. You are provided four different datasets. Initial analysis on these datasets show that they have identical mean, variance and correlation values. What should your next step in the analysis be?

A. Visualize the data to further explore the characteristics of each data set

B. Combine the data from all four of the datasets and begin planning and building a model

C. Recalculate the descriptive statistics since they are unlikely to be identical for each dataset 

D. Select one of the four datasets and begin planning and building a model

SUBMIT YOUR CHOICE

The correct answer is  A. Visualize the data to further explore the characteristics of each data set .

If the mean, variance, and correlation values of four different datasets are identical, then it means that these datasets are statistically the same. However, this does not mean that the datasets are identical. The datasets may still have different distributions, different outliers, and different patterns.

Visualizing the data can help us to explore the characteristics of each dataset and to identify any differences between the datasets. This information can be used to select the best dataset for modeling and to build a more accurate model.

Combining the data from all four datasets and beginning to plan and build a model is not a good idea. If the datasets are statistically the same, then combining them will not improve the model. In fact, it may make the model worse by introducing noise and bias.

Recalculating the descriptive statistics is also not a good idea. If the mean, variance, and correlation values were calculated correctly the first time, then there is no need to recalculate them.

Selecting one of the four datasets and beginning to plan and build a model is also not a good idea. Without visualizing the data, we do not know which dataset is the best for modeling.

Therefore, the best next step in the analysis is to visualize the data to further explore the characteristics of each data set.

1. What describes a true property of Logistic Regression method?

A. It is robust with redundant variables and correlated variables

B. It works well with variables that affect the outcome in a discontinous way

C. It handles missing values well

D. It works well with discrete variables that have many distinct values

SUBMIT YOUR CHOICE

The correct answer is  A. It is robust with redundant variables and correlated variables .

Logistic regression is a linear model that is used to predict a binary outcome. It is a very robust model and it can handle redundant variables and correlated variables well. This is because logistic regression uses a technique called regularization to shrink the coefficients of the model. Regularization helps to prevent the model from overfitting the data.

Logistic regression does not work well with variables that affect the outcome in a discontinuous way. For example, logistic regression cannot be used to predict whether a customer will click on an ad or not. This is because the outcome of whether a customer clicks on an ad is a discrete variable with two possible values (click or no click).

Logistic regression also does not handle missing values well. If a variable has missing values, then the logistic regression model will not be able to use that variable. This can reduce the accuracy of the model.

Logistic regression works well with discrete variables that have a few distinct values. For example, logistic regression can be used to predict whether a customer will churn (leave the company) or not. This is because the outcome of whether a customer churns is a discrete variable with two possible values (churn or no churn).

Here is a table that summarizes the properties of logistic regression:

Property | Description

\------- | --------

Robust with redundant variables and correlated variables | Logistic regression is a linear model and it can handle redundant variables and correlated variables well.

Works well with discrete variables that have a few distinct values | Logistic regression works well with discrete variables that have a few distinct values.

Does not work well with variables that affect the outcome in a discontinuous way | Logistic regression does not work well with variables that affect the outcome in a discontinuous way.

Does not handle missing values well | Logistic regression does not handle missing values well.

1. What describes a true property of Logistic Regression method?

A. It is robust with redundant variables and correlated variables

B. It works well with variables that affect the outcome in a discontinous way

C. It handles missing values well

D. It works well with discrete variables that have many distinct values

SUBMIT YOUR CHOICE

The answer is  A. It is robust with redundant variables and correlated variables .

Logistic regression is a linear model that is used to predict a binary outcome. It is a very robust model and it can handle redundant variables and correlated variables well. This is because logistic regression uses a technique called regularization to shrink the coefficients of the model. Regularization helps to prevent the model from overfitting the data.

Logistic regression does not work well with variables that affect the outcome in a discontinuous way. For example, logistic regression cannot be used to predict whether a customer will click on an ad or not. This is because the outcome of whether a customer clicks on an ad is a discrete variable with two possible values (click or no click).

Logistic regression also does not handle missing values well. If a variable has missing values, then the logistic regression model will not be able to use that variable. This can reduce the accuracy of the model.

Logistic regression works well with discrete variables that have a few distinct values. For example, logistic regression can be used to predict whether a customer will churn (leave the company) or not. This is because the outcome of whether a customer churns is a discrete variable with two possible values (churn or no churn).

However, logistic regression can also work well with discrete variables that have many distinct values. For example, logistic regression can be used to predict the category of a product that a customer will buy. This is because the outcome of the category of a product that a customer will buy is a discrete variable with many possible values.

Here is a table that summarizes the properties of logistic regression:

Property | Description

\------- | --------

Robust with redundant variables and correlated variables | Logistic regression is a linear model and it can handle redundant variables and correlated variables well.

Works well with discrete variables that have a few distinct values | Logistic regression works well with discrete variables that have a few distinct values.

Works well with discrete variables that have many distinct values | Logistic regression can also work well with discrete variables that have many distinct values.

Does not work well with variables that affect the outcome in a discontinuous way | Logistic regression does not work well with variables that affect the outcome in a discontinuous way.

Does not handle missing values well | Logistic regression does not handle missing values well.

1. How are window functions different from regular aggregate functions?

A. Rows are grouped into an output rows and the window function can access more than the current row.

B. Rows retain their seperate identities and the

Owindow function can access more than the

current row

C. Rows are grouped into an output row and the window function can only access the current row. 

D. Rows retain their seperate identities and the window function can only access the current row.

SUBMIT YOUR CHOICE

The answer is  B. Rows retain their seperate identities and the window function can access more than the current row .

Window functions are similar to aggregate functions in that they operate on a set of rows and return a single value. However, window functions differ from aggregate functions in two key ways:

Rows retain their separate identities. This means that each row in the window is still accessible by its original index.

Window functions can access more than the current row. This means that window functions can use information from other rows in the window to calculate their output value.

For example, the `RANK()` window function returns the rank of each row in the window, based on the values of a specified column. The `RANK()` function can access the current row and all of the rows before it in the window to calculate the rank.

In contrast, aggregate functions only operate on the current row. This means that aggregate functions cannot use information from other rows in the window to calculate their output value.

Here is a table that summarizes the differences between window functions and aggregate functions:

| Feature | Window Function | Aggregate Function |

\|---|---|---|

| Rows retain their separate identities | Yes | No |

| Can access more than the current row | Yes | No |

| Returns a single value | Yes | Yes |

| Can be used to calculate running totals, averages, and other aggregate statistics | Yes | Yes |

| Can be used to calculate ranks, percentiles, and other window-specific statistics | Yes | No |

1. You have run the association rules algorithm on your data set, and the two |rules {banana, apple} => {grape} and {apple, | orange}=> {grape) have been found to be relevant. What else must be true?

A. {banana, apple} => {orange} must be a relevant rule

B. {banana, apple, grape, orange} must be a frequent itemset

C. {grape) => {banana, apple} must be a relevant rule

D. {grape,apple,orange} must be a frequent itemset.

SUBMIT YOUR CHOICE

The answer must be  D. {grape,apple,orange} must be a frequent itemset .

Association rule mining is a process of discovering interesting relations between sets of items in large databases. It is a common technique used in market basket analysis, where it is used to find associations between products that are frequently bought together.

The association rule algorithm works by first finding frequent itemsets. A frequent itemset is a set of items that appear together in a transaction more often than expected by chance. Once the frequent itemsets have been found, the algorithm then tries to find association rules between them.

An association rule is a rule of the form X => Y, where X and Y are sets of items. The rule says that if X appears in a transaction, then Y is likely to appear in the same transaction.

The two rules that you have been given, {banana, apple} => {grape} and {apple, orange} => {grape}, are both association rules. They both say that if X appears in a transaction, then Y is likely to appear in the same transaction.

In order for these rules to be relevant, the itemsets X and Y must be frequent itemsets. In other words, X and Y must appear together in a transaction more often than expected by chance.

The itemset {grape,apple,orange} is a superset of both {banana, apple} and {apple, orange}. This means that if {banana, apple} and {apple, orange} are frequent itemsets, then {grape,apple,orange} must also be a frequent itemset.

Therefore, the answer must be  D. {grape,apple,orange} must be a frequent itemset .

1. Data visualization is used in the final presentation of an analytics project. For what else is this technique commonly used?

A. ETLT

B. Assessing data quality

C. Descriptive statistics

D. Model Selection

SUBMIT YOUR CHOICE

The correct answer is  B. Assessing data quality .

Data visualization is a powerful tool that can be used to assess data quality in a number of ways. For example, you can use data visualization to:

\* Identify outliers and anomalies in the data.

\* Explore the distribution of the data.

\* Check for missing values and inconsistencies in the data.

\* Understand the relationships between different variables in the data.

Data visualization can also be used to communicate the results of an analytics project to stakeholders. This can be helpful in getting buy-in for your project and ensuring that the results are understood.

The other options are incorrect.

\* Option A is incorrect because ETLT is a process for extracting, transforming, and loading data. It is not a technique for assessing data quality.

\* Option C is incorrect because descriptive statistics are used to summarize data. They are not a technique for assessing data quality.

\* Option D is incorrect because model selection is the process of choosing the best model for a given problem. It is not a technique for assessing data quality.

1. You submit a MapReduce job to a Hadoop cluster and notice that although the job was successfully submitted, it is not completing. What should you do?

A. Ensure that the TaskTracker is running.

B. Ensure that a DataNode is running

C. Ensure that the Job Tracker is running D. Ensure that the NameNode is running

SUBMIT YOUR CHOICE

The correct answer is  C. Ensure that the Job Tracker is running .

The Job Tracker is the master node in a Hadoop cluster. It is responsible for scheduling MapReduce jobs and tracking their progress. If the Job Tracker is not running, then no MapReduce jobs will be able to complete.

The NameNode and DataNodes are also important components of a Hadoop cluster, but they are not responsible for scheduling or tracking MapReduce jobs. The NameNode is responsible for storing the filesystem metadata, and the DataNodes are responsible for storing the actual data.

If you have submitted a MapReduce job to a Hadoop cluster and it is not completing, the first thing you should do is check to make sure that the Job Tracker is running. You can do this by checking the Hadoop logs or by running the `jps` command on the master node.

If the Job Tracker is not running, then you will need to start it up. Once the Job Tracker is running, you should be able to submit your MapReduce job again and it should complete successfully.

Here are some other things you can check if your MapReduce job is not completing:

\* Make sure that the input data is available.

\* Make sure that the MapReduce job has enough resources (CPU, memory, and storage).

\* Make sure that there are no errors in the MapReduce job configuration.

\* Make sure that the Hadoop cluster is healthy and there are no network problems.

If you have checked all of these things and your MapReduce job is still not completing, you may need to contact your Hadoop administrator for help. 

1. Which word or phrase completes the statement? Structured data is to OLAP data as quasi structured data is to

A. XML data

B. Text documents

C. Clickstream data

D. Image files

SUBMIT YOUR CHOICE

The answer is  B. Text documents .

Structured data is data that is organized in a specific way, such as in a table. OLAP data is a type of structured data that is used for online analytical processing. Quasi-structured data is data that has some structure, but not as much as structured data. Text documents are a type of quasi-structured data.

Here is a table that summarizes the three types of data:

| Data Type | Description | Example |

\|---|---|---|

| Structured data | Data that is organized in a specific way, such as in a table. | Customer records, product inventory, financial transactions |

| OLAP data | A type of structured data that is used for online analytical processing. | Sales data, customer demographics, product usage data |

| Quasi-structured data | Data that has some structure, but not as much as structured data. | Text documents, email messages, social media posts |

1. When would you use a Wilcoxson Rank Sum test?

A. When you cannot make an assumption about the distribution of the populations

B. When the populations represent the sums of other values

C. When the data cannot easily be sorted

D. When the data easily be sorted

SUBMIT YOUR CHOICE

The answer is  D. When the data easily be sorted .

The Wilcoxon Rank Sum test is a non-parametric test that can be used to compare two independent samples when the data cannot be assumed to be normally distributed. The test works by ranking the data from both samples from smallest to largest and then comparing the ranks of the two samples.

The Wilcoxon Rank Sum test is a relatively robust test, so it can be used even if the data is not normally distributed. However, it is not as powerful as a parametric test, such as the t-test, when the data is normally distributed.

The Wilcoxon Rank Sum test is also a relatively simple test to perform, so it is a good choice when you do not have access to a statistical software package.

Here are some other considerations when using the Wilcoxon Rank Sum test:

\* The data must be independent. This means that the observations in one sample cannot be related to the observations in the other sample.

\* The data must be at least ordinal. This means that the data can be ranked from smallest to largest.

\* The data should not have any outliers. Outliers can skew the results of the test.

If you are unsure whether the Wilcoxon Rank Sum test is appropriate for your data, you should consult with a statistician.

1. A data scientist is asked to implement an article recommendation feature for an online magazine. The magazine does not want to use client tracking technologies such as cookies or reading history. Therefore only the style and subject matter of the current article is available for making recommendations. All of the magazines articles are stored in a database in a format suitable for analytics. Which method should the data scientist try first?

A. Association Rules

B. Logistic Regression

C. K Means Clustering

D. Naive Bayesian

SUBMIT YOUR CHOICE

The answer is  D. Naive Bayesian .

Naive Bayesian is a machine learning algorithm that is based on the Bayes theorem. It is a simple and efficient algorithm that can be used for a variety of tasks, including text classification and spam filtering.

In the case of article recommendation, Naive Bayesian can be used to classify articles into different categories based on their style and subject matter. Once the articles have been classified, the data scientist can then recommend articles from the same category as the current article.

Naive Bayesian is a good choice for this task because it does not require any client tracking technologies. It can only use the style and subject matter of the current article to make recommendations.

Here are some other advantages of using Naive Bayesian for article recommendation:

\* It is a simple and efficient algorithm.

\* It is easy to understand and interpret.

\* It can be used with a variety of data types.

\* It is not sensitive to outliers.

Here are some disadvantages of using Naive Bayesian for article recommendation:

\* It can be inaccurate if the data is not well-labeled.

\* It can be biased if the data is not representative of the population.

\* It can be computationally expensive for large datasets.

Overall, Naive Bayesian is a good choice for article recommendation when client tracking technologies are not available. It is a simple and efficient algorithm that can be used with a variety of data types.

1. You are using k means clustering to classify heart patients for a hospital. You have chosen Patient Sex, Height, Weight, Age and Income as measures and have used 3 clusters. When you create a pair wise plot of the clusters, you notice that there is significant overlap between the clusters. What should you do?

A. Decrease the number of clusters

B. Increase the number of clusters

C. Identify additional measures to add to the analysis

D. Remove one of the measures

SUBMIT YOUR CHOICE

The correct answer is  A. Decrease the number of clusters .

If you notice that there is significant overlap between the clusters, then it means that the clusters are not well-defined. This can happen if you have chosen too many clusters or if the measures that you are using are not very good at distinguishing between the different types of heart patients.

In this case, you should try decreasing the number of clusters. This will force the algorithm to find clusters that are more distinct. You can also try identifying additional measures to add to the analysis. This will give the algorithm more information to work with and it may be able to find better clusters.

Removing one of the measures is not likely to help in this case. If the measure that you remove is not very important, then the clusters will not change very much. However, if the measure that you remove is important, then it may make the clusters worse.

Here are some additional things to consider when deciding how many clusters to use:

\* The size of the dataset. If the dataset is large, then you can use more clusters.

\* The variance of the data. If the data is very variable, then you may need to use more clusters.

\* The purpose of the clustering. If you are trying to find very distinct clusters, then you may need to use more clusters.

It is important to experiment with different numbers of clusters to see what works best for your data.

1. What is a core deliverable at the end of the analytic project?

A. The training materials

B. A whitepaper describing the project and the implementation

C. An implemented database design

D. A presentation for project sponsors

SUBMIT YOUR CHOICE

The answer is  D. A presentation for project sponsors .

A presentation for project sponsors is a core deliverable at the end of the analytic project. This presentation should summarize the project, its findings, and its recommendations. It should also address any questions or concerns that the project sponsors may have.

The other options are also important deliverables, but they are not as core as the presentation for project sponsors. The training materials are important for ensuring that the project's findings are understood and used effectively. The whitepaper describing the project and the implementation is important for documenting the project and its results. The implemented database design is important for making the project's findings available to users.

However, the presentation for project sponsors is the most important deliverable because it is the one that will ensure that the project is successful. The project sponsors are the ones who will decide whether or not to implement the project's findings. The presentation is the best opportunity to convince them that the project is worth implementing.

Here are some of the key things that should be included in a presentation for project sponsors:

\* An overview of the project, including its goals, objectives, and scope.

\* A summary of the project's findings, including any insights or recommendations.

\* A discussion of the project's benefits, both financial and strategic.

\* A Q&A session to address any questions or concerns that the project sponsors may have.

The presentation should be clear, concise, and persuasive. It should be tailored to the specific audience of the project sponsors. The goal of the presentation is to convince the project sponsors that the project is worth implementing.

1. A disk drive manufacturer has a defect rate of less than 1.5% with 98% confidence. A quality assurance team samples 1000 disk drives and finds 14 defective units. Which action should the team recommend?

A. There is a flaw in the quality assurance process and the sample should be repeated 

B. A larger sample size should be taken to determine if the plant is operating correctly 

C. A smaller sample size should be taken to determine if the plant is operating correctly 

D. The manufacturing process is functioning properly and no further action is required

SUBMIT YOUR CHOICE

` `The correct answer is B. A larger sample size should be taken to determine if the plant is operating correctly. 

The manufacturer has stated that the defect rate is less than 1.5% with 98% confidence. This means that there is a 98% chance that the true defect rate is less than 1.5%. However, there is still a 2% chance that the true defect rate is greater than 1.5%.

The quality assurance team found 14 defective units in a sample of 1000 disk drives. This is a defect rate of 1.4%, which is slightly higher than the manufacturer's stated defect rate of 1.5%. However, it is still possible that the true defect rate is less than 1.5%.

In order to be more confident that the true defect rate is less than 1.5%, the quality assurance team should take a larger sample size. A larger sample size will give the team a better estimate of the true defect rate.

If the quality assurance team takes a sample of 2000 disk drives and finds 28 defective units, then the defect rate will be 1.4%. This is still slightly higher than the manufacturer's stated defect rate, but it is within the manufacturer's stated confidence interval.

If the quality assurance team takes a sample of 2000 disk drives and finds more than 28 defective units, then the team should recommend that the manufacturer investigate the manufacturing process. It is possible that the true defect rate is greater than 1.5%.

Here are some other factors that the quality assurance team should consider when making their recommendation:

\* The cost of taking a larger sample size.

\* The time it will take to take a larger sample size.

\* The impact on production if the manufacturing process is found to be defective.

The quality assurance team should make a recommendation that is in the best interests of the manufacturer. If the cost of taking a larger sample size is high or the time it will take to take a larger sample size is long, then the team may recommend that the manufacturer continue to operate with the current sample size. However, if the impact on production would be significant if the manufacturing process is found to be defective, then the team may recommend that the manufacturer take a larger sample size.

1. What describes the use of UNION clause in a SQL statement?

A. Operates on both tables and queries and potentially increases both the number of rows and columns

B. Operates on queries and potentially decreases the number of rows

C. Operates on tables and potentially decreases the number of columns

D. Operates on queries and potentially increases the number of rows

SUBMIT YOUR CHOICE

The correct answer is  B. Operates on queries and potentially decreases the number of rows .

The UNION clause in SQL is used to combine the results of two or more queries. The resulting query will contain all the rows that are present in any of the original queries, but no duplicates. This means that the UNION clause can potentially decrease the number of rows in the result set.

The UNION clause does not operate on tables. It only operates on queries. The queries that are used with the UNION clause must have the same number of columns, and the columns must have the same data types.

The UNION clause does not increase the number of columns in the result set. The columns in the result set will be the same as the columns in the original queries.

So the answer is B.

1. How does Pigs use of a schema differ from that of a traditional RDBMS?

A. Pigs schema supports a single data type

B. Pigs schema requires that the data is physically present when the schema is defined

C. Pigs schema is optional

D. Pigs scheam is required for ETL

SUBMIT YOUR CHOICE

The correct answer is  C. Pigs schema is optional .

In a traditional RDBMS, the schema is a required part of the data model. The schema defines the structure of the data, including the names and data types of the columns. The data cannot be loaded into the database without a schema.

In Pig, the schema is optional. The data can be loaded into Pig without a schema, and the schema can be defined later. This flexibility makes Pig a good choice for working with unstructured data.

The other options are incorrect. Pig's schema supports multiple data types, does not require that the data is physically present when the schema is defined, and is not required for ETL.

So the answer is C.

1. How does Pigs use of a schema differ from that of a traditional RDBMS?

A. Pigs schema supports a single data type

B. Pigs schema requires that the data is physically present when the schema is defined

C. Pigs schema is optional

D. Pigs scheam is required for ETL

SUBMIT YOUR CHOICE

The correct answer is  C. Pigs schema is optional .

In a traditional RDBMS, the schema is a required part of the data model. The schema defines the structure of the data, including the names and data types of the columns. The data cannot be loaded into the database without a schema.

In Pig, the schema is optional. The data can be loaded into Pig without a schema, and the schema can be defined later. This flexibility makes Pig a good choice for working with unstructured data.

The other options are incorrect. Pig's schema supports multiple data types, does not require that the data is physically present when the schema is defined, and is not required for ETL.

So the answer is C.

1. What are the characteristics of Big Data?

A. Data volume, processing complexity, and business importance.

B. Data volume, business importance, and data structure variety.

C. Data type, processing complexity, and data structure variety.

D. Data volume, processing complexity, and data structure variety.

SUBMIT YOUR CHOICE

The correct answer is  D. Data volume, processing complexity, and data structure variety .

Big data is a term used to describe data sets that are too large and complex to be processed using traditional methods. Big data is characterized by three main properties:

Volume: Big data sets are very large, often petabytes or exabytes in size.

Velocity: Big data sets are constantly changing, with new data being added all the time.

Variety: Big data sets can be heterogeneous, containing a variety of data types, such as structured, semi-structured, and unstructured data.

In addition to these three main properties, big data is also often characterized by its:

Veracity: Big data can be noisy and inaccurate, which can make it difficult to analyze.

Value: Big data can be used to gain insights into business operations, customer behavior, and other areas.

Privacy: Big data can raise privacy concerns, as it can be used to track individuals' activities.

The characteristics of big data make it difficult to process using traditional methods. However, there are a number of new technologies that have been developed to handle big data, such as Hadoop, Spark, and Hive. These technologies allow businesses to store, process, and analyze big data in order to gain insights into their operations and customers.A 

1. Data Scientist is assigned to build a model from a reporting data warehouse. The warehouse contains data collected from many sources and transformed through a complex, multistage ETL process. What is a concern the data scientist should have about the data?

A. It is not structured

B. It is too processed

C. It is not normalized

D. It is too centralized

SUBMIT YOUR CHOICE

The correct answer is  B. It is too processed .

A reporting data warehouse is typically designed to provide a single source of truth for business reporting. This means that the data is often heavily processed to remove noise and inconsistencies. This can be a concern for data scientists, as it can make the data difficult to work with.

For example, the data may have been aggregated to a high level, which can make it difficult to identify trends or patterns. Additionally, the data may have been cleansed of outliers, which can also make it difficult to get an accurate picture of the data.

The data scientist should carefully evaluate the data to ensure that it is still suitable for their modeling needs. If the data is too processed, they may need to denormalize it or add noise to it in order to make it more useful.

The other options are incorrect. The data is likely to be structured, as it is coming from a data warehouse. It is also unlikely to be normalized, as this would make it more difficult to use for reporting. Finally, the data is not likely to be too centralized, as it is coming from multiple sources.

So the answer is B.

1. What is Hadoop?

A. MapReduce paradigm and HDFS

B. Java classes for HDFS types and MapReduce job management and the MapReduce paradigm 

C. MapReduce paradigm and massive

unstructured data storage on commodity hardware

D. Java classes for HDFS types and MapReduce job management and HDFS

SUBMIT YOUR CHOICE

The correct answer is  A. MapReduce paradigm and HDFS .

Hadoop is an open-source software framework that allows for the distributed storage and processing of large datasets across clusters of computers using simple programming models. It is designed to scale up from single servers to thousands of machines, each offering local computation and storage.

Hadoop consists of two main components:

Hadoop Distributed File System (HDFS) : A distributed file system that provides high-throughput access to application data.

MapReduce : A programming model and an associated implementation for processing and generating large data sets.

MapReduce is a simple programming model that allows users to write applications that process large datasets in parallel on a cluster of computers. The MapReduce job is broken down into two phases:

\* The  map phase is responsible for reading the input data, splitting it into smaller chunks, and applying a user-defined function to each chunk.

\* The  reduce phase is responsible for collecting the output of the map phase and combining it into a smaller set of output data.

Hadoop is a popular choice for storing and processing large datasets because it is scalable, fault-tolerant, and easy to use. It is used by a variety of organizations, including Google, Facebook, and Yahoo.

The other options are incorrect. Hadoop is not just Java classes for HDFS types and MapReduce job management. It is also not just the MapReduce paradigm and massive unstructured data storage on commodity hardware. Finally, Hadoop is not just Java classes for HDFS types and MapReduce job management and HDFS.

So the answer is A.

1. Which method is used to solve for coefficients b0, b1, .., bn in your linear regression model : Y = b0 + b1x1+b2x2+.... +bnxn

A. Ordinary Least squares

B. Apriori Algorithm

C. Ridge and Lasso

D. Integer programming

SUBMIT YOUR CHOICE

The correct answer is  A. Ordinary Least squares .

Ordinary least squares (OLS) is a method for estimating the coefficients in a linear regression model. It minimizes the sum of the squared residuals, which are the differences between the observed values of the dependent variable and the predicted values from the model.

The formula for OLS is as follows:

\```

b = (X'X)^(-1)X'y

\```

where:

\* b is the vector of coefficients

\* X is the matrix of independent variables

\* y is the vector of dependent variables

\* (X'X)^(-1) is the inverse of the transpose of X

OLS is the most common method for solving for the coefficients in a linear regression model. It is relatively easy to implement and is relatively robust to outliers.

The other options are incorrect. Apriori algorithm is a machine learning algorithm for finding frequent itemsets in a transaction database. Ridge and Lasso are regularization methods that can be used to improve the performance of linear regression models. Integer programming is a mathematical optimization technique that can be used to solve problems with integer variables.

So the answer is A.

1. Before you build an ARMA model, how can you tell if your time series is weakly stationary?

A. There appears to be no apparent trend component.

B. The series is normally distributed

C. The mean of the series is close to 0.

D. There appears to be a constant variance around a constant mean.

SUBMIT YOUR CHOICE

The correct answer is  D. There appears to be a constant variance around a constant mean .

Weak stationarity is a property of time series data that means that the mean and variance of the series are constant over time. This means that the series does not have any trend or seasonality, and that the noise in the series is independent and identically distributed.

To check for weak stationarity, we can look at the following properties of the time series:

\* The mean of the series should be constant over time.

\* The variance of the series should be constant over time.

\* The autocorrelation function of the series should decay to 0 as the lag increases.

If the time series meets all of these criteria, then it is weakly stationary.

The other options are incorrect. A trend component in a time series means that the mean of the series is increasing or decreasing over time. This is not a property of weakly stationary time series.

Normality is not a requirement for weak stationarity. In fact, many weakly stationary time series are not normally distributed.

The mean of a weakly stationary time series does not need to be close to 0. It can be any value as long as it is constant over time.

So the answer is D.

1. When would you use GROUP BY ROLLUP clause in your OLAP query?

A. where all sub totals and grand totals are to be included in the output

B. where only specific subtotals and grand totals for a combination of variables are to be included in the output

C. where only the grand totals are to be included in the output

D. where only the subtotals are to be included in the output

SUBMIT YOUR CHOICE

The correct answer is  B. where only specific subtotals and grand totals for a combination of variables are to be included in the output .

The GROUP BY ROLLUP clause is used in OLAP queries to produce a hierarchical view of the data. It calculates the aggregate values for all levels of the hierarchy, including the grand total. The specific subtotals and grand totals that are included in the output are determined by the grouping columns that are specified in the GROUP BY clause.

For example, the following query uses the GROUP BY ROLLUP clause to calculate the total sales for each product category and for the entire company:

\```sql

SELECT product\_category, SUM(sales) AS total\_sales

FROM sales

GROUP BY ROLLUP(product\_category)

\```

This query will return the following results:

\```

product\_category | total\_sales

\----------------- | --------

Food               | 10000

Drinks             | 5000

Toys               | 2000

All Products       | 17000

\```

The first row shows the total sales for the entire company. The second row shows the total sales for the Food product category. The third row shows the total sales for the Drinks product category. The fourth row shows the total sales for the Toys product category.

The GROUP BY ROLLUP clause can be used to produce a variety of different hierarchical views of the data. The specific subtotals and grand totals that are included in the output can be customized to meet the specific needs of the user.

1. The web analytics team uses Hadoop to process access logs. They now want to correlate this data with structured user data residing in their massively parallel database. Which tool should they use to export the structured data from Hadoop?

A. Chukwa

B. Sqoop

C. Pig

D. Scribe

SUBMIT YOUR CHOICE

The correct answer is  B. Sqoop .

Sqoop is a tool that can be used to export data from Hadoop to a variety of different data stores, including relational databases, NoSQL databases, and cloud storage. It is a popular choice for exporting structured data from Hadoop because it is easy to use and it supports a variety of different data formats.

In this case, the web analytics team wants to export the structured data from Hadoop to their massively parallel database. Sqoop can be used to do this by creating a job that will export the data from Hadoop to the database. The job will specify the data that needs to be exported, the format of the data, and the destination database.

Once the job is created, it can be run to export the data from Hadoop to the database. The data will be exported in the specified format and it will be stored in the destination database.

The other options are incorrect. Chukwa is a tool for collecting and analyzing large-scale streaming data. Pig is a high-level language for analyzing data in Hadoop. Scribe is a tool for collecting and storing log data. None of these tools are specifically designed for exporting structured data from Hadoop.

So the answer is B. 

1. Sqoop in R, functions like plot() and hist() are known as what?

A. virtual functions

B. generic functions

C. virtual methods

D. virtual functions

SUBMIT YOUR CHOICE

The correct answer is  B. generic functions .

In R, functions like plot() and hist() are known as generic functions. They are functions that can be used with different types of data. For example, the plot() function can be used to plot a variety of different data types, including numeric data, categorical data, and time series data.

Generic functions are implemented using a technique called  method dispatch . Method dispatch is a way of determining which function to call based on the type of the data that is being passed to the function. In the case of plot(), the R interpreter will determine the type of the data that is being passed to the plot() function and then call the appropriate method.

For example, if the data that is being passed to the plot() function is a vector of numeric data, then the R interpreter will call the `plot.numeric` method. If the data that is being passed to the plot() function is a vector of categorical data, then the R interpreter will call the `plot.factor` method.

Generic functions are a powerful feature of R that allow you to write code that is more general and reusable.

The other options are incorrect. Virtual functions and virtual methods are concepts that are used in object-oriented programming languages, but they are not used in R. Virtual functions are functions that are defined in a base class, but they can be overridden in derived classes. Virtual methods are similar to virtual functions, but they are specific to object-oriented programming languages.

1. Your colleague, who is new to Hadoop, approaches you with a question. They want to know how best to access their data. This colleague has a strong background in data flow languages and programming. Which query interface would you recommend?

A. Hive

B. Howl

C. Pig

D. HBase

SUBMIT YOUR CHOICE

The query interface that I would recommend for your colleague is  C. Pig .

Pig is a high-level language for processing large datasets that is designed for users with a strong background in data flow languages and programming. Pig programs are made up of a series of Pig Latin statements that are executed by the Pig engine. The Pig engine breaks down the Pig Latin statements into MapReduce jobs that are executed on a Hadoop cluster.

Pig is a good choice for your colleague because it is a powerful language that can be used to process large datasets efficiently. It is also a good choice because it is designed for users with a strong background in data flow languages and programming.

The other options are not as good of a fit for your colleague. Hive is a SQL-like language for querying data in Hadoop. It is a good choice for users who are familiar with SQL, but it is not as powerful as Pig. Howl is a distributed scripting language for Hadoop. It is a good choice for users who want to write custom scripts for Hadoop, but it is not as well-suited for processing large datasets as Pig. HBase is a NoSQL database that is designed for storing large amounts of structured data. It is not a good choice for querying data in Hadoop.

So the answer is C. Pig.

1. What is an example of a null hypothesis?

A. that a newly created model provides a prediction of a null sample means

B. that a newly created model does not provide better predictions than the currently existing model

C. that a newly created model provides a prediction that will be well fit to the null distribution.

D. that a newly created model provides a prediction of a null population mean

SUBMIT YOUR CHOICE

The correct answer is  B. that a newly created model does not provide better predictions than the currently existing model .

The null hypothesis is a statement of no difference between two populations or variables. In this case, the null hypothesis is that the newly created model does not provide better predictions than the currently existing model. This is the hypothesis that is being tested, and it is assumed to be true until there is sufficient evidence to reject it.

The alternative hypothesis is the statement that there is a difference between the two populations or variables. In this case, the alternative hypothesis is that the newly created model does provide better predictions than the currently existing model. This is the hypothesis that is accepted if the null hypothesis is rejected.

So, the null hypothesis is a statement of no difference, while the alternative hypothesis is a statement of a difference. The null hypothesis is always tested first, and it is only rejected if there is strong evidence to do so. If the null hypothesis is not rejected, then the alternative hypothesis cannot be accepted.

The other options are not examples of null hypotheses. Option A is a statement about the prediction of a null sample mean, which is not a null hypothesis. Option C is a statement about the fit of a model to a null distribution, which is not a null hypothesis. Option D is a statement about the prediction of a null population mean, which is not a null hypothesis.

1. The web analytics team uses Hadoop to process access logs. They now want to correlate this data with structured user data residing in a production single-instance JDBC database. They collaborate with the production team to import the data into Hadoop. Which tool should they use?

A. Sqoop

B. Chukwa

C. Pig

D. Scribe

SUBMIT YOUR CHOICE

The correct answer is  A. Sqoop .

Sqoop is a tool that can be used to import data from a variety of different data sources, including relational databases, NoSQL databases, and cloud storage, into Hadoop. It is a popular choice for importing data into Hadoop because it is easy to use and it supports a variety of different data formats.

In this case, the web analytics team wants to import structured user data from a production single-instance JDBC database into Hadoop. Sqoop can be used to do this by creating a job that will import the data from the database into Hadoop. The job will specify the data that needs to be imported, the format of the data, and the target Hadoop directory.

Once the job is created, it can be run to import the data from the database into Hadoop. The data will be imported in the specified format and it will be stored in the target Hadoop directory.

The other options are incorrect. Chukwa is a tool for collecting and analyzing large-scale streaming data. Pig is a high-level language for analyzing data in Hadoop. Scribe is a tool for collecting and storing log data. None of these tools are specifically designed for importing data into Hadoop.

So the answer is A. Sqoop.

1. Consider a database with 4 transactions: Transaction 1: cheese, bread, milk Transaction 2: soda, bread, milk

Transaction 3: cheese, bread Transaction 4: cheese, soda, juice The minimum support is 25%. Which rule has a confidence equal to 50%?

A. {bread)=>{milk}

B. {bread,milk}=>{cheese}

C. {juice)=>{soda}

D. {bread)=>{cheese}

SUBMIT YOUR CHOICE

The answer is  B. {bread,milk}=>{cheese} .

The confidence of an association rule is the percentage of transactions that contain the antecedent also contain the consequent. In this case, the antecedent is {bread,milk} and the consequent is {cheese}.

There are 4 transactions in the database, and 2 of them contain {bread,milk}. Of these 2 transactions, both of them contain {cheese}. So, the confidence of the rule is 2/2 = 100%.

The other options do not have a confidence of 50%.

Option A: The support of {bread} is 3/4 = 75%, which is greater than the minimum support of 25%. However, the confidence of the rule is 1/4 = 25%.

Option C: The support of {juice} is 1/4 = 25%, which is less than the minimum support of 25%.

Option D: The support of {bread} is 3/4 = 75%, which is greater than the minimum support of 25%. However, the confidence of the rule is 2/3 = 66.67%.

1. Under which circumstance do you need to implement N fold cross validation after creating a regression model?

A. There are categorical variables in the model.

B. There are missing values in the data.

C. The data is unformatted

D. There is not enough data to create a test set.

SUBMIT YOUR CHOICE

The answer is  D. There is not enough data to create a test set. 

Cross-validation is a technique used to evaluate the performance of a machine learning model. It works by splitting the data into k folds, and then training the model on k-1 folds and testing it on the remaining fold. This process is repeated k times, and the results are averaged to get an estimate of the model's performance.

N-fold cross-validation is a more robust method of cross-validation than k-fold cross-validation. It is especially useful when there is not enough data to create a test set. In this case, N-fold cross-validation can be used to evaluate the model's performance without having to sacrifice any data.

The other options are not reasons to implement N-fold cross-validation after creating a regression model.

Option A: Categorical variables can be handled by one-hot encoding or label encoding.

Option B: Missing values can be handled by imputation or by dropping the rows with missing values.

Option C: The data can be formatted by using a data cleaning library like pandas or NumPy.

So the answer is D.

1. Which word or phrase completes the statement? A spreadsheet is to a data island as a centralized database for reporting is to a

A. Data Warehouse

B. Analytic Sandbox

C. Data Mart

D. Data Warehouse

SUBMIT YOUR CHOICE

The answer is  B. Analytic Sandbox .

A spreadsheet is a personal database that is used by one person or a small team. It is often used to store data that is not easily accessible from a centralized database. A data island is a collection of data that is isolated from other data. This can happen when data is stored in different formats, in different locations, or in different systems.

A centralized database for reporting is a database that is used to store data that is needed for reporting. This data is typically stored in a consistent format and is accessible to all users who need it. An analytic sandbox is a temporary database that is used for data exploration and analysis. It is often used to test new data mining algorithms or to create ad hoc reports.

So, a spreadsheet is to a data island as a centralized database for reporting is to an analytic sandbox.

The other options are incorrect.

Option A: A data warehouse is a large collection of data that is used for analysis and reporting. It is not a good fit for the analogy because it is not a personal database.

Option C: A data mart is a smaller version of a data warehouse. It is typically used by a specific department or business unit. It is not a good fit for the analogy because it is not a centralized database.

Option D: A data lake is a repository for raw data. It is not a good fit for the analogy because it is not a database that is used for reporting.

1. Which word or phrase completes the statement? A spreadsheet is to a data island as a centralized database for reporting is to a

A. Data Warehouse

B. Analytic Sandbox

C. Data Mart

D. Data Warehouse

SUBMIT YOUR CHOICE

The answer is  B. Analytic Sandbox .

A spreadsheet is a personal database that is used by one person or a small team. It is often used to store data that is not easily accessible from a centralized database. A data island is a collection of data that is isolated from other data. This can happen when data is stored in different formats, in different locations, or in different systems.

A centralized database for reporting is a database that is used to store data that is needed for reporting. This data is typically stored in a consistent format and is accessible to all users who need it. An analytic sandbox is a temporary database that is used for data exploration and analysis. It is often used to test new data mining algorithms or to create ad hoc reports.

So, a spreadsheet is to a data island as a centralized database for reporting is to an analytic sandbox.

The other options are incorrect.

Option A: A data warehouse is a large collection of data that is used for analysis and reporting. It is not a good fit for the analogy because it is not a personal database.

Option C: A data mart is a smaller version of a data warehouse. It is typically used by a specific department or business unit. It is not a good fit for the analogy because it is not a centralized database.

Option D: A data lake is a repository for raw data. It is not a good fit for the analogy because it is not a database that is used for reporting.

1. When creating a presentation for a technical audience, what is the main objective?

A. Show how you met the project goals

B. Show that you met the project goals

C. Show if the model will meet the SLA

D. Show the technique to be used in the production environment

SUBMIT YOUR CHOICE

The main objective of a presentation for a technical audience is to  show how you met the project goals .

A technical audience is typically made up of people who are familiar with the technical aspects of the project. They will be interested in understanding how the project was executed and how the results met the project goals.

The presentation should be clear, concise, and easy to follow. It should use visuals to help explain the concepts and to make the presentation more engaging. The presenter should be prepared to answer questions from the audience.

The following are some tips for creating a presentation for a technical audience:

Start by clearly stating the project goals. What were you trying to achieve with the project?

Explain the steps that were taken to meet the project goals. What methods were used? What data was collected?

Present the results of the project. How well did the project meet the goals?

Use visuals to help explain the concepts. Charts, graphs, and diagrams can be very helpful in communicating complex ideas.

Be prepared to answer questions from the audience. The audience will likely have questions about the project, so be prepared to answer them.

By following these tips, you can create a presentation that will inform and engage your technical audience.

1. Review the following code: SELECT pn, vn, sum(prc\*qty) FROM sale GROUP BY CUBE(pn, vn) ORDER BY 1, 2, 3; Which combination of subtotals do you expect to be returned by the query?

A. ((pn,vn),(pn), (vn))

B. (pn,vn)

C. ((pn,vn),(pn),(vn),())

SUBMIT YOUR CHOICE

The correct answer is  C. ((pn,vn),(pn),(vn),()) .

The `GROUP BY CUBE` clause in the query will group the data by all possible combinations of the `pn` and `vn` columns. The `sum(prc\*qty)` aggregation function will calculate the sum of the product of the `prc` and `qty` columns for each group. The `ORDER BY` clause will order the results by the `pn`, `vn`, and `sum(prc\*qty)` columns.

The expected results of the query are:

\* ((pn,vn), sum(prc\*qty)): This subtotal will contain the total sales for all products and variants.

\* (pn, sum(prc\*qty)): This subtotal will contain the total sales for each product, grouped by variant.

\* (vn, sum(prc\*qty)): This subtotal will contain the total sales for each variant, grouped by product.

\* (): This subtotal will contain the total sales for all products and variants, grouped by nothing.

The following is an example of how the results of the query might look:

\```

(pn,vn, sum(prc\*qty))

(apple,red,1000)

(apple,green,500)

(banana,yellow,200)

(orange,orange,100)

(,,3800)

(apple,,500)

(banana,,200)

(orange,,100)

\```

1. Which word or phrase completes the statement? Data-ink ratio is to data visualization as

A. Seasonality is to ARIMA

B. Data Scientist is to big data

C. Confusion matrix is to classifier

D. K means is to Native Bayes

SUBMIT YOUR CHOICE

The answer is  C. Confusion matrix is to classifier .

A data-ink ratio is a measure of how much ink is used to convey meaning in a data visualization. A confusion matrix is a table that is used to evaluate the performance of a classifier.

A good data visualization should use as little ink as possible to convey its message. The data-ink ratio is a way to measure how well a visualization achieves this goal. A confusion matrix is a tool that can be used to evaluate the performance of a classifier. It shows how often the classifier correctly classifies the data and how often it incorrectly classifies the data.

So, a data-ink ratio is to data visualization as a confusion matrix is to classifier.

The other options are incorrect.

Option A: Seasonality is a characteristic of time series data that refers to the tendency of the data to repeat itself over regular intervals. ARIMA is a statistical model that can be used to forecast time series data that exhibits seasonality.

Option B: A data scientist is a person who collects, analyzes, and interprets data. Big data is a term used to describe large and complex datasets.

Option D: K-means is a clustering algorithm that can be used to group data points into clusters. Native Bayes is a probabilistic classifier that can be used to classify data points into two or more classes.

1. A data scientist plans to classify the sentiment polarity of 10, 000 product reviews collected from the Internet. What is the most appropriate model to use? Suppose labeled training data is available.

A. Logistic regression

B. Native Bayesian classifier

C. K means clustering

D. Linear regression

SUBMIT YOUR CHOICE

The most appropriate model to use for classifying the sentiment polarity of 10,000 product reviews is  A. Logistic regression .

Logistic regression is a statistical model that can be used to predict the probability of a binary outcome, such as positive or negative sentiment. It is a good choice for this task because it is relatively simple to understand and interpret, and it can be used with large datasets.

Native Bayesian classifier is also a good choice, but it is more complex to understand and interpret than logistic regression. K means clustering and linear regression are not appropriate for this task because they are not designed to predict binary outcomes.

Here are some additional reasons why logistic regression is a good choice for this task:

\* Logistic regression is a supervised learning algorithm, which means that it requires labeled training data. In this case, we have labeled training data, which is a list of product reviews with their corresponding sentiment polarity.

\* Logistic regression is a parametric model, which means that it makes assumptions about the underlying distribution of the data. This can be helpful in some cases, because it can make the model more accurate.

\* Logistic regression is a versatile model, and it can be used for a variety of tasks, including classification, regression, and survival analysis.

1. If your intention is to show trends over time, which chart type is the most appropriate way to depict the data?

A. Bar chart

B. Histogram

C. Stacked bar chart

D. Line chart

SUBMIT YOUR CHOICE

The most appropriate chart type to show trends over time is  D. Line chart .

A line chart is a graphical representation of data that shows how the data changes over time. It is a good choice for showing trends because it can easily show the direction and magnitude of change.

Bar charts and histograms are also good choices for showing trends, but they are not as effective as line charts. Bar charts are good for showing comparisons between different categories, while histograms are good for showing the distribution of data.

Stacked bar charts are not appropriate for showing trends, because they can be difficult to interpret when there are multiple categories.

Here is an example of a line chart that shows the trend of the stock market over time:

[Image of a line chart showing the trend of the stock market over time]

The line chart clearly shows the upward trend of the stock market over time. It also shows the magnitude of the change, which is significant.

1. Which type of numeric value does a logistic regression model estimate?

A. Probability

B. A p value

C. Any real number

D. Any integer

SUBMIT YOUR CHOICE

Logistic regression models estimate the  A. Probability of an outcome, given a set of predictor variables.

In logistic regression, the dependent variable is a binary variable, such as whether or not someone is diagnosed with a disease. The independent variables are the predictor variables, such as age, gender, and smoking status. The logistic regression model estimates the probability of a positive outcome, such as being diagnosed with a disease, given the values of the independent variables.

The output of a logistic regression model is a probability between 0 and 1. A probability of 0 means that the model is certain that the outcome will be negative, while a probability of 1 means that the model is certain that the outcome will be positive. A probability of 0.5 means that the model is equally likely to predict a positive or negative outcome.

The p-value is a measure of the statistical significance of the model. It is not a measure of the probability of the outcome.

Any real number and any integer are not appropriate answers because logistic regression models only estimate probabilities.

1. What would be considered Big Data?

A. Aggregated statistical data stored in a relational database table

B. Daily Log files from a web server that receives 100,000 hits per minute

C. An OLAP Cube containing consumer demographic information about 100,000,000 customers

D. Spreadsheets containing monthly sales data for a Global 100 corporation

SUBMIT YOUR CHOICE

The correct answer is  B. Daily Log files from a web server that receives 100,000 hits per minute .

Big data is a term used to describe datasets that are too large or complex to be processed using traditional data processing methods. The three main characteristics of big data are:

\* Volume: Big data datasets are very large, often in the terabyte or petabyte range.

\* Velocity: Big data datasets are generated and processed at high speeds.

\* Variety: Big data datasets can contain a variety of data types, including structured, semi-structured, and unstructured data.

The daily log files from a web server that receives 100,000 hits per minute meet all three of the characteristics of big data. The dataset is very large (in the terabyte range), it is generated and processed at high speeds, and it contains a variety of data types (including structured and semi-structured data).

The other options are not considered big data because they do not meet all three of the characteristics of big data.

\* Aggregated statistical data stored in a relational database table is not considered big data because it is not very large.

\* An OLAP Cube containing consumer demographic information about 100,000,000 customers is not considered big data because it is not generated and processed at high speeds.

\* Spreadsheets containing monthly sales data for a Global 100 corporation is not considered big data because it does not contain a variety of data types.

1. When would you prefer a Naive Bayes model to a logistic regression model for classification?

A. When all the input variables are numerical

B. When some of the input variable might be correlated

C. When you need to estimate the probability of an outcome, not just which class it is in.

D. When you are using several categorical input variables with over 1000 possible value each.

SUBMIT YOUR CHOICE

The correct answer is  D. When you are using several categorical input variables with over 1000 possible value each .

Naive Bayes models are a type of probabilistic model that are based on the  naive independence assumption . This assumption states that the input variables are independent of each other, given the class label. This assumption is often violated in real data, but it can be a good approximation when the input variables have a large number of possible values.

Logistic regression models do not make any assumptions about the independence of the input variables. This can make them more accurate than Naive Bayes models when the input variables are correlated. However, logistic regression models can be more computationally expensive to train and predict with than Naive Bayes models.

In the case where you are using several categorical input variables with over 1000 possible value each, the naive independence assumption is likely to be a good approximation. This is because the number of possible combinations of values for these input variables is very large, so it is unlikely that any two of the variables will be perfectly correlated.

In this case, a Naive Bayes model is likely to be more accurate and computationally efficient than a logistic regression model.

1. You are using the Apriori algorithm to determine the likelihood that a person who owns a home has a good credit score. You have determined that the confidence for the rules used in the algorithm is > 75%. You calculate lift = 1.011 for the rule, People with good credit are homeowners. What can you determine from the lift calculation?

A. Support for the association is law

B. Leverage of the rules is low

C. The rule is coincidental

D. The rule is true

SUBMIT YOUR CHOICE

The correct answer is  B. Leverage of the rules is low .

The lift metric is used to measure the  strength of the association between two items. It is calculated as follows:

\```

lift = (probability of A and B) / (probability of A)

\```

In this case, the probability of A is the probability that a person has a good credit score. The probability of B is the probability that a person owns a home. The lift of 1.011 means that the probability of a person having a good credit score is 1.1% higher if they also own a home.

A lift of 1 means that there is no association between the two items. A lift of greater than 1 means that there is a positive association between the two items. A lift of less than 1 means that there is a negative association between the two items.

In this case, the lift of 1.011 is very close to 1, so it means that there is a  weak association between owning a home and having a good credit score. This is supported by the fact that the confidence of the rule is only 75%.

A high confidence and a high lift would mean that the rule is true. However, a low confidence and a high lift would mean that the rule is coincidental. In this case, the confidence is high, but the lift is low, so the rule is not true.

The leverage of the rules is a measure of how much the association between two items changes when you control for other factors. In this case, the leverage of the rules is low, which means that the association between owning a home and having a good credit score is not very strong.

So the answer is  B. Leverage of the rules is low .

1. You are analyzing a time series and want to determine its stationarity. You also want to determine the order of autoregressive models. How are the autocorrelation functions used?

A. PACF as an indication of stationarity, and ACF for the correlation between Xt and Xt-k not explained by their mutual correlation with X1 through Xk-1.

B. ACF as an indication of stationarity, and PACF for the correlation between Xt and Xt-k not explained by their mutual correlation with X1 through Xk-1.

C. PACF as an indication of stationarity, and ACF to determine the correlation of X1 through Xk-1. 

D. ACF as an indication of stationarity, and PACF to determine the correlation of X1 through Xk-1.

SUBMIT YOUR CHOICE

The correct answer is  B. ACF as an indication of stationarity, and PACF for the correlation between Xt and Xt-k not explained by their mutual correlation with X1 through Xk-1. 

The autocorrelation function (ACF) is a measure of the correlation between a time series and its lagged values. It can be used to determine if a time series is stationary. A stationary time series is one whose statistical properties do not change over time.

The partial autocorrelation function (PACF) is a measure of the correlation between a time series and its lagged values, after removing the effects of the intermediate lagged values. It can be used to determine the order of autoregressive models.

In this case, the ACF can be used to determine if the time series is stationary. If the ACF decays to zero after a certain lag, then the time series is stationary. If the ACF does not decay to zero, then the time series is non-stationary.

The PACF can be used to determine the order of autoregressive models. The order of an autoregressive model is the number of lagged values that are used to predict the current value of the time series. The PACF will have significant spikes at the lags that correspond to the order of the autoregressive model.

So, the ACF can be used as an indication of stationarity, and the PACF can be used for the correlation between Xt and Xt-k not explained by their mutual correlation with X1 through Xk-1.

1. You are using MADlib for Linear Regression analysis. Which value does the statement return? SELECT (linregr(depvar, indepvar)).r2 FROM zeta1;

A. Goodness of fit

B. P value

C. Standard error

D. Coefficients

SUBMIT YOUR CHOICE

The correct answer is  A. Goodness of fit .

The `linregr()` function in MADlib is used to perform linear regression analysis. The `r2` parameter of the `linregr()` function returns the  goodness of fit of the linear regression model.

The goodness of fit is a measure of how well the linear regression model fits the data. A high value of r2 indicates that the model fits the data well, while a low value of r2 indicates that the model does not fit the data well.

The statement `SELECT (linregr(depvar, indepvar)).r2 FROM zeta1;` will return the goodness of fit of the linear regression model for the variables `depvar` and `indepvar` in the table `zeta1`.

The other options are incorrect.

\* The `p value` is a measure of the statistical significance of the linear regression model.

\* The `standard error` is a measure of the uncertainty in the coefficients of the linear regression model.

\* The `coefficients` are the parameters of the linear regression model.

1. Your company has 3 different sales teams. Each teams sales manager has developed incentive offers to increase the size of each sales transaction. Any sales manager |whose incentive program can be shown to increase the size of the average sales transaction will receive a bonus. Data are available for the number and average sale amount for transactions offering one of the incentives as well as transactions offering no incentive. The VP of Sales has asked you to determine analytically if any of the incentive programs has resulted in a demonstrable increase in the average sale amount. Which analytical technique would be appropriate in this situation?

A. One way ANOVA

B. Multi way ANOVA

C. Wilcoxson Rank Sum Test

D. Students t test

SUBMIT YOUR CHOICE

The correct answer is  A. One way ANOVA .

One-way ANOVA is a statistical test that is used to compare the means of two or more groups. In this case, there are three groups: the sales teams with incentives, the sales teams with no incentives, and the overall average. One-way ANOVA can be used to determine if there is a statistically significant difference in the average sales transaction amount between the three groups.

The other options are incorrect.

Multivariate ANOVA is used to compare the means of two or more groups when there are multiple independent variables. In this case, there is only one independent variable: the incentive program.

Wilcoxon Rank Sum Test is used to compare the medians of two groups. In this case, we are interested in comparing the means of the three groups, not the medians.

Student's t test is used to compare the means of two groups when the data is normally distributed. In this case, we do not know if the data is normally distributed, so we cannot use a Student's t test.

1. In which lifecycle stage are test and training data sets created?

A. Model planning

B. Data preparation

C. Model building

D. Discovery

SUBMIT YOUR CHOICE

The correct answer is  B. Data preparation .

In the data preparation lifecycle stage, the data is cleaned, formatted, and split into training and test sets. The training set is used to train the model, while the test set is used to evaluate the model's performance.

The other options are incorrect.

Model planning is the stage where the goals of the model are defined and the data is gathered.

Model building is the stage where the model is created and trained.

Discovery is the stage where the data is explored and insights are generated.

1. What is an appropriate data visualization to use in a presentation for an analyst audience?

A. ROC curve

B. Area chart

C. Pie Chart

D. Stacked bar chart

SUBMIT YOUR CHOICE

The answer is  A. ROC curve .

ROC curves are a good choice for presentations to analyst audiences because they are a versatile tool that can be used to visualize a variety of different metrics. They are also relatively easy to understand, even for non-technical audiences.

ROC curves can be used to visualize the performance of a binary classifier. They plot the true positive rate (TPR) against the false positive rate (FPR) at different thresholds. The TPR is the percentage of positive instances that are correctly classified, while the FPR is the percentage of negative instances that are incorrectly classified.

ROC curves can also be used to compare the performance of different classifiers. The classifier with the highest area under the ROC curve (AUC) is the best classifier.

Here are some other reasons why ROC curves are a good choice for presentations to analyst audiences:

\* They are a standard metric for evaluating the performance of binary classifiers.

\* They are easy to understand and interpret.

\* They can be used to visualize the performance of a classifier at different thresholds.

\* They can be used to compare the performance of different classifiers.

The other options are not as appropriate for presentations to analyst audiences.

Area charts are good for visualizing trends over time, but they can be difficult to interpret when there are multiple variables.

Pie charts are not effective for visualizing large amounts of data.

Stacked bar charts are good for visualizing comparisons between categories, but they can be difficult to interpret when there are multiple variables.

1. You have fit a decision tree classifier using 12 input variables. The resulting tree used 7 of the 12 variables, and is 5 levels deep. Some of the nodes contain only 3 data points. The AUC of the model is 0.85. What is your evaluation of this model?

A. The AUC is high, so the overall model is accurate. It is not well calibrated, because the small nodes will give poor estimates of probability

B. The tree did not split on all the input variables. You need a large data set to get a more accurate model.

C. The tree is probably overfit. Try fitting

shallower trees and using an ensemble method. D. The AUC is high, and the small nodes are all very pure. This is an accurate model.

SUBMIT YOUR CHOICE

The correct answer is  C. The tree is probably overfit. Try fitting shallower trees and using an ensemble method. 

The AUC of 0.85 is high, which means that the model is overall accurate. However, the fact that some of the nodes contain only 3 data points is a sign that the tree is overfit. Overfitting occurs when a model learns the training data too well and is not able to generalize to new data. This can happen when the model is too complex or when the training data is not large enough.

In this case, the tree is too complex because it is 5 levels deep and uses 7 of the 12 input variables. The small nodes with only 3 data points are a sign that the tree is learning the noise in the training data.

To address the overfitting, we can try fitting shallower trees. Shallower trees are less complex and are less likely to overfit the training data. We can also try using an ensemble method, such as a random forest. Ensemble methods combine multiple models to improve the accuracy and reduce overfitting.

Here are some additional reasons why the tree might be overfit:

\* The training data is not large enough.

\* The model is not regularized.

\* The model is using too many input variables.

1. Which data asset is an example of quasi-structured data?

A. Database Table

B. News article

C. XML data file

D. Webserver log

SUBMIT YOUR CHOICE

The answer is  C. XML data file .

Quasi-structured data is a type of data that has some structure, but not as much structure as a relational database or a spreadsheet. XML data files are a good example of quasi-structured data. XML files are made up of elements, which are like rows in a spreadsheet. However, the elements in an XML file can be in any order, and they can have different attributes.

The other options are not examples of quasi-structured data.

Database tables are a type of structured data. They have a fixed schema, which means that the columns and their data types are defined.

News articles are a type of unstructured data. They do not have a fixed schema, and the data can be in any order.

Webserver logs are a type of semi-structured data. They have a fixed schema, but the data can be incomplete or inaccurate.

1. Consider a database with 4 transactions: Transaction 1: cheese, bread, milk Transaction 2: soda, bread, milk Transaction 3: cheese, bread Transaction |4: cheese, soda, juice You decide to run the association rules algorithm where minimum support is 50%. Which rule has a confidence at least 50%?

A. {cheese)=>{bread}

B. {juice}=>{cheese}

C. {sode}=>{milk}

D. {milk}=>{soda}

SUBMIT YOUR CHOICE

The correct answer is  A. {cheese)=>{bread} .

The confidence of an association rule is the percentage of transactions that contain the antecedent (the left-hand side of the rule) also contain the consequent (the right-hand side of the rule).

The support of an association rule is the percentage of transactions that contain the antecedent.

In this case, the support of the rule {cheese}=>{bread} is 75%, because 3 out of 4 transactions contain both cheese and bread. The confidence of the rule is also 75%, because 3 out of 3 transactions that contain cheese also contain bread.

The other rules do not have a confidence of at least 50%.

\* The support of the rule {juice}=>{cheese} is 50%, but the confidence is 0%.

\* The support of the rule {soda}=>{milk} is 50%, but the confidence is 33.33%.

\* The support of the rule {milk}=>{soda} is 25%, but the confidence is 0%.

1. In data visualization, what is used to focus the audience on a key part of a chart?

A. Detailed text

B. Emphasis colors

C. Pastel colors

D. A data table

SUBMIT YOUR CHOICE

The answer is  B. Emphasis colors .

In data visualization, emphasis colors are used to focus the audience on a key part of a chart. They are typically used to highlight outliers, trends, and other important data points.

For example, if you are creating a chart to show the sales of different products over time, you might use emphasis colors to highlight the product that has the highest sales. This will help the audience to quickly identify the most important data point in the chart.

Other colors that can be used for emphasis include:

Bright colors , such as red, yellow, and blue.

Contrasting colors , such as black and white.

Gradients , which are shades of the same color that gradually change from light to dark.

It is important to use emphasis colors sparingly, as too many colors can be overwhelming and distracting. The goal is to use emphasis colors to highlight the most important data points, without making the chart too busy.

The other options are not used to focus the audience on a key part of a chart.

Detailed text is used to provide additional information about the data.

Pastel colors are typically used to create a calming and relaxing effect.

A data table is used to display the raw data in a more detailed format.

1. In which lifecycle stage are appropriate analytical techniques determined?

A. Data preparation

B. Model planning

C. Discovery

D. Model building

SUBMIT YOUR CHOICE

The correct answer is  C. Discovery .

In the discovery stage of the data science lifecycle, the data is explored and analyzed to identify patterns and insights. This stage is where the appropriate analytical techniques are determined.

The data scientist will look at the data and ask questions like:

\* What are the most important features in the data?

\* What are the relationships between the features?

\* Are there any outliers or anomalies in the data?

\* What are the trends in the data?

Once the data scientist has a good understanding of the data, they can start to determine which analytical techniques are appropriate for the task at hand.

The other options are incorrect.

Data preparation is the stage where the data is cleaned, formatted, and organized.

Model planning is the stage where the goals of the model are defined and the data is gathered.

Model building is the stage where the model is created and trained.

1. Consider the training data set shown in the exhibit. What are the classification (Y = 0 or 1) and the probability of the classification for the tuple X(0, 0, 1) using Naive Bayesian classifier?

A. Classification Y=0, Probability = 4//54

B. Classification Y=1, Probability = 4//54 

C. Classification Y=0, Probability = 1//54 

D. Classification Y=1, Probability = 1//54

SUBMIT YOUR CHOICE

The correct answer is  B. Classification Y=1, Probability = 4//54 .

The Naive Bayesian classifier works by assuming that the attributes of a data point are independent of each other. In other words, it assumes that the probability of a data point belonging to a certain class is the product of the probabilities of each of its attributes belonging to that class.

The training data set shown in the exhibit has two classes, 0 and 1. The class 0 has 4 data points, and the class 1 has 5 data points. The attribute values are also binary, 0 and 1.

To classify the tuple X(0, 0, 1), we need to calculate the probability of it belonging to each class. The probability of X(0, 0, 1) belonging to class 0 is:

\```

P(X(0, 0, 1)|Class 0) \* P(Class 0)

\```

The probability of X(0, 0, 1) belonging to class 0 is the product of the probabilities of its three attributes being 0. The probability of each attribute being 0 is 1/2, since there are 2 possible values for each attribute and 1 of those values is 0. So the probability of X(0, 0, 1) belonging to class 0 is:

\```

(1/2)^3 \* 4/9

\```

The probability of class 0 is the number of data points in class 0 divided by the total number of data points, which is 4/9. So the overall probability of X(0, 0, 1) belonging to class 0 is:

\```

(1/2)^3 \* 4/9 = 1/54

\```

The probability of X(0, 0, 1) belonging to class 1 is:

\```

P(X(0, 0, 1)|Class 1) \* P(Class 1)

\```

The probability of X(0, 0, 1) belonging to class 1 is the product of the probabilities of its three attributes being 0. The probability of each attribute being 0 is 1/2, since there are 2 possible values for each attribute and 1 of those values is 0. So the probability of X(0, 0, 1) belonging to class 1 is:

\```

(1/2)^3 \* 5/9

\```

The probability of class 1 is the number of data points in class 1 divided by the total number of data points, which is 5/9. So the overall probability of X(0, 0, 1) belonging to class 1 is:

\```

(1/2)^3 \* 5/9 = 4/54

\```

Since the probability of X(0, 0, 1) belonging to class 1 is greater than the probability of it belonging to class 0, the Naive Bayesian classifier will classify X(0, 0, 1) as class 1. The probability of this classification is 4/54.

So the answer is  B. Classification Y=1, Probability = 4//54 .

1. What are Precision and Recall rate of the model?

A. Precision = 277//262

Recall = 288/262

B. Precision = 288/262

Recall = 277/262

C. Precision = 262/277

Recall = 262/288

D. Precision = 262/288

Recall = 262/277

SUBMIT YOUR CHOICE

The correct answer is C. Precision = 262/277 and Recall = 262/288 

Precision is the fraction of predicted positive instances that are actually positive. In this case, there are 262 predicted positive instances, and 26 of them are actually positive, so the precision is 262/277.

Recall is the fraction of actual positive instances that are predicted positive. In this case, there are 288 actual positive instances, and 26 of them are predicted positive, so the recall is 262/288.

Here is a table that summarizes the confusion matrix for the Naive Bayes classifier:

| Actual | Predicted |

\|---|---|

| Positive | 26 | 262 |

| Negative | 0 | 15 |

Precision is calculated by dividing the number of true positives by the number of true positives plus the number of false positives. In this case, there are 26 true positives and 26 false positives, so the precision is 26/(26 + 26) = 26/52 = 262/277.

Recall is calculated by dividing the number of true positives by the number of true positives plus the number of false negatives. In this case, there are 26 true positives and 15 false negatives, so the recall is 26/(26 + 15) = 262/288.

Therefore, the precision of the model is 262/277 and the recall of the model is 262/288 You are working on creating an OLAP query that outputs several rows of with summary rows of subtotals and grand totals in addition to regular rows that may contain NULL as shown in the exhibit. 

1. Which function can you use in your query to distinguish the row from a regular row to a subtotal row?

A.GRroOUP\_ID

B.ROLLUP

C.raNK

D. GROUPING

SUBMIT YOUR CHOICE

The correct answer is D. GROUPING 

The GROUPING function in SQL is used to distinguish rows from regular rows to subtotal rows in an OLAP query. The GROUPING function returns a value of 1 for a subtotal row and 0 for a regular row.

For example, if you have an OLAP query that outputs the following rows:

\```

Country | Sales

\------- | --------

USA | 100

Canada | 50

\```

And you want to add a subtotal row for North America, you can use the GROUPING function like this:

\```

SELECT

`  `Country,

`  `Sales,

`  `GROUPING(Country) AS IsSubtotal

FROM

`  `sales

GROUP BY

`  `Country

\```

This will output the following rows:

\```

Country | Sales | IsSubtotal

\------- | -------- | --------

USA | 100 | 0

Canada | 50 | 0

North America | 150 | 1

\```

The GROUPING function is a powerful tool for adding subtotals and grand totals to OLAP queries. It can be used to make your queries more informative and easier to understand.

1. Your customer provided you with 2,000 unlabeled records and asked you to separate them into three groups. What is the correct analytical method to use?

A. Naive Bayesian classification

B. Linear regression

C. Kmeans clustering

D. Logistic regression

SUBMIT YOUR CHOICE

The correct analytical method to use is C. Kmeans clustering 

Kmeans clustering is a unsupervised learning algorithm that groups unlabeled data into a predefined number of clusters. In this case, you have 2,000 unlabeled records and you need to separate them into 3 groups. Kmeans clustering is a good choice for this task because it is relatively simple to implement and it can be used to cluster data with any number of dimensions.

Naive Bayesian classification is a supervised learning algorithm that is used to classify labeled data. Linear regression and logistic regression are both supervised learning algorithms that are used to predict a continuous value from a set of features. In this case, you do not have labeled data and you do not need to predict a continuous value, so neither Naive Bayesian classification, linear regression, nor logistic regression are good choices.

Here is a brief overview of the Kmeans clustering algorithm:

1\. The algorithm starts by randomly selecting k points in the data as the initial cluster centroids.

2\. Each data point is then assigned to the cluster with the closest centroid.

3\. The centroids of the clusters are then recalculated based on the mean of the data points in each cluster.

4\. Steps 2 and 3 are repeated until the centroids no longer change.

The Kmeans clustering algorithm is a good choice for this task because it is relatively simple to implement and it can be used to cluster data with any number of dimensions. It is also a relatively fast algorithm, which is important when you are working with large datasets.

I hope this helps! Let me know if you have any other questions.

1. Which word or phrase completes the statement? Theater actor is to Artistic and Expressive as Data Scientist is to

A. Introverted and Technical

B. Logical and Steadfast

C. Independent and Intelligent

D. Communicative and Collaborative

SUBMIT YOUR CHOICE

The correct answer is D. Communicative and Collaborative 

A theater actor is typically artistic and expressive, while a data scientist is typically communicative and collaborative. Theater actors use their creativity and imagination to bring characters to life, while data scientists use their communication and collaboration skills to work with others to solve problems.

Here is a table that summarizes the key differences between theater actors and data scientists:

| Feature | Theater Actor | Data Scientist |

\|---|---|---|

| Role | To bring characters to life | To solve problems |

| Skills | Creativity, imagination, acting, singing, dancing | Communication, collaboration, problem-solving, programming |

| Personality | Artistic, expressive, outgoing | Communicative, collaborative, independent, intelligent |

Theater actors and data scientists are both creative and intelligent, but they use their creativity and intelligence in different ways. Theater actors use their creativity to bring characters to life, while data scientists use their creativity to solve problems. Theater actors are typically outgoing and expressive, while data scientists are typically more introverted and technical.

However, both theater actors and data scientists are important members of society. Theater actors entertain and educate us, while data scientists help us to solve problems and make better decisions.

1. What is the primary bottleneck in text classification?

A. The fact that text corpora are dynamic

B. The ability to parse unstructured text data

C. The high dimensionality of text data.

D. The availablity of tagged training data

SUBMIT YOUR CHOICE

The correct answer is D. The availablity of tagged training data 

Text classification is the task of assigning a label to a piece of text. It is a challenging task because text data is often unstructured and noisy. This makes it difficult to extract features that can be used to train a classifier.

Another challenge with text classification is the availability of tagged training data. Tagged training data is data that has been labeled with the correct category. This data is essential for training a classifier, but it can be difficult and expensive to obtain.

The other options are also challenges in text classification, but they are not the primary bottleneck. The fact that text corpora are dynamic means that the data is constantly changing, which can make it difficult to keep a classifier up-to-date. The ability to parse unstructured text data is a challenge, but it is becoming less of a bottleneck as new technologies are developed. The high dimensionality of text data can make it difficult to train a classifier, but there are techniques that can be used to reduce the dimensionality of the data.

Therefore, the primary bottleneck in text classification is the availability of tagged training data.

1. In addition to less data movement and the ability to use larger datasets in calculations, what is a benefit of analytical calculations in a database?

A. quicker time to insight

B. improved connections between disparate data sources

C. more efficient handling of categorical values

D. full use of data aggregation functionality

SUBMIT YOUR CHOICE

The correct answer is A. quicker time to insight 

Analytical calculations in a database can provide quicker time to insight because the calculations can be performed on the data where it is stored. This eliminates the need to move the data to a separate analytical platform, which can save time and resources.

Additionally, analytical calculations in a database can be performed on larger datasets than would be possible on a separate analytical platform. This is because databases are designed to store and process large amounts of data.

The other options are also benefits of analytical calculations in a database, but they are not as significant as quicker time to insight.

\* Improved connections between disparate data sources can be beneficial, but it is not as important as quicker time to insight.

\* More efficient handling of categorical values can be beneficial, but it is not as important as quicker time to insight.

\* Full use of data aggregation functionality can be beneficial, but it is not as important as quicker time to insight.

Therefore, the most significant benefit of analytical calculations in a database is quicker time to insight.

1. What is holdout data?

A. a subset of the provided data set that is removed by the data scientist because it contains data errors

B. a subset of the provided data set selected at random and used to validate the model 

C. a subset of the provided data set selected at random and used to initially construct the model

D. a subset of the provided data set that is removed by the data scientist because it contains outliers

SUBMIT YOUR CHOICE

The correct answer is B. a subset of the provided data set selected at random and used to validate the model 

Holdout data is a subset of the provided data set that is selected at random and not used to train the model. It is used to validate the model after it has been trained. The model is evaluated on the holdout data to see how well it performs on unseen data.

The other options are incorrect.

\* Option A is incorrect because holdout data is not removed from the data set because it contains data errors. Instead, data errors are corrected before the holdout data is selected.

\* Option C is incorrect because the training data is used to initially construct the model. The holdout data is not used to construct the model.

\* Option D is incorrect because holdout data is not removed from the data set because it contains outliers. Outliers can be handled in a number of ways, such as by removing them from the data set, transforming them, or weighting them differently.

Therefore, holdout data is a subset of the provided data set selected at random and used to validate the model.

1. You have been assigned to do a study of the daily revenue effect of a pricing model of online transactions. All the data currently available to you has been loaded into your analytics database; revenue data, pricing data, and online transaction data. You find that all the data comes in different levels of granularity. The transaction data has timestamps (day, hour, minutes, seconds), pricing is stored at the daily level, and revenue data is only reported monthly.

What is your next step?

A. Disregard revenue as a driver in the pricing model and create a daily model based on pricing and transactions only

B. Report back to the business owner that the current data model does not support the business question

C. Interpolate a daily model for revenue from the monthly revenue data 

D. Aggregate all data to the monthly level in order to create a monthly revenue model

SUBMIT YOUR CHOICE

The correct answer is C. Interpolate a daily model for revenue from the monthly revenue data 

The goal of the study is to determine the daily revenue effect of a pricing model. However, the data is not available at the daily level for all three variables. The transaction data has timestamps, but the pricing data and revenue data are only available at the daily and monthly levels, respectively.

To address this, you can interpolate a daily model for revenue from the monthly revenue data. This will allow you to create a daily revenue model that can be used to study the effect of the pricing model on daily revenue.

The other options are not feasible.

\* Option A is not feasible because revenue is a key driver in the pricing model. Disregarding revenue would make the model useless.

\* Option B is not feasible because the business owner wants to know the daily revenue effect of the pricing model. Reporting back that the current data model does not support the business question is not helpful.

\* Option D is not feasible because aggregating all the data to the monthly level would mean that you would lose the daily granularity of the transaction data. This would make it impossible to study the daily revenue effect of the pricing model.

Therefore, the next step is to interpolate a daily model for revenue from the monthly revenue data.

1. What is LOESS used for?

A. It fits a smoothed curve to scatterplot data to give a general sense of the data behavior

B. It is a significance test for the correlation between two variables

C. It is run after a one way ANOVA to determine which population has the highest mean value

D. It plots a continuous varible versus a discrete varible, to compare distributions across classes

SUBMIT YOUR CHOICE

The correct answer is A. It fits a smoothed curve to scatterplot data to give a general sense of the data behavior 

LOESS stands for Locally Estimated Scatterplot Smoothing. It is a non-parametric regression method that fits a smoothed curve to scatterplot data. The curve is fitted locally, which means that it is adjusted to the data in the immediate vicinity of each point. This makes LOESS a good choice for data that is not normally distributed or that has outliers.

LOESS can be used to give a general sense of the data behavior, to identify trends, and to smooth out noise. It is often used in conjunction with other statistical methods, such as linear regression and ANOVA.

The other options are incorrect.

\* Option B is incorrect because LOESS is not a significance test. It is a smoothing method.

\* Option C is incorrect because LOESS is not run after a one way ANOVA. It can be used to smooth the data before a one way ANOVA is performed, but it is not a part of the ANOVA procedure.

\* Option D is incorrect because LOESS does not plot a continuous variable versus a discrete variable. It plots a continuous variable against another continuous variable.

1. Which key role for a successful analytic project can consult and advise the project team on the value of end results and how these will be used on a day-to-day basis?

A. Data Scientist

B. Business Intelligence Analyst

C. Business User

D. Project Manager

SUBMIT YOUR CHOICE

The correct answer is C. Business User 

Business users are the people who will be using the results of the analytic project on a day-to-day basis. They are the ones who can best advise the project team on the value of the end results and how they will be used.

Business intelligence analysts can also play a role in this, but they are more focused on the technical aspects of the project. Project managers are responsible for the overall success of the project, but they may not have the same level of expertise as the business users or the business intelligence analysts.

Here are some of the key responsibilities of a business user in an analytic project:

` `Consult with the project team on the project goals and objectives. The business user should be involved in defining the project goals and objectives from the start. This will ensure that the project is aligned with the business needs.

` `Provide input on the data that will be used in the project. The business user should be able to identify the data that is most important to the project and provide input on how the data should be cleaned and prepared.

` `Test the results of the project and provide feedback. The business user should test the results of the project to make sure that they are accurate and useful. They should also provide feedback to the project team on how the results can be improved.

` `Communicate the results of the project to other stakeholders. The business user should be able to communicate the results of the project to other stakeholders in a way that is clear and concise. They should also be able to answer questions about the project and its results.

By fulfilling these responsibilities, business users can ensure that analytic projects are successful and that the results are used to improve the business.

1. Which word or phrase completes the

statement? A data warehouse is to a centralized database for reporting as an

analytic sandbox is to a ?

A. Collection of data assets for modeling

B. Centralized database of KPIs

C. Collection of low volume databases

D. Collection of data assets for ETL

SUBMIT YOUR CHOICE

The answer is A. Collection of data assets for modeling 

A data warehouse is a centralized database for reporting, while an analytic sandbox is a collection of data assets for modeling. Business users can use an analytic sandbox to experiment with different data sets and modeling techniques, without affecting the data warehouse. This allows business users to ensure that analytic projects are successful and that the results are used to improve the business.

The other options are incorrect.

` `Centralized database of KPIs is not a good fit, because KPIs are typically used for reporting, not modeling.

` `Collection of low volume databases is not a good fit, because an analytic sandbox should contain a variety of data sets, including high and low volume data sets.

` `Collection of data assets for ETL is not a good fit, because ETL is the process of extracting, transforming, and loading data, and an analytic sandbox is not used for ETL.
