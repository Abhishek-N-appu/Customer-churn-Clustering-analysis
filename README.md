# Customer-churn-Clustering-analysis
In this project we are using Telco Customer churn data to analyze the customer churn with clustering
install anaconda navigator through the link:https://www.anaconda.com/download download all the files from this repsitory. launch jupyter notebook in anaconda navigator![image](https://github.com/Abhishek-N-appu/Customer-churn-Clustering-analysis/assets/150499125/107c9af4-26d5-41ec-9c4b-3c6552822476)
create a new python notebook and start coding as shown in the above screen shot. or else
![image](https://github.com/Abhishek-N-appu/Customer-churn-Clustering-analysis/assets/150499125/870d2c3c-a86e-4d3f-a743-03962618b23b)
upload all notebook and datasets downloaded from this repository and run
# import and load the data
import all the required libraries and data and look at attribute discription as shown below.
![Screenshot 2023-12-21 121320](https://github.com/Abhishek-N-appu/Customer-churn-Clustering-analysis/assets/150499125/da8ef252-8cf6-4987-8649-723365fb8325)
This dataset contains infomation on 7043 customers and 21 attributes, with NO missing values in any columns
The data set includes information about:

Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
Demographic info about customers – gender, age range, and if they have partners and dependents
# visualization of data
![Screenshot 2023-12-21 121627](https://github.com/Abhishek-N-appu/Customer-churn-Clustering-analysis/assets/150499125/dd09c717-d5ec-4c97-92ab-5d74b670028a)
Demographic Variables
![Screenshot 2023-12-21 121803](https://github.com/Abhishek-N-appu/Customer-churn-Clustering-analysis/assets/150499125/0d92c950-aaa0-4089-b996-f931f5087c2c)
![Screenshot 2023-12-21 121905](https://github.com/Abhishek-N-appu/Customer-churn-Clustering-analysis/assets/150499125/762bd89e-24f2-415b-9c09-3da1dbb1603c)
# Getting statistics of variables
![Screenshot 2023-12-21 121950](https://github.com/Abhishek-N-appu/Customer-churn-Clustering-analysis/assets/150499125/c7c9b726-c1ec-4953-86dd-e9b544414b79)
from the above stats u can see
1. Gender does not seem to play any role in customer Churn
Individuals with dependents are less likely to leave the company .
Having a parnter and or being a Senior Citizen slightly increases the odd of an individual leaving the company {Churning}
Uneven group sizes comparision might be difficult, should look at proportions to see if there are any significant differences
The Churn rate for having no Dependents is greater than the Churn Rate for those with dependents .
The Churn Rate for non-senior citizens is less than the churn rate for senior citizens 65+
he Churn rate for individuals without parters is greater than the churn rate for those with partners
# customer account visualization
## payment method
![Screenshot 2023-12-21 122333](https://github.com/Abhishek-N-appu/Customer-churn-Clustering-analysis/assets/150499125/bc63c245-2a8a-4d32-84b7-995d5b1d8817)
Even distribution of payment methods, with Electronic check being the most popular

Churn Rates consistent amongst different payment method, Bank Transfer (automatic) has the highest Churn Rates
# visualizing which service cause churn
![Screenshot 2023-12-21 122702](https://github.com/Abhishek-N-appu/Customer-churn-Clustering-analysis/assets/150499125/c4948106-ca74-4f95-8cc0-194e3eb4420f)Insights
No Security Services, Device Protection, Tech support, Online Backup increases the Churn Rates
Individuals with Fiber Optic churn More compared to ones using DSL
# cluster analysis
![Screenshot 2023-12-21 122839](https://github.com/Abhishek-N-appu/Customer-churn-Clustering-analysis/assets/150499125/ad3a4f5c-290a-41e6-af24-4a489223875d)
![Screenshot 2023-12-21 122902](https://github.com/Abhishek-N-appu/Customer-churn-Clustering-analysis/assets/150499125/abdbf9c0-d076-4f50-beee-799fecdf498c)

# profolling clusters
![Screenshot 2023-12-21 123148](https://github.com/Abhishek-N-appu/Customer-churn-Clustering-analysis/assets/150499125/fee4763d-eae8-49d8-892f-cd2de2283266)
# final cluster representation
![Screenshot 2023-12-21 123339](https://github.com/Abhishek-N-appu/Customer-churn-Clustering-analysis/assets/150499125/c7823ebd-ad42-419c-a31f-48147e3ade2f)

Clusters 0 and 2 are typically -

in the Month - to Month Contract
More likely to be elderly
Does not have Online Security
Uses Fiber optic

## In Conclusion: Cluster analysis is helpful for placing customers into segments using data, which allow businesses to decide which segment(s) to target form distinct marketing mixs that will satisfy the needs and wants of each targeted Cluster.
