# [Power BI] E-commerce Analysis Project

## I.Introduction
The project involves the business request to maximize GMV and optimize spending of the company by identifying and measuring key metrics to analyse the company performance and deliver insights for improvements.

## II. Dataset
To access to the datasets, please refer to the [link](https://drive.google.com/drive/folders/1RAYr-8jxwVvEcV9kU2rps7Qh-HAnslPl?usp=drive_link)


## III. Design thinking approach
### Step 1. Empathize 
#### 5W-1H
| Question | Answer |
|----------|--------|
| **Who will see the dashboard?** | Marketing team, Sales team, E-commerce team |
| **If we have to choose only one stakeholder, who will be?** | E-commerce team |
| **What problem will the dashboard help to solve?** | Business objectives: To maximize the GMV (gross merchandise volume) <br> The dashboard will provide an overall-to-detail picture of business performance of the e-commerce company, point out the key insights which support decision-making process for the next strategies |
| **Where and when will our stakeholders see the dashboard?** | In the meeting, in the presentation session or anywhere that they have to make decisions |
| **Why do we have to build the dashboard?** | Our stakeholders will need the dashboard to see the overall performance, then zoom into the trends, insights, outliers for further strategies. |
| **How will our stakeholders see the dashboard to solve their business objectives?** | They have to see the overall performance then zoom into divided layers like customers, services, etc. |

#### Empathy map
| Category | Description |
|----------|------------|
| **Thinking and feeling** <br> What does the user/customer think and feel? | The business performance fluctuates, and they wonder about the reasons behind it. <br> When they present, their superiors/subordinates will ask them why in details. <br> They feel confused and hard to find the insights. |
| **Seeing** <br> What does the customer/user see? | They see the overall business picture with different kinds of reasons behind, they cannot see the exact reasons that lead to that business situation. |
| **Saying and doing** <br> What does the customer/user say? | "We need to be more data-driven" <br> They seek for data and visualization that supports their decision-making process. |
| **Pains** <br> What are the biggest problems and challenges? | Insufficient data and information may lead to inefficient solutions. |
| **Gains** <br> What are the opportunities and benefits? | Key insights, unmet needs, straight-to-the-point strategies, data-driven solutions. |

### Step 2. Ideate
#### Issues trees
<img width="787" alt="Image" src="https://github.com/user-attachments/assets/a1d43f31-b394-4f17-83f2-8ce1032f7171" />

#### Northstar metrics
| **Question** | **Answer** |
|-------------|-----------|
| **What VALUE you want to measure?** | Sales, Average deal size, Orders, Repeated customers |
| **WHEN the value DELIVERY SUCCESS?** | When these two metrics reach its maximum value. |
| **WHY do you choose this metric?** | - **Sales revenue** shows the total monetary value generated, reflecting profitability and financial health. <br> - **Average deal size** provides insights into which products are driving revenue growth. Companies can use this information to adjust their product offerings, pricing strategies, and sales tactics to focus on higher-value opportunities. <br> - **Order** indicates transaction volume, providing insights into customer demand, purchase frequency, and conversion rates. <br> - **Repeated customers** provides insights into customer loyalty, satisfaction, and the effectiveness of the company's products or services. By monitoring and improving the rate, companies can enhance customer satisfaction, increase revenue, and strengthen their competitive position in the market, which drives long-term business growth. |

#### Point of view
| **DIMENSION GROUP** | **Group 1** | **Group 2** | **Group 3** |
|--------------------|------------|------------|------------|
| **Group Name**    | Time       | Product    | Region     |

| **View** | **Description** | **Why** |
|------------------|---------------|---------|
| **View 1: Sales Analysis (sales + average deal size)** | Total sales, sales by time period, sales by product, sales by region | To see sales performance over the periods, which product has the highest/smallest sales, which region contributes the most/least to sales, average deal size of top products |
| **View 2: Customer Analysis <br> (customers + orders)** | Total customers, total repeat customers, total orders, orders by time periods, orders by product, orders by region | To determine transaction volume, customer demand |
| **View 3: Service Analysis** | Average delivery time, review score, distribution of review score | To find out the reasons/insights which affect sales |

## IV. Dashboard
<img width="1323" alt="Image" src="https://github.com/user-attachments/assets/10f44605-7aac-41a2-83cf-a370830cc1b6" />

<img width="1323" alt="Image" src="https://github.com/user-attachments/assets/651aaa86-5b0f-4932-ba9b-3cc61af91adf" />

<img width="1323" alt="Image" src="https://github.com/user-attachments/assets/d0a1e9f6-7e8f-4b25-9e17-0ec4c04b2344" />

## V. Key findings and Recommendations
### 1. Key findings
#### Sales Performance Analysis
- The high GMV categories include health & beauty, watches & gifts, and bed & bath, which are the top contributors to sales.
- Furniture mattresses, music, and flowers have the least sales.
- Sales show a strong upward trend until mid-2018, followed by a decline.
- The average deal size is **$165.93**, with high-value categories contributing the most revenue.


#### Customer Behavior
- The repeat customer rate is low, with only 3.5% making more than one purchase.
- Regarding geographical concentration, sales are significantly concentrated in **SP (41.75K orders), RJ (13K orders), and MG (12K orders)**.
- **73.92%** of customers use credit cards.
- The peak order volume occurred in the first quarter of 2018, followed by a significant decline.

#### Service & Customer Experience
Orders with faster shipping times of less than 30 days received significantly higher review scores, while delayed deliveries were closely linked to lower customer satisfaction.

### 2. Recommendations
#### Boost Sales in High-GMV Categories
- Expand and promote top-selling categories like health & beauty, watches, and bed & bath.
  - Introduce bundling discounts or subscription models for these categories.
  - Offer limited-time deals to sustain demand in peak seasons.
  
- Fix Low-GMV Categories: Reduce SKUs or reposition categories like furniture mattresses and flowers with better promotions or improved supply chain efficiency.

#### Improve Customer Retention & Repeat Purchases
- Loyalty Programs: Since 97% of customers purchase only once, introduce:
  - A loyalty rewards system with discounts on repeat purchases.
  - Personalized product recommendations via email/SMS based on past purchases.
- Target High-Value Regions: Focus on SP, RJ, and MG with:
  - Localized marketing campaigns.
  - Faster fulfillment centers to reduce delivery time.

#### Optimize Service & Logistics
- Reduce Delivery Time: Since long delivery times impact review scores, implement:
  - More regional fulfillment centers in top-order states (SP, RJ, MG).
  - Express delivery options for premium customers.

- Improve Order Status & Transparency:
  - Automate order updates to reduce cancellations.
  - Optimize inventory to ensure product availability.













