# Fraud-Detection---Insurance-Claims
## AIM : 

**Fraud Detection Using ML and Python**. In this project, we have to detect fraud in a real-world environment, using ML algorithms and Neo4j graph database. I am creating a python notebook that will help predict the fraud and represent it using a Neo4j database.


## What is a Fraud Detection Model? 

A fraud detection model is a ML model that helps in real-time fraud detection. Machine Learning (ML) is a set of methods and techniques that let computers recognize the patterns and trends and generate predictions based in those.

## Why is Machine Learning suited for Fraud Detection?

With the availability of so many methods and technologies in the market, why is ML suited for fraud detection? Lets see :

**• It is Super-Fast:** In Fraud Detection, we need results super quick, so that we don’t let the fraudster escape. ML is best suited for this.

**• Efficient and Cheap:** Running hundreds and thousands of payments calculation per second is no easy task, the human cost and time would be immense, but ML does the same in a matter of seconds.

**• More Accurate:** Machine learning models are able to learn from patterns of normal behaviour that are very hard to spot otherwise. It is quick to adapt to changes and identify fraud patterns.

**• Scalable:** In case of sudden need of resources, we can scale the ML model for new boundaries and reapply the same algorithm effectively.

## Insurance Fraud, what is it?

Insurance fraud is an illegal act on the part of either the buyer or seller of an insurance contract. Insurance fraud from the issuer includes selling policies from non-existent companies, failing to submit premiums, and churning policies to create more commissions. Buyer fraud, meanwhile, can consist of exaggerated claims, falsified medical history, post-dated policies, viatical fraud, faked death or kidnapping, and murder.

## Insurance Claims dataset

We use a dataset (insurance_claims.csv) comprising of 1000 rows, and 36 columns in the csv(comma separated values) format. We then work on the data and predict the fraudulent patterns using ML.
 
![image](https://user-images.githubusercontent.com/95923021/179353860-a4e54459-7c77-4a42-99ee-e637fcf9c2ec.png)


## How to predict fraud using ML : 

Machine Learning is gives us many models/algorithms that we can use to solve such problems. The steps are in the following order :

•	 Import the libraries and dataset: We first import the necessary libraries and the dataset that will be required. In this case we use pandas, numpy, and seaborn. We then import our dataset – ‘insurance_claims.csv’ by using

 df = pd.read_csv('/content/insurance_claims.csv')
 
**•	Pre-Processing Data:** After importing the dataset, we pre-process the data to look for missing values, NaN values and to check the datatypes used in the dataset.

**•	Visualize Missing Values:** After the pre-processing, we look at the data in the form of graphs and see the missing values, to better understand our dataset.

**•	Handling Missing Values:** We then handle the missing values by replacing then with 0. We then drop the unnecessary labels from our dataset.

**•	Outliers Detection:** We then detect the outliers and train our categorical variables for the classification algorithm.

**•	Use ML algorithm:** After everything has been done, we apply the ML classification algorithm to test our model. 


## Random Forest Classification Model :

 Random Forest is a classifier that contains a number of decision trees on various subsets of the given dataset and takes the average to improve the predictive accuracy of that dataset. Instead of relying on one decision tree, the random forest takes the prediction from each tree and based on the majority votes of predictions, and it predicts the final output.

![image](https://user-images.githubusercontent.com/95923021/179419556-addc864d-1d04-47a0-97fa-9061afb28ef3.png)


## Conclusion:

Hope this project helps !!!
You can contact me incase of further queries.
