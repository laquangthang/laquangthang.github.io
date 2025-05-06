---
layout: page
title: Walmart Ecommerce Analysis Dashboard
description: 
img: assets/img/Walmart.jpg
importance: 1
category: work
---

## About this project
- In this project, I assumed the role of a Data Analyst tasked with analyzing Walmart's ecommerce performance.<br>
- The primary goal was to create a comprehensive and interactive dashboard to provide actionable insights into sales trends, market performance, product contributions, and customer behavior. <br>
- This dashboard aims to answer critical business questions for various stakeholders (Management, Marketing, Sales, Operations): <br>

<b>Overall Performance:</b> What are the key trends in total revenue, profit, and quantity sold over time? How does current performance compare to previous periods? <br>
<b>Product & Category Analysis:</b> Which product categories drive the most revenue and profit? What is the profit margin across different categories and subcategories? What are the top-selling individual products? <br>
<b>Market Analysis:</b> How do different geographical zones compare in terms of revenue and profit generation? Which zones are performing well or need improvement? <br>
<b>Customer & Operations:</b> What are the patterns in purchasing behavior (e.g., order quantity distribution)? What is the return rate, and what are the primary reasons for product returns? <br>


## The dataset

The analysis is based on Walmart's ecommerce transaction data, encompassing the years from 2015 to 2012
The dataset presumably includes detailed information on: <br>
+ Sales transactions (Order ID, Date, Product ID, Quantity, Revenue)<br>
+ Product details (Product ID, Name, Category, Subcategory)<br>
+ Profit/Cost data (allowing calculation of Profit and Profit Margin)<br>
+ Customer/Location data (linked to orders, allowing geographic zone analysis)<br>
+ Delivery information (Delivery Type)<br>
+ Return data (Order ID, Return Reason)<br>


## Picking a stock

<h2> The report </h2>
Unlike a static PDF, the output is an interactive, multi-page dashboard. This allows stakeholders to explore the data dynamically, filter by different dimensions (Year, Category, Location, Delivery Type, Zone), and drill down into specific areas of interest. The dashboard is structured as following:
<b>Home:</b> Welcome page. <br>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Walmart_0.png" title="Home Page" 
		class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<br>

<b>Overview</b>: High-level KPIs, overall trends, and category breakdowns.<br>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Walmart_1.png" title="Overview" 
		class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<br>

<b>Market:</b> Geographic performance analysis (Zones) and top product identification.<br>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Walmart_2.png" title="Overview" 
		class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<br>

<b>Product & Customer:</b> Deeper dive into category profitability, purchasing seasonality, and return analysis.<br>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Walmart_3.png" title="Overview" 
		class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<br>

<b>Summary:</b> Intended for summarizing key findings and recommendations.<br>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Walmart_3.png" title="Overview" 
		class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<br


## Key Insights

1. <p><b>Significant Growth & Recovery:</b> While there was a slight dip around 2017-2018, Walmart's ecommerce experienced a major breakthrough in 2020, with overall Revenue, Profit, and Quantity showing strong year-over-year growth (approx. 28-29% vs previous period shown). Profit margins remained relatively stable around 56%.</p>
2. <p><b>Category Performance:</b> "Health and beauty" and "Fashion" are the leading categories for both Revenue and Profit. "Electronics" contributes the least. Interestingly, profit margins are quite similar (around 56%) across most major categories.</p>
3. <p><b>Zone Dominance & Opportunity:</b> Zone 3 significantly outperforms other zones in both Revenue and Profit, showing particularly strong growth in 2020. This highlights an opportunity to investigate and potentially replicate Zone 3's success factors in other zones (Zone 1, 2, 4). Zone 1 presents an interesting case with high profit from only one location.</p>
4. <p><b>Top Products Identified:</b> Specific products driving significant revenue were identified (e.g., Avon Soft Musk, Triple Power C20 Speaker, Yazole Watch), providing focus for marketing or inventory management.</p>
5.<p><b> Return Rate Concerns:</b> A substantial return rate of 27.18% was observed. The primary driver is "Quality-Defective item," indicating potential issues with product quality control or supplier management that need addressing. Delivery-related issues ("Missing item/part," "Wrong item") are secondary but also significant factors.</p>
6. <p><b>Purchasing Patterns:</b> The quantity per order is generally low and quite similar across transactions. Peak sales activity seems concentrated in the first five months of the year (Jan-May) and is distributed fairly evenly across the days of the week.</p>
