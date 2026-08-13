# Maven Market - Retail Performance & Customers Analytics
A Power BI portfolio project analysing *sales performance, customer behaviour, product profitability and store performance* for a multi-national grocery retailer.

⛏️**Tools:** Power BI | DAX & Visual Calculation | Power Query | Data Modelling | Time Intelligence | Business Analysis

## ⭐ Project Overview
This project analyses the performance of Maven Market, a multi-national grocery chain with stores across Canada, Mexico and the US.

The dashboard was designed from a FP&A and commercial analytics perspective, with the objective of moving beyond descriptive reporting to identify the key drivers behind changes in *Sales, Customer behaviour, Products and Stores Performance*. It allows users to move from an executive-level view into detailed store, product and customer analysis through interactive slicers, dynamic measures and drill-through functionality.

## 🎯 Business Objectives
The dashboard was developed to help managers answer 4 key questions:

***1. How is the business performing?***
 * How are sales, transactions trending?
 * How does current performance compare with the same period last year?
 * What is the driving changes in sales revenue?
 * How are gross margin and return rate changing?

***2. Which drivers contribute the performance?***
 * Which regions and store types contribute the most sales?
 * Which stores are outperforming or underperforming?
 * Which product brands generate the most sales revenue?
 * Which areas or anomalies require further investigation?

***3. What drives customer behaviour?***
 * How many customers actively making transactions?
 * What percentage of active customers made purchases more than 1 time?
 * How many customers have returned after being inactive 90+days?
 * Is customer engagement improving or deteriorating?
 * How does Average Order Value change alongside customer and transaction growth during weekday and weekend?

***4. Where are the commercial opportunities and risks?***
 * Which products generate high revenue and high margins?
 * Which products are slow-moving?
 * Which products have higher return rates while low sales?
 * Are changes in customer retention associated with changes in product returns?
 * Which stores, regions or products should be investigated further?

## 🛠️ Key Techniques
The dashboard was built by using the following tools and technologies:
 * 💡 **Power BI Desktop:** Main business intelligence platform used for report creation which includes connecting, modelling, aggregating and visualising data
   - 🔍*Power Query* - Data transformation and cleaning process for extracting, cleaning and shaping data to prepare it for modeling and analysis
   - 🔗*Data Modeling* - Relationships established among fact tables (transactions and returns) and dimension tables (calendar, customers, products, stores and regions) to enable cross-filtering and accurate calculation
   - 🧠*Data Analysis Expressions (DAX)* + *Visual Calculations* - used for creating supporting tables, grouping and aggregating data, dynamic visuals and conditional logic
   - ⚙️*Parameters* - let users to dynamically update measures inputs to see the impact on a visual or change the metrics/dimensions shown in a visual
   - 📈*Tooltips* - hiddden custom information to be shown against the hovered product name
   - 🧐*Report Interactions* - an interactive analytical experience with drill-through, cross-visual interactions, bookmarks and page nagvigation

 * 🕵️ **Key Analytical Methods:**
   - 🏆*Top/Bottom N Analysis* - identify highes/lowest performing stores, products or brands
   - 📅*Time Intelligence* - analyse business growth trends to support performance evaluation and decision-making
   - ⚖️*Pareto Analysis* - identify the store types that drive the majority of sales (opportunity) / returns (risks), supporting more targeted resource allocation and performance management

## 💾 Data Source
This data is from Maven Market, a multi-national grocery chain with locations in Canada, Mexico and the US, including daily transactions data and returns data, details on their 10,281 customers, 1,560 products and 24 stores.

<a href="https://www.udemy.com/course/microsoft-power-bi-up-running-with-power-bi-desktop/?couponCode=26BBPAA2MX"> Data Source </a>

The transactional data covers the period from *<ins> 1 January 1997 </ins>* to *<ins> 31 December 1998 </ins>*. The date fields is shifted and extended across fact and dimension tables to align the dataset with the current reporting period and enable realistic relative-date calculations.

## 📊 Dashboard Structure
 * **Executive Dashboard:** intentionally designed as the entry point into the detailed analysis page. The objective is to answer <ins>what happened</ins> and <ins>where did it happen</ins>
   - *Overview* - provides a high-level overview of business performance in the latest period (year/quarter/month)
   - *Sales Performance* - provides a detailed-level sales performance movement over year/quarter/month
 * **Customers Analytics:** focuses on customer activity, retention and purchasing behaviour. One of the key analytical areas is the relationship between *Reactivation Rate* and *Repeat Purchase Rate*. For example, a higher reactivation rate combined with a declining repeat purchase rate may indicate that more previously 90+days inactive customers have returned, but these customers may not yet demonstrate sustained purchasing behaviour.




## Data Assumptions & Limitations


## Potential Extensions

