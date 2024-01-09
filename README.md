# Retail-Store-Sales-Analysis-Using Excel

## Business Case Study
The dataset provides detailed insights into a retail store transactions for July 2021. This dataset is a valuable resource for analyzing sales trends, understanding retail outlet classifications, and evaluating the performance of various channels and delivery agents.

## Business Problem
The retail company aims to optimize its operations and enhance customer satisfaction. The company seeks to uncover valuable insights to inform strategic decision-making.

- Who are the highest buying customers in terms of total purchase quantity?
- How do sales vary across different states? Can we identify regions with notable sales performance?
- Which delivery agents have consistently demonstrated top performance in terms of timely and successful order fulfillment?
- How many orders are placed for each product category, providing insights into popular and less popular items?
- What is the distribution of shipping statuses based on the classification of retail outlets?
- Which states exhibit high sales volumes, and how does this vary across different sales channels?
- Can we identify producers with low sales figures?

The analysis aims to provide actionable insights for the company, facilitating targeted strategies to improve customer satisfaction, optimize inventory, and enhance overall operational efficiency.

## Excel Tools Used

1. **SUM:** Utilized for aggregating total quantities, sales figures, and other numeric data.

2. **AVERAGE:** Applied to calculate average values for specific metrics.

3. **IFS:** Employed to filter and analyze data based on multiple conditions, facilitating nuanced insights.

4. **Pivot Tables:** Used for dynamic data summarization, providing a comprehensive view of various aspects of the dataset.

5. **Charts:** Utilized for visual representation, including line charts to depict sales figures by states and other relevant visualizations for enhanced interpretation.


## Data Transformation

### Sales Figure Calculation:
To derive the sales figure, we need to consider the unit price in both Naira (NGN) and South African Rand (ZAR) and multiply them by order quantity.

![Sales](https://github.com/tolulopeoa/Excel-Retail-Store-Sales-Analysis/assets/102050942/10efc54a-c6dc-4791-9656-e469d88e7b12)

### Currency Conversion:
Create a new column 'Sales (USD)' by converting the 'Sales' to dollars based on the respective country's exchange rate provided in the 'Details' sheet.

![Sales USD](https://github.com/tolulopeoa/Excel-Retail-Store-Sales-Analysis/assets/102050942/c6ecd81e-2a74-49fc-8022-92557497c616)

### Order Categorization:
To better understand the order categories, a new column 'Order Category' will be generated based on the following rules:
- 'Low End' orders: Quantity between 0 and 100
- 'Mid End' orders: Quantity between 101 and 300
- 'High End' orders: Quantity between 301 and 1000
  
![Quantity Category](https://github.com/tolulopeoa/Excel-Retail-Store-Sales-Analysis/assets/102050942/bb25ae09-923f-4fdb-a9da-390f0717a861)

## Findings
1. #### Who are the highest buying customers in terms of total purchase quantity?

![Top 10 Customeras](https://github.com/tolulopeoa/Excel-Retail-Store-Sales-Analysis/assets/102050942/f388093e-a14f-486d-8bee-6815848c6dcf)
This chart highlights the top 10 customers contributing significantly to the total purchase quantity.

 #### Top Customer with the Highest Order:
 - **Customer Name:** Iya Ruka K Store
 - **Total Purchase Quantity:** 752
   

2. #### How do sales vary across different states? Can we identify the states with notable sales performance?

![Sales performance by states](https://github.com/tolulopeoa/Excel-Retail-Store-Sales-Analysis/assets/102050942/86f01f04-9b83-43ba-95b8-ade169aaf3c8)
The chart reveals significant variation in sales across different states. The top-performing states, based on the sum of sales price, are as follows:

 - **Lagos:** $247,780
 - **FCT:** $48,080
 - **Ogun:** $41,705

On the other hand, some states have relatively lower sales figures, with the lowest being in **Soweto** at $23 and **Katlehong** at $28.

This highlights the disparities in sales performance among states, with Lagos standing out as the leading contributor to overall sales. Understanding these variations can guide strategic decision-making for targeted marketing and resource allocation.


3. #### Which delivery agents have consistently demonstrated top performance in terms of timely and successful order fulfillment?

![Top Delivery Agents](https://github.com/tolulopeoa/Excel-Retail-Store-Sales-Analysis/assets/102050942/26854c57-6196-407e-84b5-4295ff3e4663)
The analysis identifies delivery agents who have consistently demonstrated top performance in terms of timely and successful order fulfillment. The two delivery agents with the highest number of successful deliveries are:

 - **Kagiso Katlego:** 1313 deliveries
 - **Nomfundo Sibongile:** 1309 deliveries

These delivery agents stand out for their reliability and efficiency in ensuring that orders are delivered on time, contributing significantly to overall customer satisfaction and fulfillment success.


4. #### How many orders are placed for each product category, providing insights into popular and less popular items?
   ![Orders by Product Category](https://github.com/tolulopeoa/Excel-Retail-Store-Sales-Analysis/assets/102050942/d259db9c-e5ce-4075-aa6a-ba26559701de)
The analysis provides insights into the distribution of orders across different product categories, shedding light on popular and less popular items. Here are the findings:

- **Top Product Category:** Food, with the highest number of orders (13058).
- **Least Product Category:** Wine & Spirits, with the lowest number of orders (228).

Understanding the order distribution across product categories is crucial for inventory management and meeting customer demand effectively.


5. #### What is the distribution of shipping statuses based on the classification of retail outlets?
   ![Outlet type shipping status](https://github.com/tolulopeoa/Excel-Retail-Store-Sales-Analysis/assets/102050942/97501de4-8158-4b86-89ee-1ab2851c6720)
The chart explores the distribution of shipping statuses across different retail outlet types. Here are the findings:

- **Outlet Type with the Most 'Delivered' Shipping Status:** Convenience Store, with 2761 successful deliveries.

Understanding the shipping status distribution by outlet type is valuable for optimizing delivery processes and addressing any issues that may arise in specific types of retail outlets.


6. #### Which states exhibit high sales volumes, and how does this vary across different sales channels?
   ![Sales across Sales Channels in different states](https://github.com/tolulopeoa/Excel-Retail-Store-Sales-Analysis/assets/102050942/242af758-1538-474d-94e4-77cf0a6cf890)
The analysis investigates sales volumes across different states based on various sales channels. 

- **Top 3 Leading States by Sales Volume:**
  1. Gauteng: Not actively engaged in Field Sales, but it dominates in Mobile App sales.
  2. Lagos: Significant sales across Mobile App and Telesales.
  3. Ogun: Higher sales in Telesales compared to Mobile App.

Understanding the sales distribution across states and sales channels is crucial for tailoring marketing and operational strategies to maximize revenue.

7. #### Can we identify producers with sales figures of below $10,000?
   ![Producers with Sales Figures Below $10,000](https://github.com/tolulopeoa/Excel-Retail-Store-Sales-Analysis/assets/102050942/095c20f3-9615-43c0-bf28-83dda2fe9e5c)

The producers listed above have sales figures below $10,000. This insight is valuable for assessing the performance of individual producers and exploring potential strategies to enhance their sales performance.

## Conclusion

In this comprehensive analysis of the dataset of a Retail store orders in July 2021, we explored various aspects of the sales and delivery ecosystem. From identifying top customers and high-performing states to evaluating delivery agents' efficiency and categorizing products, the analysis provides valuable insights. The examination of sales across different channels and the identification of producers with specific sales figures further contribute to a holistic understanding of the business landscape. These insights can guide strategic decisions, optimize operations, and enhance overall business performance.

## Recommendation

- Prioritize engagement strategies with top customers like "Iya Ruka K Store" and "Ym Stores" to foster loyalty and increase sales.

- Allocate marketing resources based on state-wise sales performance, with a focus on boosting sales in high-performing states like Lagos.

- Recognize and incentivize top-performing delivery agents, specifically Kagiso Katlego and Nomfundo Sibongile, to maintain high-quality service.

- Optimize inventory and promotions based on popular product categories such as "Food" while addressing potential gaps in less popular categories.

- Tailor strategies for different outlet types, with a focus on convenience stores where successful deliveries are more prominent.

- Implement targeted campaigns across sales channels, especially mobile app and telesales, in high-sales states like Gauteng and Lagos.

- Collaborate with producers like PZ Cussons Nigeria Plc and Extreme Manufacturing Nig Ltd to explore opportunities for increasing sales beyond the $10,000 threshold.
