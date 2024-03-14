## simranandsaguni.github.io
# Food and Beverage Sales Analysis through Power BI
Food and Beverages have become an integral part of human not just for  survival but for celebration, entertainment, enjoyment and many more. While the kind of the foods we eat have greatly varied over the past years nevertheless to say, the development of the growing food and beverage culture has greatly advantaged not just the consumers but also in the sustainable development of the economy. Foods and beverages, we consumer solely reflects on our cultural aspect as well. Therefore, due to the rapid growth and development of Food and Beverage Industry, we have decided to doour project in this topic.

The following blog showcases the data visualization of sales dataset for foods and beverages industry throughout the Quarter of the year 2019. The Power BI project was created by Saguni Thapa Magar and Simran Sapkota as a pair project.

### Overview of the Sales Data
The Sales data for foods and beverages comprises information including Quantity, Product category, Product Group, Salesperson, etc. The key objective of this visualization is to understand how the revenue model and sales order for food and beverages are affected by factors such as channel, Product Category, Product Group, salesperson, etc. throughout the month and Quarter. 

The dataset is collected from Kaggle with the objective of visualizing the data.
Dataset link: https://www.kaggle.com/datasets/krishnasharangam/food-and-beverage-sales-data

#### The following are the work performed for this dataset

#### i.) Model Relationship Management: 

![Screenshot 2024-03-14 155818](https://github.com/SimranSapkota1/simransapkota/assets/159395426/9dea6596-31b3-475e-82dd-467934d7fde7)

The model relationship in powerbi shows how one data is structured and related to other data. The dataset contains one to one relationship as the information in the dataset only appears once. Therefore, the first step we followed after cleaning the data is creating a model view of one table with other table sheets within the given dataset frame.



#### ii.) Implementation of Dax Formulas: 

![Screenshot 2024-03-14 160315](https://github.com/SimranSapkota1/simransapkota/assets/159395426/9a560228-ec51-4be3-85a5-23f8254764a5)

![Screenshot 2024-03-14 160442](https://github.com/SimranSapkota1/simransapkota/assets/159395426/1cc5bd0e-d058-42b9-ae62-c1cfb504fdc5)

![Screenshot 2024-03-14 160616](https://github.com/SimranSapkota1/simransapkota/assets/159395426/279d3782-0c5b-4af9-b826-26523113fe59)

![Screenshot 2024-03-14 160729](https://github.com/SimranSapkota1/simransapkota/assets/159395426/2202c330-ae79-41af-8ee9-78934861ab91)

DAX formulas include functions, operators, and values to perform advanced calculations and queries on data in related tables and columns in tabular data models. We created a Sales Amount column, and from the new measure tool in table view through Formula Sales Amount = Sheet1[Quantity]* Sheet1[UnitPrice]. This created a total Sales Amount. This helped in the proper visualization and interpretation of the given data in the dashboard.

### Performance Measurement
![Screenshot 2024-03-14 160948](https://github.com/SimranSapkota1/simransapkota/assets/159395426/d356a3c2-0747-4163-a664-200386274ec3)

To measure the performance of the data, we used various tools like Bar Charts, Clustered Bar Charts, Donut Charts, Column Charts, Cards, etc., allowing us to interpret and understand the dataset information easily. These tools proved helpful for profitability measurement, tracking key performance indicators of Sales revenue, average order per product, customer acquisition and retention, and loss throughout the Quarters and months. Similarly, we can measure sales revenue or customer purchases on the basis of region, product categories, and varieties to identify high-profit areas so that maximum resources can be used for customer retention.
Key Findings and Managerial Insights

#### Basic Yearly Overview
![Screenshot 2024-03-14 161143](https://github.com/SimranSapkota1/simransapkota/assets/159395426/82bd05e0-4e46-4192-acd5-f21949ef81cb)

- The total revenue brought in by the food and beverage industry for the year was USD 17.91 million. There were 52.6K orders throughout the year, with an average ticket price (ATP) of USD $340.7.
- Revenue and Orders by Month: Orders and revenue both reach their highest in October, with good performance in the summer, fall, and winter months (excluding February and March).
- Revenue and Orders by Quarter: As shown in the previous chart, the highest revenue and orders are in the third and fourth quarters, which comprise the fall and winter months of the year.
- Revenue by Product Group: The standout food product is wheat flour, with its revenue being near USD 5M. The list continues with OIl, Yeast, Flour, Liquor, etc.
- Revenue and Orders by Salesperson: The highest number of orders captured by a salesperson is 9570, which is USD 4,707,402 in revenue. The salesperson's name is Carla Ferreira, highlighted in yellow in the heatmap.
- Revenue by Channel: 48% of revenue is generated by retail orders, 34% by distributors, and 17% by online channels.

#### Drill-Down through Slicer
We aim to analyze the performance of sales and beverages through product segmentation, different channels, and different quarters for which we have added slicers accordingly.

### 1. Product Segmentation

#### a). Drink

![Screenshot 2024-03-14 161444](https://github.com/SimranSapkota1/simransapkota/assets/159395426/f94ceeeb-96c9-4b1f-ab21-d2dcc42c3a83)

- The total revenue brought in by drinks for the year was USD 1.54 million. There were 5146 orders throughout the year, with an average ticket price (ATP) of USD 299.7.
- Revenue and Orders by Month: In the colder months, drink orders and revenue are relatively higher than in the warmer months. Orders and revenue both reach their highest in November and lowest in April for the year.
- Revenue and Orders by Quarter: As shown in the previous chart, the highest revenue and orders are in the fourth quarter, which comprises the colder months of the year.
- Revenue by Product Group: Hard liquor is the most standout beverage, with revenue of over USD 1M. Other drinks capture less revenue, less than USD 500k.
- Revenue and Orders by Salesperson: The salesperson captured 2429 orders, which generated revenue of USD 821,424.61. The salesperson's name is Kaua Araujo, highlighted in yellow in the heatmap.
- Revenue by Channel: 67% of drinks' revenue is captured through retail orders, and the remaining 26% is captured by distributors.

#### b). Food

![Screenshot 2024-03-14 161642](https://github.com/SimranSapkota1/simransapkota/assets/159395426/5dabdffb-58d2-418f-a4ab-68bd2d03c87d)

- The total revenue brought in by food for the year was USD 16.37 million. There were 47.4K orders throughout the year, with an average ticket price (ATP) of USD $345.2.
- Revenue and Orders by Month: In the colder months, food orders and revenue drop significantly, with the lowest of the year in February. Orders and revenue reach their highest in October, with good performance in the fall and summer months (May through January).
- Revenue and Orders by Quarter: As shown in the previous chart, the highest revenue and orders are in the third and fourth quarters, which comprise the fall and winter months of the year.
- Revenue by Product Group: The most standout food product is wheat flour, with its revenue being near USD $5M. The list then continues with OIl, Yeast, Flour, etc.
- Revenue and Orders by Salesperson: The highest number of orders captured by a salesperson is 8991, which generated USD 4,564,143.19 in revenue. The salesperson's name is Carla Ferreira, highlighted in yellow in the heatmap.
- Revenue by Channel: 46% of drinks' revenue is captured by retail orders, 34% by distributors, and the remaining 18% by online channels.

#### Managerial Insights
The analysis of the data reveals seasonal trends in beverage and food revenue. Beverage sales peak in colder months, while food sales peak in warmer months. Salesperson performance and product category dominance were also identified. These findings suggest strategic adjustments:

- Seasonality: Align marketing efforts with peak sales seasons for each category (beverages - colder months, food - warmer months).
- Sales Force: To motivate the sales team, recognize and incentivize top performers (K. Araujo - beverages, C. Ferreira - food).
- Product Mix: Analyze the top-selling products (e.g., hard liquor in beverages, wheat flour in food) and explore opportunities for range expansion or complementary product promotion.
- Distribution Channels: Optimize resource allocation across channels (retail vs. distributors) based on their contribution to revenue for each product category, as seen in the analysis of retail channels for both food and drinks. 

This data-driven approach can enhance profitability by maximizing sales opportunities and optimizing resource allocation.

### 2. Channel

#### a). Distributors: 

![Screenshot 2024-03-14 161844](https://github.com/SimranSapkota1/simransapkota/assets/159395426/d7f50f12-08ab-4524-8de7-c789af3fac22)

- Distributors' total revenue for the year was USD 6.10 million. This included 18.3K orders annually and an average ticket price (ATP) of USD 333.9.
- Revenue and Orders by Month: In the colder months, distributors' orders and revenue drop significantly, with the lowest of the year in February. The order and revenue both reach their highest in November, with good performance in the fall and winter months (May through January).
- Revenue and Orders by Quarter: As shown in the previous chart, the highest revenue and orders is in the fourth quarter, followed by the third quarter, as these quarters comprise the fall and winter months of the year.
- Revenue and Orders by Salesperson: The highest number of orders captured by a salesperson is 1455, making a revenue of USD 349,897.22. The salesperson's name is Julio Lima, highlighted in yellow in the heatmap.
- Revenue by Product Category: 93% of revenue and orders through distributors come from food, and the remaining 7% comes from drinks.

#### b).Online Channels

![Screenshot 2024-03-14 162035](https://github.com/SimranSapkota1/simransapkota/assets/159395426/c89f2b0a-27b5-42fc-b5d7-47a9d0825963)

- The total revenue brought in by online channels for the year was USD 3.11 million. It consisted of 12K orders annually with an average ticket price (ATP) of USD 258.9.
- Revenue and Orders by Month: In the spring and summer months, online channel orders and revenue drop significantly, with the lowest of the year in April. Orders and revenue both reach their highest in September, with good performance in the fall and winter months (September through January).
- Revenue and Orders by Quarter: As shown in the previous chart, the highest revenue and orders is in the third quarter, followed by the fourth quarter, as these quarters comprise the fall and winter months of the year.
- Revenue and Orders by Salesperson: The highest number of orders captured by a salesperson is 6285, which is a revenue of USD 1,678,337. The name of the salesperson is Felipe Goncalves, as highlighted in yellow in the heatmap.
- Revenue by Product Category: 97% of revenue and orders through distributors come from food, and the remaining 3% comes from drinks.

#### c). Retails:

![Screenshot 2024-03-14 162246](https://github.com/SimranSapkota1/simransapkota/assets/159395426/493f6e4f-dc38-4c7f-8d96-d8d98c74f54f)

- The total revenue brought in by retail channels for the year was USD 8.70 million. It consisted of 22.3K orders throughout the year with an average ticket price (ATP) of USD $390.6.
- Revenue and Orders by Month: In the winter months, retail channel orders and revenue drop significantly, with the lowest of the year in February. Orders and revenue both reach their highest in October, with good performance in the summer and fall months (May through October).
- Revenue and Orders by Quarter: As shown in the previous chart, the lowest revenue and orders is in the first quarter, as this quarter comprises the winter months of the year.
- Revenue and Orders by Salesperson: The most number of orders captured by salesperson is 9570 that made revenue of USD 4,767,402.55. The name of the salesperson is Carla Ferreira as highlighted by yellow in the heatmap.
- Revenue by Product Category: 88% of revenue and orders through distributors comes from food and remaining 12% comes from drink.

#### Managerial Insights

#### Channel Optimization:

- Distributors: Focus on food (especially wheat flour), with marketing aligned to colder months (peak sales). Learn from a top performer (Julio Lima) to improve your overall sales strategy.
- Online Channels: Prioritize food (esp. wheat flour) promotions during fall/winter (peak sales). Analyze top performers (Felipe Goncalves) for replicable tactics.
- Retail: Maintain focus on both food and beverages. Align promotions with seasonal trends (food peaks summer/fall, beverages peak winter). Leverage top performer (Carla Ferreira) to enhance team sales techniques.

#### Product Focus:

- Food is King: Prioritize food marketing and product development across all channels.
- Wheat Flour Powerhouse: Analyze the reasons behind wheat flour's success and consider expanding the flour range or complementary products.

#### Sales Force:

- To motivate the team, recognize and incentivize top performers (Julio Lima—Distributors, Felipe Goncalves—Online, Carla Ferreira—Retail).
- Analyze their sales strategies and share best practices to elevate overall team performance.

#### Seasonality:

- Align marketing efforts with peak sales seasons for each product category (food - warmer months, beverages - colder months) across all channels.

## Conclusion

Therefore, visualization of sales data using Power BI Desktop provides valuable insights, enabling stakeholders to make informed decisions, organizations to adapt to changing marketing dynamics, and companies to drive sustainable growth. By clearly understanding the data-driven insights, they can utilize their resources to grab and capitalize on more marketing opportunities for the future.



