# Customer Churn Segmentation

Customer Segmentation is the process of division of customer base into several groups of individuals that share a similarity in different ways that are relevant to marketing such as gender, age, interests, and miscellaneous spending habits.


Companies that deploy customer segmentation are under the notion that every customer has different requirements and require a specific marketing effort to address them appropriately. Companies aim to gain a deeper approach of the customer they are targeting. Therefore, their aim has to be specific and should be tailored to address the requirements of each and every individual customer. Furthermore, through the data collected, companies can gain a deeper understanding of customer preferences as well as the requirements for discovering valuable segments that would reap them maximum profit. This way, they can strategize their marketing techniques more efficiently and minimize the possibility of risk to their investment.


The technique of customer segmentation is dependent on several key differentiators that divide customers into groups to be targeted. Data related to demographics, geography, economic status as well as behavioral patterns play a crucial role in determining the company direction towards addressing the various segments.


[DATA can be downloaded from here](https://drive.google.com/file/d/19BOhwz52NUY3dg8XErVYglctpr5sjTy4/view)

## Steps involved are :
* Read-data
* Study the Summary and Standard Deviation of columns
* Visualise Data
* Plot an Elbow-plot 
* Find optimal clusters
* Perform K-means clustering (6 Clusters) 
* Plot clusters
* Insights


## Visualisation :
Gender BarPlot

![gender](https://github.com/Abrar-04/customer_churn_R/blob/main/images/Gender.png) 

Gender Pie-Chart

![gender-pie](https://github.com/Abrar-04/customer_churn_R/blob/main/images/gender-pie.png)

Age Distribution Histogram 

![age-hist](https://github.com/Abrar-04/customer_churn_R/blob/main/images/age-hist.png)

Age Boxplot

![age-box](https://github.com/Abrar-04/customer_churn_R/blob/main/images/age-box.png)

Annual Income histogram

![income-hist](https://github.com/Abrar-04/customer_churn_R/blob/main/images/income-hist.png)

Annual Income Distribution Curve

![income-dist](https://github.com/Abrar-04/customer_churn_R/blob/main/images/income-dist.png)

Spending Score Boxplot

![spending-box](https://github.com/Abrar-04/customer_churn_R/blob/main/images/spending-box.png)

Spending Score Boxplot Histogram

![spending-hist](https://github.com/Abrar-04/customer_churn_R/blob/main/images/spending-hist.png)

---------------------------------------------------------------------------------------------------------------------

# Elbow method plot to find K-clusters :
![elbow](https://github.com/Abrar-04/customer_churn_R/blob/main/images/elbow.png)

---------------------------------------------------------------------------------------------------------------------

# Optimal no.of clusters :
![optim](https://github.com/Abrar-04/customer_churn_R/blob/main/images/optimal%20elbow.png)

---------------------------------------------------------------------------------------------------------------------

# Optimal Clusters: 6 :
![clusts](https://github.com/Abrar-04/customer_churn_R/blob/main/images/k6.png)

---------------------------------------------------------------------------------------------------------------------

# PLOT 6 clusters :
![plot](https://github.com/Abrar-04/customer_churn_R/blob/main/images/six-cluster.png)

---------------------------------------------------------------------------------------------------------------------

# INSIGHTS :

From the above visualization, we observe that there is a distribution of 6 clusters as follows –

* <b>Cluster 6 and 4</b>: These clusters represent the customer_data with the medium income salary as well as the medium annual spend of salary.

*  Cluster 1 : This cluster represents the customer_data having a high annual income as well as a high annual spend.

* Cluster 3 : This cluster denotes the customer_data with low annual income as well as low yearly spend of income.

* ## Cluster 2 : This cluster denotes a high annual income and low yearly spend.

* ## Cluster 5 : This cluster represents a low annual income but its high yearly expenditure.



