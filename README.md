# AM10_Group_2
![logo](olist_logo.jfif "logo")

## What is your topic? 
* Analysis on Brazilian e-commerce website 

## What issues or questions are you addressing? 
* Where are customers and sellers located? Are there certain regions which have a higher percentage of buyers when compared to sellers? We may also be interested in comparing economic data in Brazil or specific cities with where purchases are located and the value. We will do a heatmap on geolocations of orders and sales. 
* Are there any seasonal patterns in sales in Brazil? We will use the datetime and total sales for each day/month/quarter to see the time series trend of sales on Olist. 
* Who should Olist target based on customer segmentation? We will cluster customers by how many return purchases they made and how much revenue they brought. 
* Do certain product types (that are sold and exchanged on Olist) typically get higher ratings than others? We can look at the lower rating product categories and make recommendations to improve the general service for those categories. 

## What is the source of the data you will be using?
* https://www.kaggle.com/olistbr/brazilian-ecommerce/
* A brief schema of the dataset is shown below. 

![schema](schema.png "schema")


## Structure and 'Story' of our analysis. 

The main aim of this project is to analyse data associated with the retailer 'OList' in Brazil, to see if we can develop insights and suggestions that may improve the company's business operations. 

In particular we will begin by focusing on regional/geographical factors - by trying to understand the geographical characteristics of OList's consumer base and use these to develop strategic insights. We will analyse the regions within which the majority of OList's buyers and sellers are located - to help us build an approximate consumer profile. The visualisations produced highlight that there is not a significant difference in the regional locations of our buyers and our sellers, and that both are typically focused around the more urban areas of Brazil in the Southeastern regions. 

Understanding that the typical OList consumer lives in urban areas of Brazil, we can use this information to focus more specifically on the delivery and logistics services between cities to see if these can be improved to draw further consumer utility and ultimately further profits. We will examine the primary transmission routes (seller to buyer) for products and also look at their average delivery times, to work out where logistical strategies should be targeted. It is possible that delivery between certain key cities is hindering the quality of OList's services - this is something that needs to be addressed. 

We will also compare the average spending power per customer with the average GDP per capita in each of these major Brazilian cities, to see if any cities are not being adequately exploited by OList. This will allow us to suggest potential growth strategies based on an understanding of which key areas of Brazil are using OList services less than they potentially should be. 

Once we have analysed the regional characteristics of the consumer base, and made suggestions that could improve growth and better exploit certain regional discrepancies and opportunities, we will focus more on the social/demographic characteristics, to see which demographic consumer bases are most common and which product types are most frequently purchased. This will allow us to see which products are being sold most effectively. We will also look at customer satisfaction to determine which product types are not being well handled by OList - we will attempt to understand why this is and also suggest potential improvements for how OList can improve customer satisfaction for certain product types. 

Finally, once we have better understood the main regional and demographic concerns, as well as the most (and least) successful OList products, we will examine the effects of vouchers on consumer behaviours. This will offer a final insight into whether promotional strategies surrounding discounts/vouchers may be effective in drawing further profit. This may help inform our framework for future promotional strategies


## What statistical techniques do you think you may be using?
* We used linear regression to see the courier efficiency.  
* Basic statistical techniques (mean, median, percentage, standard deviation, etc.).
