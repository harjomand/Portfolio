# Data Analytics Portfolio
Repository containing Data Science and Data Analytics projects. 

## Predictive Analytics - Machine Learning & Deep Learning with Python
### [Project 1: Prospective Cross-Sell and Up-Sell Opportunities in Customers?](https://github.com/harjomand/Portfolio/blob/main/How_to_Identify_Potential_Cross_sell_And_Up_sell_Customers.ipynb) 
* Explanatory data analytics, Feature Engineering, Feature Importance, Supervised Machine Learning (Logistic Regression, Decision Tree, and Random Forest), Multilayer Perceptrons (MLP), K-means, Autoencoder in Pytorch, and PCA .   
* Benchmark: The benchmark was Logistic regression and it produced 0.7694 AUC on Test dataset.
* Results: By utilizing Random Forest and hyper tuning the parameters, the 0.8025 AUC was achieved. 

* Techniques: 
   - Supervised Machine Learning : Logistic Regression, Decision Tree,Random Forest,
   - Deep Learning : Multilayer Perceptrons (MLP),
   - Unsupervised Machine Learning : K-means, Principal Components Analysis (PCA), and
   - Autoencoder
   
* Tools: 
   - **Python**: Pandas,Numpy,Sklearn,Matplotlib,Seaborn,Keras,and Pytorch 
   
![](/images/RandomForest.PNG)


## Descriptive Analytics - Big Data with Python 
### [Project 2: What impact did the imposed restriction policies during the second wave of COVID-19 in Melbourne have on population mobility trends?](https://github.com/harjomand/Portfolio/blob/main/Covid-19-Melbourne.ipynb) 
* By utilizing the Amazon Web Services (AWS) a NoSQL database is created . The NoSQL database is queried and is analysed to answer the research question.  
* Results: Melbourne's residents demonstrated commendable adherence to the rules, and as a consequence, restrictions were eased on October 26, 2020. Notably, there was a significant decline in various sectors in both March and June. This was primarily due to the public's commitment to following guidelines, maintaining social distancing, and minimizing non-essential travel.

* Techniques:
   - AWS Cloud
   - NoSQL 
   - MongoDB
   
* Tools: 
   - **Python**: Pandas,Numpy,Matplotlib,Seaborn,datetime,PyMongo 
   
![](/images/Covid-19.PNG)


### [Project 3: What was the effect of alterations in transit station activity on the new COVID-19 cases in Brazil and Australia? ](https://github.com/harjomand/Portfolio/blob/main/COVID19_Australia_Brazil.ipynb) 
* A spark distributed dataframes is created . Spark is used to explore, filter, analyse two time-series. 
* Results: Australia experienced two peaks, one in April 2020 and another in August 2020. Since August 2020, the number of new cases in Australia has significantly declined, indicating effective pandemic management. In contrast, Brazil's graph displays notable volatility. Brazil's peak occurred in January 2021 following the new year holidays. Increased station movements in Brazil during November 2020 led to a surge in new cases in January 2021. Imposed restrictions affected transit station movements differently in Australia and Brazil. While station movements decreased significantly in both countries in March 2020, the trend diverged. In Brazil, movements surpassed the baseline in November 2020, resulting in a peak in new cases in January 2021. In Australia, station movements dropped considerably in March 2020 and have not fully returned to normal. The number of new cases has remained low since the second wave in August 2020.

* Techniques: 
   - Spark
   
* Tools: 
   - **Python**: Pandas,Numpy,Matplotlib,Seaborn,datetime,PySpark
  
![](/images/Aus_Br.PNG)



## Descriptive Analytics - Multivariate Analysis for High Dimensional Data with R
### [Project 4:Multivariate Analysis: Percentage of Employment Across Various Industries in Different Regions](https://github.com/harjomand/Portfolio/blob/main/Analysing-Eurogroup.pdf) 
* Applying MANOVA, PCA Analysis, Factor Analysis and Parallel analysis on dependent variables which measure the percentage employment within different employment sectors. The independent variable is Group which is a factor that represents the country regions. 
* Results: In accordance with parallel analysis, it is determined that the number of factors equals NA, and the number of components equals 0. The analysis strongly advises against using any factors, indicating that Factor Analysis (FA) is not suitable for this dataset. The scree plot reveals that the observed eigenvalues for the first 2 components (1.632 and 1.540) are both higher than the mean values derived from simulated datasets (1.421 and 1.097). Nonetheless, the simulated data exhibits significant variation, resulting in substantial standard deviations around the means. The 95th percentile value for the first component (1.665) surpasses the observed eigenvalue. Interestingly, the 95th percentile value for the second component (1.256) falls below the observed eigenvalue. However, due to the impracticality of the first component, consideration of the second component is not feasible.

* Techniques: 
   - Multivariate Analysis Of Variance (MANOVA)
   - Principal Component Analysis (PCA)
   - Factor Analysis
   - Parallel Analysis 
   
* Tools : 
   - **R**: MVN,car, and psych
   
![](/images/Parallel_Analysis_Scree_Plots.PNG)

### [Project 5: Multivariate Analysis: Exploring the Correlation Between Students' Psychological Factors and Academic Performance](https://github.com/harjomand/Portfolio/blob/main/Psychological-Variables-and-Academic-Grades.pdf) 
* Multivariate Analysis for High-Dimensional Data . Applying Canonical Correlation Analysis (CCA) , Discriminant Function Analysis (DFA) , and Cluster Analysis on the Dataset. 
* Results: I discovered a series of positive correlations within and between the psychological and academic variable sets, all of which exhibited moderate strength. Additionally, it became apparent that students with lower levels of self-control and motivation tend to perform poorly in subjects like English, math, history, and biology.However, it is essential to note that the analysis did not yield the desired results. The initial correlation matrices hinted at concerns, particularly the numerous low correlations within the psychological matrix. This leads us to consider the possibility that our assumption of multivariate normality (MVN) may have been misguided, and further testing might reveal that the data does not conform to a multivariate normal distribution.
  
* Techniques: 
   - Canonical Correlation Analysis (CCA) 
   - Discriminant Function Analysis (DFA) 
   - Cluster Analysis
   
* Tools : 
   - **R**: yacca,lattice,caret,MASS, and ade4
   
![](/images/Cluster_Dendorogram.PNG)


## Prescriptive Analytics - Simulation with Python
### [Project 6: Express Checkout Simulation](https://github.com/harjomand/Portfolio/blob/main/Express%20Checkout%20Simulation%20with%20Python%20.ipynb)
* Simulating a real-world scenario with Python: Comparing different checkout configuration and providing recommendation on the quickest checkout service. The aim is to determine the best possible decision . 
* Results: The express checkout should be adopted as it averages a lower checkout time compared to the other methods tested. From a theoretical point of view, having an express checkout is better and reduce the service time.
* Tools: 
   - **Python**: modsim

![](/images/Express_Checkout_.PNG)


### [Project 7: Brisbane City Council Bike System](https://github.com/harjomand/Portfolio/blob/main/Brisbane%20-%20Bike.ipynb)
* Simulating a real-world scenario with Python : Developing a bikeshare model for Brisbane City Council(BCC) and predict the number of unhappy customers at each bike station at the end of each hour over the 24 hour period.

* Tools: 
   - **Python**: modsim

![](/images/Unhappycustomers.PNG)


