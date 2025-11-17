# Supply Chain & Sales Analytics Dashboard

## 1. Context 

### 1.1. Introduction 

This **Supply Chain & Sales Analytics** dataset reflects an entire lifecycle of an order in multi-category retail and e-commerce operations – from customer order placement to delivery or return. The dataset includes **_9,994_** order transactions, including detailed information on products, customers, operations, salespeople, and locations.

### 1.2. Dataset Structure

- **Fact Table**: `fact_Retail Order` (9,994 order transactions).

- **Dimension Tables**: 9 supporting tables (`Calendar`, `Category`, `SubCategory`, `Customer`, `Customer Segment`, `Location`, `Product`, `Retail Sales People`, `Ship Mode`).
- **Time**: multiple years, with **1,237 days** in Calendar Dimension.
- **Geography**: 631 locations in many countries and regions.
- **Products**: 1,862 products, divided into **3 product lines** (Furniture, Office Supplies, Technology) and **17 subcategories**.
- **Customers**: 793 customers, divided into **3 segments** (Corporate, Consumer, Home Office).
- **Shipping methods**: 4 modes (Standard Class, Second Class, First Class, Same Day).
- **Sales team**: 4 salespersons in charge of regions/customers.

### 1.3. Challenges & Business Implications

- **46% of orders are late** → logistics optimization in demand.

- **8% of orders are returned** → impacting costs and customer experience.
- **Profit management** → need to balance competitive pricing and margins.
- **Different customer segments** → expectations of service and delivery speed are also different.

This dataset also answers **_important questions_**:

- How to improve delivery performance and reduce delays?

- Which products/categories are most profitable?
- How does customer behavior differ between Corporate, Consumer and Home Office?
- Which geographies have potential for expansion?
- Which sales people bring the most value?



