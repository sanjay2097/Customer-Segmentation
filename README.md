# Customer-Segmentation
![image](https://user-images.githubusercontent.com/98027899/165004448-34fab2aa-d0ec-4e08-abe0-0effa9fdd3dd.png)

### Objective:

### In this project, our task was to identify major customer segments on a transnational data set with 55,000 records which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

### Customer segmentation is the process of grouping customers together based on common characteristics. These customer groups are beneficial in marketing campaigns, in identifying potentially profitable customers, and in developing customer loyalty.Once you have these segments, you can build the right product, set the right distribution and positioning, and match the right sales motion to each customer, while also refining your segments over time. Done well, it’s a model that gives anyone at your company an immediate understanding of our customers.

### **Common types of customer segmentation include**:

* Demographic segmentation

* Geographic segmentation

* Behavioral segmentation

* Psychographic segmentation

* Customer journey segmentation

### Once you have these segments, you can build the right product, set the right distribution and positioning, and match the right sales motion to each customer, while also refining your segments over time. Done well, it’s a model that gives anyone at your company an immediate understanding of your customers.

![image](https://user-images.githubusercontent.com/98027899/173230905-089dadc7-3481-4ea1-8874-9091764854b1.png)


### **Data Description** :

* InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
* StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
* Description: Product (item) name. Nominal.
* Quantity: The quantities of each product (item) per transaction. Numeric.
* InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
* UnitPrice: Unit price. Numeric, Product price per unit in sterling.
* CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
* Country: Country name. Nominal, the name of the country where each customer resides.

![image](https://user-images.githubusercontent.com/98027899/173230909-11205aa2-8f1c-4476-92d9-37b58d212c7d.png)

### **Project Details** :

### Most of the data available in our dataset is from UK
![download](https://user-images.githubusercontent.com/98027899/173230399-f27a7f6a-1629-478a-950c-322d6228504b.png)

### Hourly, Weekly, and Monthly analysis
![download (1)](https://user-images.githubusercontent.com/98027899/173230515-314a7c93-3d2e-4498-9092-bbcae222309c.png)

### Average Revenue Per Month
![download (2)](https://user-images.githubusercontent.com/98027899/173230528-7f0500d1-c838-48ad-9da5-5ef64426983b.png)

### Average Revenue Per Day
![download (3)](https://user-images.githubusercontent.com/98027899/173230556-27ff0032-8d98-4c8d-a706-3db137c9fc75.png)

### Correlation heatmap between Recency, Freqency and Monetary scores
![download (4)](https://user-images.githubusercontent.com/98027899/173230589-9eaabec5-8af9-4e60-bd7b-92e5a93edc29.png)

### Distribution of RFM scores for every unique customer in dataset
![download (5)](https://user-images.githubusercontent.com/98027899/173230632-2db73a4b-4f7d-4ebe-996b-1065bb574271.png)

### Silhouette Score for KMeans Clustering
![download (6)](https://user-images.githubusercontent.com/98027899/173230670-313fa738-abfa-4ad6-9c33-d4ec0219843f.png)

### Pointplot for visualizing the seperate clusters
![download (7)](https://user-images.githubusercontent.com/98027899/173230711-614b1af0-fbef-4d99-af68-2a836d0d4264.png)

![image](https://user-images.githubusercontent.com/98027899/173230915-d4c79503-eb11-4024-bc69-53999cf20d91.png)

### **Conclusion** :
### We have engineered features to obtain new features such as RFM, RFMGroup, and RFMScore for getting more details of customers' purchasing behaviour.We have employed use of unsupervised learning algorithms KMeans and Hierarchical Agglomerative clustering to segment the customers into 2 major groups.We have achieved Silhouette score of 40% and generated optimal number of clusters for best and worst costomers.

![image](https://user-images.githubusercontent.com/98027899/173230917-6498e61f-1214-4366-8c28-cc38e920e44c.png)

### **Scope** :

### Consumer segmentation enables us to uncover valuable audience insights that can help to dictate the content, targeting and media buying strategy of our digital campaigns. It allows us to understand which audiences exist, who to target and why, and the most effective way to reach them.We have grouped our wholesale customer base into two major segments one comprising best customers with high recency frequency and monetary scores while other on the lowest side.This will help us in formulating marketing strategies and build the right product to boost sales.

![image](https://user-images.githubusercontent.com/98027899/173230923-3cc7d6d0-b9c3-4652-b82e-e0c56168c9c4.png)

### **References** :

https://www.shopify.in/encyclopedia/customer-segmentation

https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html











