# Sales Data Analysis Report

## 1. Introduction

This report presents an analysis of the sales data contained in the **Excel Sales Report** dataset. The objective of the analysis is to understand the company's sales performance, identify the major revenue drivers, evaluate customer and sales-channel performance, and provide actionable recommendations for improving future sales.

The dataset contains **2,000 sales transactions** recorded throughout **2026**. The analysis focuses on revenue, quantity sold, product categories, regions, sales channels, customer types, discounts, products, and salesperson performance.

The analysis is intended to answer important business questions such as:

- What is the overall sales performance?
- Which regions generate the highest revenue?
- Which sales channels perform best?
- Which product categories contribute most to revenue?
- How important are returning customers?
- Which products generate the most revenue?
- What strategies can be used to improve sales performance?


# 2. Data Description

The dataset consists of **2,000 unique sales transactions** with **12 variables**.

### Dataset Summary

| Metric | Value |
|---|---:|
| Total Transactions | 2,000 |
| Total Revenue | $2,452,084.30 |
| Total Quantity Sold | 5,552 |
| Average Revenue per Transaction | $1,226.04 |
| Average Quantity per Transaction | 2.78 |
| Number of Regions | 5 |
| Number of Sales Channels | 4 |
| Number of Customer Types | 2 |
| Number of Product Categories | 6 |
| Number of Products | 28 |
| Number of Salespeople | 15 |
| Data Period | January - December 2026 |

### Variables

| Variable | Description |
|---|---|
| `Order ID` | Unique identifier for each transaction |
| `Date` | Date on which the transaction occurred |
| `Region` | Geographical region where the sale occurred |
| `Sales Channel` | Channel through which the product was sold |
| `Customer Type` | Indicates whether the customer is new or returning |
| `Product Category` | Category to which the product belongs |
| `Product` | Specific product sold |
| `Salesperson` | Employee responsible for the sale |
| `Quantity` | Number of units purchased |
| `Unit Price` | Price per unit before discount |
| `Discount` | Discount percentage applied to the transaction |
| `Revenue` | Revenue generated from the transaction |

### Data Quality

The dataset was checked for missing values and duplicate records.

- There are **no missing values**.
- There are **no duplicate rows**.
- All **2,000 Order IDs are unique**.
- The dataset contains records covering the full year from **January 1, 2026 to December 31, 2026**.
- Numerical fields such as quantity, unit price, discount, and revenue contain valid values.

Therefore, the dataset was considered sufficiently clean for analysis.


# 3. Methodology

The analysis followed a structured data-analysis process.

### Step 1: Data Inspection

The Excel workbook was examined to understand:

- Number of records
- Number of variables
- Data types
- Missing values
- Duplicate records
- Date range
- Categorical variables
- Numerical variables

### Step 2: Data Cleaning

The following checks were performed:

- Checked for missing values
- Checked for duplicate transactions
- Verified unique Order IDs
- Confirmed date formats
- Reviewed numerical fields
- Checked categorical variables for consistency

No major data-cleaning issues were identified.


### Step 3: Descriptive Analysis

Descriptive statistics were calculated for:

- Total revenue
- Total quantity sold
- Average revenue per transaction
- Average quantity per transaction

### Step 4: Group Analysis

Revenue and transaction performance were analyzed by:

- Region
- Sales channel
- Customer type
- Product category
- Product
- Month


### Step 5: Business Insights

The results were interpreted to identify opportunities for:

- Revenue growth
- Customer retention
- Product prioritization
- Sales-channel optimization
- Regional improvement
- Discount management


# 4. Analysis & Findings

## 4.1 Overall Sales Performance

The business generated approximately **$2.45 million in revenue** from **2,000 transactions** during 2026.

The dataset recorded a total of **5,552 units sold**, giving an average of approximately **2.78 units per transaction**.

The average revenue generated per transaction was approximately **$1,226.04**.

### Key Findings

- Total Revenue: **$2,452,084.30**
- Total Orders: **2,000**
- Total Units Sold: **5,552**
- Average Order Revenue: **$1,226.04**
- Average Units per Order: **2.78**

The relatively high average revenue per transaction suggests that the business generates substantial value from individual orders, particularly through higher-priced technology products.


# 4.2 Monthly Revenue Analysis

Revenue varied considerably throughout the year.

| Month | Revenue |
|---|---:|
| January | $168,680.63 |
| February | $173,605.25 |
| March | $236,738.70 |
| April | $241,034.34 |
| May | $153,642.43 |
| June | $258,658.95 |
| July | $150,713.14 |
| August | $185,321.62 |
| September | $233,080.36 |
| October | $189,721.57 |
| November | $274,368.31 |
| December | $186,519.01 |

### Findings

**November** generated the highest monthly revenue at approximately **$274,368.31**.

The second-highest month was **June**, with approximately **$258,658.95**.

**July** recorded the lowest revenue at approximately **$150,713.14**, followed closely by May.

The results show significant monthly fluctuations rather than consistent revenue throughout the year.

### Interpretation

The strong performance in November may indicate increased customer demand during promotional or end-of-year shopping periods.

The weaker performance in May and July suggests that the company may need targeted promotions or campaigns during slower periods.

# 4.3 Regional Sales Performance

The company operates across five regions:

| Region | Revenue | Revenue Share |
|---|---:|---:|
| North | $561,753.72 | 22.91% |
| Central | $556,705.18 | 22.70% |
| East | $467,808.85 | 19.08% |
| South | $444,494.30 | 18.13% |
| West | $421,322.25 | 17.18% |

### Findings

The **North** region generated the highest revenue, closely followed by the **Central** region.

The **West** region generated the lowest revenue.

### Key Observation

The difference between the highest and lowest regions is approximately:

**$561,753.72 - $421,322.25 = $140,431.47**

This indicates a meaningful performance gap between regions.

### Interpretation

North and Central appear to be the strongest regional markets and could provide useful insights into successful sales strategies.

The West region may require further investigation to determine whether its lower performance is caused by:

- Lower customer demand
- Fewer transactions
- Product availability
- Salesperson performance
- Distribution challenges
- Lower marketing activity

  # 4.4 Sales Channel Analysis

Revenue was distributed across four sales channels.

| Sales Channel | Revenue | Revenue Share |
|---|---:|---:|
| Online | $791,536.99 | 32.28% |
| Corporate Sales | $718,745.00 | 29.31% |
| Retail Store | $631,399.37 | 25.75% |
| Marketplace | $310,402.93 | 12.66% |

### Findings

The **Online channel** generated the highest revenue, contributing approximately **32.28%** of total revenue.

**Corporate Sales** was the second-highest-performing channel with approximately **29.31%**.

The **Marketplace** channel performed considerably lower, generating only **12.66%** of total revenue.

### Interpretation

Online and Corporate Sales are the company's strongest sales channels.

Together, these two channels generated approximately:

**$1.51 million**

This represents approximately **61.6% of total revenue**.

The company should therefore continue investing in online sales infrastructure and corporate-client relationships.

# 4.5 Customer Type Analysis

Customers were divided into two categories:

| Customer Type | Revenue | Revenue Share | Orders |
|---|---:|---:|---:|
| Returning | $1,683,325.30 | 68.65% | 1,311 |
| New | $768,759.00 | 31.35% | 689 |

### Findings

Returning customers generated approximately **68.65% of total revenue**.

New customers generated approximately **31.35%**.

Returning customers therefore generated more than twice the revenue generated by new customers.

### Interpretation

Customer retention is a major contributor to the company's revenue.

This suggests that existing customers have strong purchasing value and that customer loyalty should remain a major business priority.

The company should continue developing:

- Loyalty programs
- Repeat-purchase campaigns
- Customer relationship management
- Personalized offers
- Email marketing
- Customer retention strategies

At the same time, new-customer acquisition should not be neglected because new customers represent an important source of future returning customers.


# 4.6 Product Category Analysis

Revenue performance by product category was as follows:

| Product Category | Revenue | Revenue Share |
|---|---:|---:|
| Computers | $1,346,491.26 | 54.91% |
| Monitors | $526,744.59 | 21.48% |
| Networking | $259,475.31 | 10.58% |
| Storage | $229,837.63 | 9.37% |
| Accessories | $72,895.26 | 2.97% |
| Office Supplies | $16,640.26 | 0.68% |

### Findings

The **Computers** category was the dominant revenue generator, accounting for approximately **54.91%** of total revenue.

Monitors were the second-largest category at **21.48%**.

Computers and Monitors together generated approximately:

**$1.87 million**

This represents approximately **76.39% of total revenue**.

### Interpretation

The business is heavily dependent on technology products, particularly computers.

This represents both an opportunity and a risk.

The opportunity is that high-value computer products drive substantial revenue.

The risk is that poor performance in the computer category could significantly affect overall company revenue.




# 5. Key Insights

Based on the analysis, several important business insights were identified.

## Insight 1: Returning Customers Are Extremely Valuable

Returning customers generated approximately **68.65% of total revenue**.

This demonstrates that customer retention is one of the company's strongest revenue drivers.

**Business implication:** Retaining existing customers should be treated as a major strategic priority.

---

## Insight 2: Computers Dominate Revenue

The Computer category generated approximately **54.91% of total revenue**.

This means more than half of the company's revenue comes from one product category.

**Business implication:** Computer products should receive strong inventory, marketing, and sales support.

---

## Insight 3: Online Sales Are the Strongest Channel

Online sales generated approximately **$791,536.99**, making it the largest sales channel.

**Business implication:** Improving the company's online shopping experience could provide significant opportunities for growth.

---

## Insight 4: Revenue Is Concentrated in a Few Products

The top five products generated approximately **57.7% of total revenue**.

**Business implication:** These products should receive careful inventory management and strategic marketing.

---

## Insight 5: North and Central Are Strong Markets

North and Central generated the highest regional revenues.

**Business implication:** Successful strategies used in these regions could potentially be adapted to lower-performing regions.

---

## Insight 6: Marketplace Sales Have Growth Potential

Marketplace sales contributed only **12.66%** of total revenue.

Compared with Online and Corporate Sales, this is relatively low.

**Business implication:** The marketplace channel may have opportunities for improvement through better product listings, pricing, promotions, customer reviews, and advertising.

---

## Insight 7: Sales Performance Varies by Month

November was the strongest month, while July was the weakest.

**Business implication:** The company should identify the factors responsible for seasonal fluctuations and create campaigns to improve sales during weaker months.


# 6. Recommendations

## 6.1 Strengthen Customer Retention

Since returning customers generate approximately **68.65% of revenue**, the company should invest heavily in customer retention.

Recommended strategies include:

- Introduce customer loyalty programs.
- Provide exclusive offers to returning customers.
- Use personalized marketing campaigns.
- Offer repeat-purchase discounts.
- Send product recommendations based on previous purchases.
- Develop a customer relationship management strategy.

## 6.2 Invest More in High-Performing Products

Computers generate more than half of total revenue.

The company should:

- Promote high-performing laptops and PCs.
- Create product bundles.
- Cross-sell accessories with computer purchases.
- Monitor stock levels closely.

For example, a laptop purchase could be bundled with:

- Laptop stand
- Wireless mouse
- Keyboard
- External storage

This could increase the average order value.



## 6.3 Develop Regional Sales Strategies

North and Central are the strongest regions, while West has the lowest revenue.

Management should investigate the reasons behind the regional differences.

For weaker regions, the company could consider:

- Localized marketing
- Regional promotions
- Improved distribution
- Local partnerships
- Additional sales representatives
- Region-specific product offers

## 6.4 Prepare for Seasonal Demand

November recorded the highest monthly revenue, while July recorded the lowest.

The company should use historical sales patterns to plan:

- Inventory
- Staffing
- Marketing campaigns
- Promotions
- Product launches

Additional promotional activities could be introduced during historically weak months.


# 7. Conclusion

The analysis of the 2026 sales dataset shows that the company generated approximately **$2.45 million in revenue from 2,000 transactions**.

The strongest contributors to revenue were **returning customers, computer products, online sales, and high-value technology products**.

Returning customers generated approximately **68.65% of revenue**, demonstrating the importance of customer retention.

The Computer category contributed approximately **54.91% of total revenue**, making it the most important product category.

The Online channel was the highest-performing sales channel, contributing approximately **32.28% of revenue**, while Marketplace sales represented only **12.66%**.

Regionally, **North and Central** were the strongest markets, while **West** recorded the lowest revenue.

At the product level, the **Gaming Laptop** was the highest-revenue product, generating approximately **$432,576.06**.

The analysis also identified significant monthly fluctuations, with **November** being the strongest month and **July** being the weakest.

Overall, the company has a strong sales foundation but could improve performance by focusing on **customer retention, high-performing products, online sales, marketplace optimization, regional growth, targeted discounts, and seasonal planning**.

Future analysis could go further by examining **profit margins, customer lifetime value, conversion rates, inventory levels, sales targets, and the relationship between discounts and sales volume**. These additional metrics would provide a more complete picture of business profitability and operational performance.


# Sales Data Analysis Report

## 1. Introduction

This report presents an analysis of the sales data contained in the **Excel Sales Report** dataset. The objective of the analysis is to understand the company's sales performance, identify the major revenue drivers, evaluate customer and sales-channel performance, and provide actionable recommendations for improving future sales.

The dataset contains **2,000 sales transactions** recorded throughout **2026**. The analysis focuses on revenue, quantity sold, product categories, regions, sales channels, customer types, discounts, products, and salesperson performance.

The analysis is intended to answer important business questions such as:

- What is the overall sales performance?
- Which regions generate the highest revenue?
- Which sales channels perform best?
- Which product categories contribute most to revenue?
- How important are returning customers?
- Which products generate the most revenue?
- Which salespeople have the strongest performance?
- How do discounts relate to average order revenue?
- What strategies can be used to improve sales performance?

---

# 2. Data Description

The dataset consists of **2,000 unique sales transactions** with **12 variables**.

### Dataset Summary

| Metric | Value |
|---|---:|
| Total Transactions | 2,000 |
| Total Revenue | $2,452,084.30 |
| Total Quantity Sold | 5,552 |
| Average Revenue per Transaction | $1,226.04 |
| Average Quantity per Transaction | 2.78 |
| Number of Regions | 5 |
| Number of Sales Channels | 4 |
| Number of Customer Types | 2 |
| Number of Product Categories | 6 |
| Number of Products | 28 |
| Number of Salespeople | 15 |
| Data Period | January - December 2026 |

### Variables

| Variable | Description |
|---|---|
| `Order ID` | Unique identifier for each transaction |
| `Date` | Date on which the transaction occurred |
| `Region` | Geographical region where the sale occurred |
| `Sales Channel` | Channel through which the product was sold |
| `Customer Type` | Indicates whether the customer is new or returning |
| `Product Category` | Category to which the product belongs |
| `Product` | Specific product sold |
| `Salesperson` | Employee responsible for the sale |
| `Quantity` | Number of units purchased |
| `Unit Price` | Price per unit before discount |
| `Discount` | Discount percentage applied to the transaction |
| `Revenue` | Revenue generated from the transaction |

### Data Quality

The dataset was checked for missing values and duplicate records.

- There are **no missing values**.
- There are **no duplicate rows**.
- All **2,000 Order IDs are unique**.
- The dataset contains records covering the full year from **January 1, 2026 to December 31, 2026**.
- Numerical fields such as quantity, unit price, discount, and revenue contain valid values.

Therefore, the dataset was considered sufficiently clean for analysis.

---

# 3. Methodology

The analysis followed a structured data-analysis process.

### Step 1: Data Inspection

The Excel workbook was examined to understand:

- Number of records
- Number of variables
- Data types
- Missing values
- Duplicate records
- Date range
- Categorical variables
- Numerical variables

### Step 2: Data Cleaning

The following checks were performed:

- Checked for missing values
- Checked for duplicate transactions
- Verified unique Order IDs
- Confirmed date formats
- Reviewed numerical fields
- Checked categorical variables for consistency

No major data-cleaning issues were identified.

### Step 3: Descriptive Analysis

Descriptive statistics were calculated for:

- Total revenue
- Total quantity sold
- Average revenue per transaction
- Average quantity per transaction
- Discount levels

### Step 4: Group Analysis

Revenue and transaction performance were analyzed by:

- Region
- Sales channel
- Customer type
- Product category
- Product
- Salesperson
- Month

### Step 5: Comparative Analysis

Different business segments were compared to determine:

- Highest and lowest performing regions
- Most profitable sales channels
- Most valuable customer segment
- Highest-performing product categories
- Top-performing products
- Top-performing salespeople
- Monthly revenue trends

### Step 6: Business Insights

The results were interpreted to identify opportunities for:

- Revenue growth
- Customer retention
- Product prioritization
- Sales-channel optimization
- Regional improvement
- Discount management

---

# 4. Analysis & Findings

## 4.1 Overall Sales Performance

The business generated approximately **$2.45 million in revenue** from **2,000 transactions** during 2026.

The dataset recorded a total of **5,552 units sold**, giving an average of approximately **2.78 units per transaction**.

The average revenue generated per transaction was approximately **$1,226.04**.

### Key Findings

- Total Revenue: **$2,452,084.30**
- Total Orders: **2,000**
- Total Units Sold: **5,552**
- Average Order Revenue: **$1,226.04**
- Average Units per Order: **2.78**

The relatively high average revenue per transaction suggests that the business generates substantial value from individual orders, particularly through higher-priced technology products.

---

# 4.2 Monthly Revenue Analysis

Revenue varied considerably throughout the year.

| Month | Revenue |
|---|---:|
| January | $168,680.63 |
| February | $173,605.25 |
| March | $236,738.70 |
| April | $241,034.34 |
| May | $153,642.43 |
| June | $258,658.95 |
| July | $150,713.14 |
| August | $185,321.62 |
| September | $233,080.36 |
| October | $189,721.57 |
| November | $274,368.31 |
| December | $186,519.01 |

### Findings

**November** generated the highest monthly revenue at approximately **$274,368.31**.

The second-highest month was **June**, with approximately **$258,658.95**.

**July** recorded the lowest revenue at approximately **$150,713.14**, followed closely by May.

The results show significant monthly fluctuations rather than consistent revenue throughout the year.

### Interpretation

The strong performance in November may indicate increased customer demand during promotional or end-of-year shopping periods.

The weaker performance in May and July suggests that the company may need targeted promotions or campaigns during slower periods.

---

# 4.3 Regional Sales Performance

The company operates across five regions:

| Region | Revenue | Revenue Share |
|---|---:|---:|
| North | $561,753.72 | 22.91% |
| Central | $556,705.18 | 22.70% |
| East | $467,808.85 | 19.08% |
| South | $444,494.30 | 18.13% |
| West | $421,322.25 | 17.18% |

### Findings

The **North** region generated the highest revenue, closely followed by the **Central** region.

The **West** region generated the lowest revenue.

### Key Observation

The difference between the highest and lowest regions is approximately:

**$561,753.72 - $421,322.25 = $140,431.47**

This indicates a meaningful performance gap between regions.

### Interpretation

North and Central appear to be the strongest regional markets and could provide useful insights into successful sales strategies.

The West region may require further investigation to determine whether its lower performance is caused by:

- Lower customer demand
- Fewer transactions
- Product availability
- Salesperson performance
- Distribution challenges
- Lower marketing activity

---

# 4.4 Sales Channel Analysis

Revenue was distributed across four sales channels.

| Sales Channel | Revenue | Revenue Share |
|---|---:|---:|
| Online | $791,536.99 | 32.28% |
| Corporate Sales | $718,745.00 | 29.31% |
| Retail Store | $631,399.37 | 25.75% |
| Marketplace | $310,402.93 | 12.66% |

### Findings

The **Online channel** generated the highest revenue, contributing approximately **32.28%** of total revenue.

**Corporate Sales** was the second-highest-performing channel with approximately **29.31%**.

The **Marketplace** channel performed considerably lower, generating only **12.66%** of total revenue.

### Interpretation

Online and Corporate Sales are the company's strongest sales channels.

Together, these two channels generated approximately:

**$1.51 million**

This represents approximately **61.6% of total revenue**.

The company should therefore continue investing in online sales infrastructure and corporate-client relationships.

---

# 4.5 Customer Type Analysis

Customers were divided into two categories:

| Customer Type | Revenue | Revenue Share | Orders |
|---|---:|---:|---:|
| Returning | $1,683,325.30 | 68.65% | 1,311 |
| New | $768,759.00 | 31.35% | 689 |

### Findings

Returning customers generated approximately **68.65% of total revenue**.

New customers generated approximately **31.35%**.

Returning customers therefore generated more than twice the revenue generated by new customers.

### Interpretation

Customer retention is a major contributor to the company's revenue.

This suggests that existing customers have strong purchasing value and that customer loyalty should remain a major business priority.

The company should continue developing:

- Loyalty programs
- Repeat-purchase campaigns
- Customer relationship management
- Personalized offers
- Email marketing
- Customer retention strategies

At the same time, new-customer acquisition should not be neglected because new customers represent an important source of future returning customers.

---

# 4.6 Product Category Analysis

Revenue performance by product category was as follows:

| Product Category | Revenue | Revenue Share |
|---|---:|---:|
| Computers | $1,346,491.26 | 54.91% |
| Monitors | $526,744.59 | 21.48% |
| Networking | $259,475.31 | 10.58% |
| Storage | $229,837.63 | 9.37% |
| Accessories | $72,895.26 | 2.97% |
| Office Supplies | $16,640.26 | 0.68% |

### Findings

The **Computers** category was the dominant revenue generator, accounting for approximately **54.91%** of total revenue.

Monitors were the second-largest category at **21.48%**.

Computers and Monitors together generated approximately:

**$1.87 million**

This represents approximately **76.39% of total revenue**.

### Interpretation

The business is heavily dependent on technology products, particularly computers.

This represents both an opportunity and a risk.

The opportunity is that high-value computer products drive substantial revenue.

The risk is that poor performance in the computer category could significantly affect overall company revenue.

---

# 4.7 Product Performance

The five highest-revenue products were:

| Rank | Product | Revenue |
|---:|---|---:|
| 1 | Gaming Laptop | $432,576.06 |
| 2 | Laptop Air 13 | $273,532.50 |
| 3 | Laptop Pro 14 | $263,486.40 |
| 4 | All-in-One PC | $254,994.00 |
| 5 | Ultrawide Monitor | $190,959.45 |

### Findings

The **Gaming Laptop** was the strongest individual product, generating approximately **$432,576.06**.

The top five products generated approximately:

**$1.42 million**

This represents approximately **57.7% of total company revenue**.

### Interpretation

Revenue is concentrated among a relatively small number of high-performing products.

The company should ensure that these products receive:

- Adequate inventory
- Strong marketing support
- Competitive pricing
- Prominent placement on online platforms
- Promotional campaigns
- Cross-selling opportunities

---

# 4.8 Salesperson Performance

The top-performing salespeople based on revenue were:

| Rank | Salesperson | Revenue |
|---:|---|---:|
| 1 | Mei Tan | $224,065.80 |
| 2 | Hafiz Rahman | $203,962.00 |
| 3 | Amir Hassan | $194,689.22 |
| 4 | Raj Kumar | $189,044.54 |
| 5 | Chloe Lim | $182,494.65 |

### Findings

**Mei Tan** generated the highest revenue among the 15 salespeople.

The top five salespeople collectively generated approximately **$994,256**.

The lowest-performing salesperson by revenue was **Ben Ho**, with approximately **$117,570.14**.

### Interpretation

There is a noticeable performance difference between salespeople.

Management could study the methods used by top-performing salespeople and use their successful approaches to improve overall team performance.

Possible areas to investigate include:

- Number of customers handled
- Average order value
- Product knowledge
- Conversion rate
- Customer retention
- Discount usage
- Sales channel assignment

---

# 4.9 Discount Analysis

The average discount across transactions was approximately **7.38%**.

Revenue performance by discount range showed:

| Discount Range | Revenue | Average Revenue per Order |
|---|---:|---:|
| 0–4.9% | $718,750.19 | $1,281.19 |
| 5–9.9% | $977,145.10 | $1,252.75 |
| 10–14.9% | $368,100.10 | $1,168.57 |
| 15–20% | $388,088.91 | $1,128.17 |

### Findings

Transactions receiving lower discounts generally had higher average revenue.

The average revenue per order decreased as discount levels increased:

- 0–4.9% discount → **$1,281.19**
- 5–9.9% discount → **$1,252.75**
- 10–14.9% discount → **$1,168.57**
- 15–20% discount → **$1,128.17**

### Interpretation

Higher discounts may be associated with lower average transaction revenue.

However, this analysis shows **association rather than causation**. A higher discount does not necessarily cause lower revenue because discounts may be offered on different products, customer segments, or transaction types.

The company should therefore monitor discount effectiveness carefully.

---

# 5. Key Insights

Based on the analysis, several important business insights were identified.

## Insight 1: Returning Customers Are Extremely Valuable

Returning customers generated approximately **68.65% of total revenue**.

This demonstrates that customer retention is one of the company's strongest revenue drivers.

**Business implication:** Retaining existing customers should be treated as a major strategic priority.

---

## Insight 2: Computers Dominate Revenue

The Computer category generated approximately **54.91% of total revenue**.

This means more than half of the company's revenue comes from one product category.

**Business implication:** Computer products should receive strong inventory, marketing, and sales support.

---

## Insight 3: Online Sales Are the Strongest Channel

Online sales generated approximately **$791,536.99**, making it the largest sales channel.

**Business implication:** Improving the company's online shopping experience could provide significant opportunities for growth.

---

## Insight 4: Revenue Is Concentrated in a Few Products

The top five products generated approximately **57.7% of total revenue**.

**Business implication:** These products should receive careful inventory management and strategic marketing.

---

## Insight 5: North and Central Are Strong Markets

North and Central generated the highest regional revenues.

**Business implication:** Successful strategies used in these regions could potentially be adapted to lower-performing regions.

---

## Insight 6: Marketplace Sales Have Growth Potential

Marketplace sales contributed only **12.66%** of total revenue.

Compared with Online and Corporate Sales, this is relatively low.

**Business implication:** The marketplace channel may have opportunities for improvement through better product listings, pricing, promotions, customer reviews, and advertising.

---

## Insight 7: Sales Performance Varies by Month

November was the strongest month, while July was the weakest.

**Business implication:** The company should identify the factors responsible for seasonal fluctuations and create campaigns to improve sales during weaker months.

---

# 6. Recommendations

## 6.1 Strengthen Customer Retention

Since returning customers generate approximately **68.65% of revenue**, the company should invest heavily in customer retention.

Recommended strategies include:

- Introduce customer loyalty programs.
- Provide exclusive offers to returning customers.
- Use personalized marketing campaigns.
- Offer repeat-purchase discounts.
- Send product recommendations based on previous purchases.
- Develop a customer relationship management strategy.

---

## 6.2 Invest More in High-Performing Products

Computers generate more than half of total revenue.

The company should:

- Maintain sufficient inventory of high-performing computer products.
- Promote high-performing laptops and PCs.
- Create product bundles.
- Cross-sell accessories with computer purchases.
- Monitor stock levels closely.

For example, a laptop purchase could be bundled with:

- Laptop stand
- Wireless mouse
- Keyboard
- USB-C hub
- External storage

This could increase the average order value.

---

## 6.3 Improve the Online Sales Channel

Online sales are currently the strongest channel.

The company should consider:

- Improving website usability.
- Simplifying checkout.
- Improving product search.
- Providing detailed product descriptions.
- Using customer reviews.
- Offering personalized recommendations.
- Improving mobile shopping.
- Running targeted digital advertising campaigns.

---

## 6.4 Improve Marketplace Performance

Marketplace revenue is significantly lower than Online, Corporate Sales, and Retail Store revenue.

The company should investigate:

- Product listing quality
- Product pricing
- Customer reviews
- Marketplace visibility
- Advertising
- Delivery times
- Product availability
- Promotional campaigns

Improving marketplace performance could create an additional source of revenue.

---

## 6.5 Develop Regional Sales Strategies

North and Central are the strongest regions, while West has the lowest revenue.

Management should investigate the reasons behind the regional differences.

For weaker regions, the company could consider:

- Localized marketing
- Regional promotions
- Improved distribution
- Local partnerships
- Additional sales representatives
- Region-specific product offers

---

## 6.6 Optimize Discounts

The analysis suggests that higher discounts are associated with lower average revenue per transaction.

The company should avoid unnecessary discounting.

Instead, discounts should be targeted toward:

- New customer acquisition
- Slow-moving products
- Seasonal campaigns
- Customer retention
- High-volume purchases

Management should also track whether discounts actually increase sales volume enough to justify the reduction in revenue per transaction.

---

## 6.7 Learn From High-Performing Salespeople

The company should analyze the techniques used by top-performing salespeople such as:

- Mei Tan
- Hafiz Rahman
- Amir Hassan
- Raj Kumar
- Chloe Lim

Their sales approaches could be converted into training materials for the wider sales team.

---

## 6.8 Prepare for Seasonal Demand

November recorded the highest monthly revenue, while July recorded the lowest.

The company should use historical sales patterns to plan:

- Inventory
- Staffing
- Marketing campaigns
- Promotions
- Product launches

Additional promotional activities could be introduced during historically weak months.

---

# 7. Conclusion

The analysis of the 2026 sales dataset shows that the company generated approximately **$2.45 million in revenue from 2,000 transactions**.

The strongest contributors to revenue were **returning customers, computer products, online sales, and high-value technology products**.

Returning customers generated approximately **68.65% of revenue**, demonstrating the importance of customer retention.

The Computer category contributed approximately **54.91% of total revenue**, making it the most important product category.

The Online channel was the highest-performing sales channel, contributing approximately **32.28% of revenue**, while Marketplace sales represented only **12.66%**.

Regionally, **North and Central** were the strongest markets, while **West** recorded the lowest revenue.

At the product level, the **Gaming Laptop** was the highest-revenue product, generating approximately **$432,576.06**.

The analysis also identified significant monthly fluctuations, with **November** being the strongest month and **July** being the weakest.

Overall, the company has a strong sales foundation but could improve performance by focusing on **customer retention, high-performing products, online sales, marketplace optimization, regional growth, targeted discounts, and seasonal planning**.

Future analysis could go further by examining **profit margins, customer lifetime value, conversion rates, inventory levels, sales targets, and the relationship between discounts and sales volume**. These additional metrics would provide a more complete picture of business profitability and operational performance.

---

# 8. Executive Summary

| Key Metric | Result |
|---|---:|
| Total Revenue | **$2,452,084.30** |
| Total Orders | **2,000** |
| Total Units Sold | **5,552** |
| Average Order Revenue | **$1,226.04** |
| Top Region | **North** |
| Top Sales Channel | **Online** |
| Top Customer Type | **Returning Customers** |
| Top Product Category | **Computers** |
| Top Product | **Gaming Laptop** |
| Top Salesperson | **Mei Tan** |
| Best Month | **November** |
| Lowest Month | **July** |
| Average Discount | **7.38%** |
