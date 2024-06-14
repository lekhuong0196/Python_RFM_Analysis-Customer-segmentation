# PYTHON_RFM_ANALYSIS-CUSTOMER-SEGMENTATION
# I. INTRODUCTION
## 1. About RFM Analysis
**Why RFM?**

 •	RFM (Recency, Frequency, Monetary) analysis is a marketing model using customer segmentation based on their transaction history.

 •	This model could be very useful, especially for small and medium-sized enterprises (SMEs) with limited marketing resources, helping them focus on the potentially right customer segments to increase ROI, reduce churn, reduce cost, improve customer relationship, and a lot more.

**How?**

•	In RFM analysis, customers are scored based on three factors (Recency - how recently, Frequency - how often, Monetary - how much), then labeled based on the combination of RFM scores.

## 2. Dataset

This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

•	**InvoiceNo**: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'C', it indicates a cancellation.

•	**StockCode**: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.

•	**Description**: Product (item) name. Nominal.

•	**Quantity**: The quantities of each product (item) per transaction. Numeric.

•	**InvoiceDate**: Invoice Date and time. Numeric, the day and time when each transaction was generated.

•	**UnitPrice**: Unit price. Numeric, Product price per unit in sterling.

•	**CustomerID**: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.

•	**Country**: Country name. Nominal, the name of the country where each customer resides.

![image](https://github.com/lekhuong0196/Python_RFM_Analysis-Customer-segmentation/assets/138196501/fb30c113-bd93-4ced-8da5-4c411aa8fbeb)

## 3. RFM model

•	RFM is a method used for analyzing customer value. It is commonly used in database marketing and direct marketing and has received particular attention in retail and professional services industries

•	RFM stands for the three dimensions:

i.	**Recency** – How recently did the customer purchase?

ii.	**Frequency** – How often do they purchase?

iii.	**Monetary Value** – How much do they spend?

•	RFM analysis numerically ranks a customer in each of these three categories, generally on a scale of 1 to 5 (the higher the number, the better the result). The “best” customer would receive a top score in every category.

 ![image](https://github.com/lekhuong0196/Python_RFM_Analysis-Customer-segmentation/assets/138196501/ec92ed96-2350-4b8d-9ede-fa63acee43e4)

## 4. Business questions

•	Which customer segment has the highest potential for profitability?

•	What marketing programs should be implemented for each customer segment?

•	How to track the effectiveness of marketing programs implemented for each customer segment?

•	How to improve the effectiveness of the FRM segmentation model?
# II. DATA VISUALIZATION WITH PYTHON

**Distribution chart for each variable of the model**
![image](https://github.com/lekhuong0196/Python_RFM_Analysis-Customer-segmentation/assets/138196501/ea8d1ef0-707f-4c12-88f1-6cc5fe479801)
![image](https://github.com/lekhuong0196/Python_RFM_Analysis-Customer-segmentation/assets/138196501/ee2c511d-b4b3-45ee-942a-2b466f76215c)
![image](https://github.com/lekhuong0196/Python_RFM_Analysis-Customer-segmentation/assets/138196501/19c8b86c-183f-48a1-b7d6-f1fbb33693bd)
**Treemap of RFM segments of customer count**
![image](https://github.com/lekhuong0196/Python_RFM_Analysis-Customer-segmentation/assets/138196501/e469167b-ce11-4edc-9f82-0b349686e52e)
**Treemap of RFM segments of total sales**
![image](https://github.com/lekhuong0196/Python_RFM_Analysis-Customer-segmentation/assets/138196501/53ea2a4e-6297-46fc-81be-34b96641be17)
# III. INSIGHTS
•	2 segments with the highest proportion of customers are Champions (19.21%) and Hibernating custumers (16.28%)

•	Negative segments such as Hibernating and Lost accounted for a high proportion of customers, 16.28% and 11.15%, respectively. However, these two groups account for less than 8% of total sales

•	The two most positive segments both account for a high proportion of total sales (Champion (60.88%) and Loyalty (11.89%). This is a good sign for the company and in upcoming marketing campaigns, the company needs to have campaigns to maintain and develop this customer segment.

# IV. RECOMMENDATIONS

**•	The company needs to have policies to:**

**•	Positive customers:**

-	For new customers who have made a recent purchase, send a personalized welcome email or offer that thanks them for their purchase and encourages them to return to our business.

-	For customers who have made a high-value purchase ( Champions, loyar), thank them for their business and offer a loyalty program that rewards them for their continued purchases.

**•	Negative customers:**

-	For hibernating customers who have not made a purchase in a while, send a win-back email or offer that encourages them to return to our business.
  
-	For customers who have made multiple purchases in the past but have not made one recently, send personalized email campaigns that showcase new products or services that may be of interest to them.
  
-	For high-value customers who have not made a purchase in a while, send a personalized email or offer that highlights new products or services that may be of interest to them and offer a special discount or promotion that is tailored to their past purchase history.

