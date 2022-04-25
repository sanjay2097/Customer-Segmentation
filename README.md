# Customer-Segmentation

Customer segmentation is the process of grouping customers together based on common characteristics. These customer groups are beneficial in marketing campaigns, in identifying potentially profitable customers, and in developing customer loyalty.

Common types of customer segmentation include:

* Demographic segmentation

* Geographic segmentation

* Behavioral segmentation

* Psychographic segmentation

* Customer journey segmentation

Once you have these segments, you can build the right product, set the right distribution and positioning, and match the right sales motion to each customer, while also refining your segments over time. Done well, it’s a model that gives anyone at your company an immediate understanding of your customers.

![image](https://user-images.githubusercontent.com/98027899/165004448-34fab2aa-d0ec-4e08-abe0-0effa9fdd3dd.png)


However, let us also be clear on what customer segmentation is not:

* Mere intuition about customers.
* A substitute for strategy or planning.
* Judgment on which customer segment(s) to pursue.

Segmentation cannot incorporate all strategic considerations nor changes to product, pricing, and packaging over time. Instead, it’s an ongoing exercise to capture relevant differences between your customers.

### The importance of customer segmentation

For a growing business, segmentation is necessary to know your customers and your market, and share this understanding across teams. Beyond a certain size, it’s impossible to do without. At Intercom, we have benefitted from customer segmentation in these ways:

* Describing types of customers in a common way across go-to-market, product, and engineering. For example, Sales team is now able to give segmented customer feedback to our product leaders to influence our roadmap.
* Understanding our most and least engaged customers at a granular level. For example, Analytics team might find that one customer segment tends to use our product weekly, while another just monthly.
* Surfacing promising or untapped business opportunities. For example, imagine this scenario: Marketing team discovers a new segment that’s already converting well without having been explicitly targeted before.
* Enabling us to make tactical decisions with a holistic view of our customers. For example, Product team could decide to build a data export API after learning our fastest growing segment exports their conversation data far more often than other segments.
* Informing our approach to the market. For example, leadership team might decide to focus our company strategy on targeting the segments with the best revenue retention.
* Assessing progress on our marketing strategy. For example, our Finance team is now able to confirm whether new customer growth is up in our target segments.

## Problem Description
In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

## Data Description

* InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
* StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
* Description: Product (item) name. Nominal.
* Quantity: The quantities of each product (item) per transaction. Numeric.
* InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
* UnitPrice: Unit price. Numeric, Product price per unit in sterling.
* CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
Country: Country name. Nominal, the name of the country where each customer resides.
