# sql-zepto-analysis
## Project Overview
Quick-commerce platforms like **Zepto** operate in a high-velocity, low-margin environment where **pricing accuracy, discount strategy, and inventory availability** directly impact revenue and customer experience.

This project uses **SQL-driven analysis** on a grocery product dataset to identify:
- Pricing inconsistencies
- Discount strategy gaps
- Inventory and stock availability risks
- Category-level revenue opportunities

The insights are translated into **business-ready visuals** and a PowerPoint presentation for stakeholder communication.

---

## Business Objectives
- Clean and standardize raw product data for analysis
- Evaluate pricing and discount strategies across categories
- Identify high-value products that are out of stock
- Analyze revenue contribution by category
- Assess value-for-money using price-per-gram analysis
- Generate actionable business recommendations

---

## Dataset Description
- **Source:** Simulated Zepto grocery product dataset
- **Granularity:** SKU-level data
- **Key Fields:**
  - Product name & category
  - MRP and discount percentage
  - Discounted selling price
  - Available quantity & stock status
  - Product weight (grams)

---

## Tools & Technologies
- **SQL** – Data cleaning, transformation, and analysis  
- **PowerPoint** – Business storytelling & visualization  
- **Data Analytics Techniques**
  - Data cleaning & validation
  - Aggregations & filtering
  - Pricing and inventory analysis

---

## Data Cleaning (SQL)
Key cleaning steps performed using SQL:
- Removed invalid records (MRP = 0)
- Standardized pricing units (paise → rupees)
- Checked and handled missing values
- Validated stock availability fields
- Ensured consistency across categories and pricing columns

These steps ensured reliable downstream analysis.

---

## Key Business Questions Answered

### 1. Which categories contribute the most revenue?
Revenue calculated using:Used to identify high-impact categories.

### 2. Are discount strategies consistent across categories?
Analyzed average discount percentage by category to uncover inconsistencies.

### 3. Are high-MRP products out of stock?
Identified premium products unavailable for sale, highlighting potential revenue leakage.

### 4. Which products offer the best value to customers?
Computed **price per gram** to compare value across brands and pack sizes.

### 5. How does inventory weight vary by category?
Assessed total inventory weight to support warehouse and logistics planning.

---

## Key Insights
- Certain categories generate disproportionately higher revenue
- Discount strategies vary significantly across categories
- Multiple high-MRP products are marked out of stock, indicating lost revenue opportunities
- Medium and bulk pack sizes offer better price-per-gram value
- Inventory weight distribution can inform supply-chain optimization

---

## Business Recommendations
- Prioritize restocking of high-MRP, high-demand products
- Standardize discount strategies within categories
- Promote bulk products with better unit economics
- Optimize warehouse allocation using inventory weight insights

---

## Visual Deliverables
- 📊 Revenue by Category (Bar Chart)
- 📉 Average Discount % by Category
- 📋 High-MRP Out-of-Stock Products (Table)
- 📋 Best Value Products by Price per Gram (Table)

All visuals are compiled into a stakeholder-ready PowerPoint presentation.

---



