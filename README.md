# AM10_Group_2
## What is your topic? 
* Analysis on Brazilian e-commerce website 

##What issues or questions are you addressing? 
* Where are customers and sellers located? Are there certain regions which have a higher percentage of buyers when compared to sellers? We may also be interested in comparing economic data in Brazil or specific cities with where purchases are located and the value. We will do a heatmap on geolocations of orders and sales. 
* Are there any seasonal patterns in sales in Brazil? We will use the datetime and total sales for each day/month/quarter to see the time series trend of sales on Olist. 
* Who should Olist target based on customer segmentation? We will cluster customers by how many return purchases they made and how much revenue they brought. 
* Do certain product types (that are sold and exchanged on Olist) typically get higher ratings than others? We can look at the lower rating product categories and make recommendations to improve the general service for those categories. 

##What is the source of the data you will be using?
* https://www.kaggle.com/olistbr/brazilian-ecommerce/
* A brief schema of the dataset is shown below. 

![schema](schema.png "schema")


##What statistical techniques do you think you may be using?
* We can compare ratings of product categories by using confidence intervals to see if they are significantly different. 
* We will use K-means or K-nearest-neighbour (KNN) for clustering customers.
