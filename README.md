# Retail-Store-Sales-Analysis-Using Excel

## Business Case Study
The dataset provides detailed insights into retail store transactions for July 2021 This dataset is a valuable resource for analyzing sales trends, understanding retail outlet classifications, and evaluating the performance of various channels and delivery agents.

## Business Problem
The retail company aims to optimize its operations and enhance customer satisfaction. The company seeks to uncover valuable insights to inform strategic decision-making.

- Who are the highest buying customers in terms of total purchase quantity?
- How do sales vary across different states? Can we identify regions with notable sales performance?
- Which delivery agents have consistently demonstrated top performance in terms of timely and successful order fulfillment?
- How many orders are placed for each product category, providing insights into popular and less popular items?
- What is the distribution of shipping statuses based on the classification of retail outlets?
- Which states exhibit high sales volumes, and how does this vary across different sales channels?
- Can we identify delivery agents with a track record of underperformance or delayed deliveries?

The analysis aims to provide actionable insights for the company, facilitating targeted strategies to improve customer satisfaction, optimize inventory, and enhance overall operational efficiency.

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
1. Who are the highest buying customers in terms of total purchase quantity?

![Top 10 Customeras](https://github.com/tolulopeoa/Excel-Retail-Store-Sales-Analysis/assets/102050942/f388093e-a14f-486d-8bee-6815848c6dcf)
This chart highlights the top 10 customers contributing significantly to the total purchase quantity.

 #### Top Customer with the Highest Order:
 - **Customer Name:** Iya Ruka K Store
 - **Total Purchase Quantity:** 752
   

2. How do sales vary across different states? Can we identify the states with notable sales performance?

![Sales performance by states](https://github.com/tolulopeoa/Excel-Retail-Store-Sales-Analysis/assets/102050942/86f01f04-9b83-43ba-95b8-ade169aaf3c8)
The chart reveals significant variation in sales across different states. The top-performing states, based on the sum of sales price, are as follows:

 - **Lagos:** $247,780
 - **FCT:** $48,080
 - **Ogun:** $41,705

On the other hand, some states have relatively lower sales figures, with the lowest being in **Soweto** at $23 and **Katlehong** at $28.

This highlights the disparities in sales performance among states, with Lagos standing out as the leading contributor to overall sales. Understanding these variations can guide strategic decision-making for targeted marketing and resource allocation.


3. Which delivery agents have consistently demonstrated top performance in terms of timely and successful order fulfillment?

![Top Delivery Agents](https://github.com/tolulopeoa/Excel-Retail-Store-Sales-Analysis/assets/102050942/26854c57-6196-407e-84b5-4295ff3e4663)
The analysis identifies delivery agents who have consistently demonstrated top performance in terms of timely and successful order fulfillment. The two delivery agents with the highest number of successful deliveries are:

 - **Kagiso Katlego:** 1313 deliveries
 - **Nomfundo Sibongile:** 1309 deliveries

These delivery agents stand out for their reliability and efficiency in ensuring that orders are delivered on time, contributing significantly to overall customer satisfaction and fulfillment success.

