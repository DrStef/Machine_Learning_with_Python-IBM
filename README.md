# Machine Learning with Python

Course: Machine Learning with Python.
Part of IBM Data Science Certificate. 

### Simple Linear Regression

We have downloaded a fuel consumption dataset, FuelConsumption.csv, which contains model-specific fuel consumption ratings and estimated carbon dioxide emissions for new light-duty vehicles for retail sale in Canada.
Linear Regression for predicting: "CO2 Emission (g) v. Fuel consumption (l)"

[Jupyter Notebook: Linear-Regression](ML0101EN-Reg-Simple-Linear-Regression-Co2_V2.ipynb)


### Multiple Linear regression 

x = np.asanyarray(test[['ENGINESIZE','CYLINDERS','FUELCONSUMPTION_COMB']])
y = np.asanyarray(test[['CO2EMISSIONS']])

[Jupyter Notebook: Multiple-Linear-Regression](ML0101EN-Reg-Mulitple-Linear-Regression-Co2-v4.ipynb)



### Polynomial Regression 

train_x = np.asanyarray(train[['ENGINESIZE']])
train_y = np.asanyarray(train[['CO2EMISSIONS']])
[Jupyter Notebook: Polynomial-Regression](ML0101EN-Reg-Polynomial-Regression-Co2-V2.ipynb)


### Non-Linear Regression 
china_gdp 1960 - 2014

[Jupyter Notebook: Non-Linear Regression](ML0101EN-Reg-NoneLinearRegression-V3.ipynb)


### Recommandation System 
Create a recommendation system using Content Based filtering 
Now, let's take a look at how to implement Content-Based or Item-Item recommendation systems. This technique attempts to figure out what a user's favourite aspects of an item is, and then recommends items that present those aspects. In our case, we're going to try to figure out the input's favorite genres from the movies and ratings given.
ML0101EN-RecommendationSystem_Content Based Filtering-movies-V2.ipynb

###  Recommendation system based on collaborative filtering
Create recommendation system based on collaborative filtering
The first technique we're going to take a look at is called Collaborative Filtering, which is also known as User-User Filtering. As hinted by its alternate name, this technique uses other users to recommend items to the input user. It attempts to find users that have similar preferences and opinions as the input and then recommends items that they have liked to the input. There are several methods of finding similar users (Even some making use of Machine Learning), and the one we will be using here is going to be based on the Pearson Correlation Function.
ML0101EN-RecommendationSystem-Collaborative-Filtering-movies-V2.ipynb




###  K Nearest neighbors to classify data
Imagine a telecommunications provider has segmented its customer base by service usage patterns, categorizing the customers into four groups. If demographic data can be used to predict group membership, the company can customize offers for individual prospective customers. It is a classification problem. That is, given the dataset, with predefined labels, we need to build a model to be used to predict class of a new or unknown case.
Our objective is to build a classifier, to predict the class of unknown cases. We will use a specific type of classification called K nearest neighbour.
ML0101EN-K-Nearest-Neighbors-Classification_Telecom_Customer_Category-V2.ipynb


###  Customer Segmentation with K-Means
Imagine that you have a customer dataset, and you need to apply customer segmentation on this historical data. Customer segmentation is the practice of partitioning a customer base into groups of individuals that have similar characteristics. It is a significant strategy as a business can target these specific groups of customers and effectively allocate marketing resources. For example, one group might contain customers who are high-profit and low-risk, that is, more likely to purchase products, or subscribe for a service. A business task is to retain those customers. Another group might include customers from non-profit organizations and so on.
ML0101EN-K-Means-Clustering-Customer-Segmentation-V2.ipynb

###  Hierarchical Clustering - Agglomerative

Clustering on Vehicle dataset
Imagine that an automobile manufacturer has developed prototypes for a new vehicle. Before introducing the new model into its range, the manufacturer wants to determine which existing vehicles on the market are most like the prototypes--that is, how vehicles can be grouped, which group is the most similar with the model, and therefore which models they will be competing against.
Our objective here, is to use clustering methods, to find the most distinctive clusters of vehicles. It will summarize the existing vehicles and help manufacturers to make decision about the supply of new models.
ML0101EN-Hierarchical-Clustering-Cars-V2.ipynb

###  Density-Based Clustering

Weather Station Clustering using DBSCAN & scikit-learn.
DBSCAN is especially very good for tasks like class identification in a spatial context. The wonderful attribute of DBSCAN algorithm is that it can find out any arbitrary shape cluster without getting affected by noise. For example, this following example cluster the location of weather stations in Canada. DBSCAN can be used here, for instance, to find the group of stations which show the same weather condition. As you can see, it not only finds different arbitrary shaped clusters, can find the denser part of data-centered samples by ignoring less-dense areas or noises.
ML0101EN-Density-Based Clustering-Weather-V2.ipynb


###  Logistic Regression with Python

Load the Telco Churn data
Telco Churn is a hypothetical data file that concerns a telecommunications company's efforts to reduce turnover in its customer base. Each case corresponds to a separate customer and it records various demographic and service usage information. Before you can work with the data, you must use the URL to get the ChurnData.csv.
ML0101EN-Classification-Logistic-Regression-Customer_Churn_V3.ipynb



Stephane Dedieu April May 2022.
Rev. Oct 2022. 

Various projects.  


