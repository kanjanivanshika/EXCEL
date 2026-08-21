## Restaurant Data Set | SWIGGY |


## 🎯Project Objective

The main goal of this dashboard is to help restaurant owners and managers make smart, data-driven decisions to boost profits and improve the guest experience. By visualizing this data, the project aims to identify top-selling menu items, pinpoint peak dining hours for better staff scheduling, track revenue trends, and uncover areas where service can be improved. The Objective of this project is to build a centralized, interactive analytics dashboard that translates daily restaurant operational data into actionable business insights. This Dashboard Aims to: Maximize Profitability, Optimize Operations, Reduce Waste, Enhance Retention.


## 📊Dataset Description

This Dataset captures daily restaurant operations across sales, menu costs, staff levels and customer satisfaction. It combines transactional logs with operational metrics to help managers link staffing and costs directly to daily revenue and reviews.

### Key Columns & Data Fields.

| NO. | Column Name             | Description                                                      |
| --: | ------------------------| ---------------------------------------------------------------- |
|   1 | **Order_ID**            | Unique Identifier for each order.                                |
|   2 | **Date**                | Calendar Date for Transaction.                                   |
|   3 | **Time**                | Exact Hour of the Order (To find Peak Times)                     |
|   4 | **Item_ID**             | Link to the Menu Item Sold.                                      |
|   5 | **Quantity Sold**       | No. of Units Ordered.                                            |
|   6 | **Order_Type**          | Categorized as Dine-IN, Take Away, or Delivery.                  |
|   7 | **Payment Method**      | Categorized as Credit Card, Cash, UPI.                           |
|   8 | **Table Number**        | Table identifier (Null for Delivery/Take Away)                   |
|   9 | **Wait Time Minutes**   | Total Minutes from order placement to Food Delivery.             |
|  10 | **Item_ID**             | Unique Identifier for each Drink/Dish.                           |
|  11 | **Item Name**           | The name of the Menu Item.                                       |
|  12 | **Category**            | Categorized as Appetizer, Main Course, Dessert, Beverages.       |
|  13 | **Selling Price**       | Price Charged to Customer.                                       |
|  14 | **Ingredient Cost**     | The exact cost to produce the Dish.(COGS)                        |
|  15 | **Profit_Margin**       | Calculated Column. (Selling Price-Ingredient Cost)               |
|  16 | **Stock_Status**        | In Stock, Low Stock, Out of Stock.                               |
|  17 | **Feedback_ID**         | Unique Identifier for each review.                               |
|  18 | **Rating Score**        | Numerical rating from 1 to 5 Stars.                              |
|  19 | **Sentiment Tag**       | Categorized as Food Quality, Service Speed, Cleanliness or Value.|
|  20 | **Customer_Type**       | New vs Returning Customer (If tracked via loyalty program)       |
|  21 | **Shift_ID**            | Unique identifier for work shift.                                |
|  22 | **Date**                | Date of Shift.                                                   |
|  23 | **Shift_Type**          | Morning, Afternoon, Evening, Night.                              |
|  24 | **Employees on Duty**   | Count of front of house and kitchen staff working.               |
|  25 | **Total Labor Cost**    | Total wages paid for specific shift.                             |


## 🧮Calculated Columns

**Total Revenue** - Quantity Sold * Selling Price.                                               

**Total Cost**    - Quantity Sold * Ingredient Cost.

**Order Profit**  - Total Revenue - Total Cost.

**Profit Margin ($)** - Selling Price - Ingredient Cost.

**Profit Margin (%)** - Profit Margin ($) / Selling Price * 100.

**Labor Per Cost** - Total Labor Cost/ Sales Table * 100.

**Revenue per Employee** - Total Revenue for Shift/Employees on Duty.


## 📈Dashboard Features

## KPI Cards
**Total Revenue** - Total money generated from orders.
**Total Orders** - Number of orders.
**Total Quantity Sold** - Total units/ Items Sold
**Total Cost** - Total Ingredient cost.
**Total Profit** - Revenue - Cost.
**Profit Margin %** - Profit as % of selling price.
**Average Order Value** - Revenue / Orders.
**Average Rating** - Average customer rating.
