# Dynamic Pricing

Based on transaction data, participant prices, promotions and sales plans, write system that will offer a price

Date: day-month-year.

Important: there may be new buyers.

## DATA:

**transactions.csv — user transaction data (± 1.3 million rows):**
| dates            | SKU | user | price         |
| -----------------|:---:| ----:|--------------:|
| date of purchase | SKU | user | price for SKU |


**sample.csv — sample of 1000 SKUs**
| sku_id | fincode | ui1_code | ui2_code | ui3_code  | vendor | brand_code | creation_date | expiration_date |
| -------|:-------:| --------:|---------:|-----------|:------:| ----------:|--------------:|-----------------|


**promo_df.csv — promotion data:**
| SKU | week_num    | year | discount     |
| ----|:-----------:| ----:|-------------:|
| SKU | week number | year | SKU discount |


**canc_df.csv — competitor price data**
| SKU | year | week_num    | ret_net_1_price |ret_net_2_price  |ret_net_3_price  |
| ----|:----:| -----------:|----------------:|----------------:|----------------:|
| SKU | year | week number | retail №1 price | retail №2 price | retail №3 price |


**sales_plan.csv — sales plan data:**
| SKU | year | month |    plan        | back_bonus                    |
| ----|:----:|------:|---------------:|------------------------------:|
| SKU | year | month | plan for sales | bonus for completing the plan |

**wholesale_trade_table.csv — purchasing data:**
| SKU | year | week_num    |    cost_price  | 
| ----|:----:|------------:|---------------:|
| SKU | year | week number | cost price     | 



