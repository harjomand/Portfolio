# Data Science Portfolio
Repository containing Data Science and Data Analytics projects. 

## Machine Learning & Deep Learning - Python
### [Project 1: How to Identify Potential Cross-sell And Up-sell Customers?](https://github.com/harjomand/Portfolio/blob/main/How_to_Identify_Potential_Cross_sell_And_Up_sell_Customers.ipynb) 
* Explanatory data analytics, Feature Engineering, Feature Importance, Supervised Machine Learning (Logistic Regression, Decision Tree, and Random Forest), Multilayer Perceptrons (MLP), K-means, Autoencoder in Pytorch, and PCA .   
* Benchmar: The benchmark was Logistic regression and it produced 0.7694 AUC on Test dataset.
* Results: By utilizing Random Forest and hyper tuning the parameters, the 0.8025 AUC was achieved. 

* Techniques: 
   - Supervised Machine Learning : Logistic Regression, Decision Tree,Random Forest,
   - Deep Learning : Multilayer Perceptrons (MLP),
   - Unsupervised Machine Learning : K-means, Principal Components Analysis (PCA), and
   - Autoencoder
   
* Tools: 
   - **Python**: Pandas,Numpy,Sklearn,Matplotlib,Seaborn,Keras,and Pytorch 
   
![](/images/RandomForest.PNG)


## Big Data 
### [Project 2: How did the imposed restriction policies during the second wave of COVID-19 in Melbourne effect the population mobility trends?](https://github.com/harjomand/Portfolio/blob/main/Covid-19-Melbourne.ipynb) 
* By utilizing the Amazon Web Services (AWS) a NoSQL database is created . The NoSQL database is queried and is analysed to answer the research question.  
* Results: People really obeyed the rules in Melbourne and as the result of that the restrictions were eases on 26th of October 2020. I saw a rapid drop in March and June in all different sections. People followed the rule, practiced social distancing and avoided optional and not important travels.

* Techniques: 
   - AWS Cloud
   - NoSQL 
   - MongoDB
   
* Tools: 
   - **Python**: Pandas,Numpy,Matplotlib,Seaborn,datetime,PyMongo 
   
![](/images/Covid-19.PNG)


### [Project 3: How did the change in the movements in the transit stations has impacted the new Covid-19 cases in Brazil and Australia? ](https://github.com/harjomand/Portfolio/blob/main/COVID19_Australia_Brazil.ipynb) 
* A spark distributed dataframes is created . Spark is used to explore, filter, analyse two time-series. 
* Results: There were two peaks to Australia, one in April 2020 and one in August 2020. For Australia, the number of new cases has dropped significantly since August 2020. Australia has managed the pandemic very well. On the other hand, for Brazil, we can see a very volatile graph. The peak for Brazil was in January 2021 after the new year holidays. The movement in stations in Brazil increased in November 2020 which led to increase in number of new cases in January 2021. The imposed restrictions have impacted the transit stations movements from baseline in Australia and Brazil in different ways. The movement in the stations reduced in Australia and Brazil significantly in March 2020 but it has increased for Brazil since then. For Brazil, the movement in stations has passed the baseline in November 2020 which led to a peak in number of new cases in January 2021. For Australia , the movement in stations has dropped significantly in March 2020 and has not got back to normal and the number of new cases has been very less since the second wave in August 2020.

* Techniques: 
   - Spark
   
* Tools: 
   - **Python**: Pandas,Numpy,Matplotlib,Seaborn,datetime,PySpark
  
![](/images/Aus_Br.PNG)




## Multivariate Analysis for High-Dimensional Data with R
### [Project 4: Multivariate Analysis - Percentage of Employment in Different Industries By Different Regions](https://github.com/harjomand/Portfolio/blob/main/Analysing-Eurogroup.pdf) 
* Applying MANOVA, PCA Analysis, Factor Analysis and Parallel analysis on dependent variables which measure the percentage employment within different employment sectors. The independent variable is Group which is a factor that represents the country regions. 
* Results: Parallel analysis suggests that the number of factors = NA and the number of components = 0 . The analysis recommends that no factors be used - FA is not appropriate for this data. The scree plot shows that the observed eigen values for the first 2 components (1.632 and 1.540) are both greater than the mean of the simulate data sets (1.421 and 1.097). However, there is quite a bit of variation in the simulated data sets, creating large standard deviations around the means. The 95th percentile value for component 1 (1.665) is greater than the observed eigen value. Interestingly the 95th percentile value for component 2 (1.256) is below the observed eigen value, however since the first component is not feasible we cannot consider the second component.

* Techniques: 
   - Multivariate Analysis Of Variance (MANOVA)
   - Principal Component Analysis (PCA)
   - Factor Analysis
   - Parallel Analysis 
   
* Tools : 
   - **R**: MVN,car, and psych
   
![](/images/Parallel_Analysis_Scree_Plots.PNG)

### [Project 5: Multivariate Analysis - Analysing The Relationship Between Student's Psychological Variables and Their Academic Grades](https://github.com/harjomand/Portfolio/blob/main/Psychological-Variables-and-Academic-Grades.pdf) 
* Multivariate Analysis for High-Dimensional Data . Applying Canonical Correlation Analysis (CCA) , Discriminant Function Analysis (DFA) , and Cluster Analysis on the Dataset. 
* Results: I realized that there are a range of correlations (all positive) within and between psychological and the academic variables sets. They all have moderate correlation.Also, we realized that students who have less control and motivation are associated with students who have low academics in english , maths , history and biology. But the analysis really has not been that successful and possibly those initial correlation matrices should warn us because we had a lot of really low correlation in the Psychological matrix which was a concern. Its possible that our assumption of MVN was a mistake and maybe if we test, it won’t fit a Multivariate normality.

* Techniques: 
   - Canonical Correlation Analysis (CCA) 
   - Discriminant Function Analysis (DFA) 
   - Cluster Analysis
   
* Tools : 
   - **R**: yacca,lattice,caret,MASS, and ade4
   


## Simulation with Python
### [Project 6: Express Checkout Simulation](https://github.com/harjomand/Portfolio/blob/main/Express%20Checkout%20Simulation%20with%20Python%20.ipynb)
* Simulating a real-world scenario with Python: Comparing different checkout configuration and providing recommendation on the quickest checkout service.
* Results: The express checkout should be adopted as it averages a lower checkout time compared to the other methods tested. From a theoretical point of view, having an express checkout is better and reduce the service time.
* Tools: 
   - **Python**: modsim

![](/images/Express_Checkout.PNG)


### [Project 7: Brisbane City Council Bike System](https://github.com/harjomand/Portfolio/blob/main/Brisbane%20-%20Bike.ipynb)
* Simulating a real-world scenario with Python : developing a bikeshare model for Brisbane City Council(BCC) and predict the number of unhappy customers at each bike station at the end of each hour over the 24 hour period.

* Tools: 
   - **Python**: modsim

![](/images/Unhappycustomers.PNG)


