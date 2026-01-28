# bmw-sales-analysis-sql
# BMW Worldwide Sales Analysis (2010–2024)

## 📌 Project Overview
This project analyzes **BMW worldwide sales data from 2010 to 2024** to identify sales trends, top-performing models, regional performance, and customer preferences.  
The analysis integrates **Excel, Power Query, and SQL** to generate actionable insights that can support BMW’s strategic decisions in pricing, production, inventory planning, and marketing.

---

## 🧩 Business Problem
BMW operates in a highly competitive global automotive market where customer preferences, regional demand, and product performance change rapidly.  
However, BMW lacks a clear, data-driven understanding of:
- Regional sales performance
- Customer model preferences
- Impact of fuel type, transmission, and pricing on sales
- Key drivers of high and low sales performance  

Without these insights, optimizing sales strategy and long-term growth becomes challenging.

---

## 🎯 Solution Objectives
- Analyze global sales trends from **2010–2024**
- Identify top-performing models by region, price, and specifications
- Understand customer preferences across fuel type, transmission, and color
- Provide data-backed recommendations to improve BMW’s sales strategy

---

## 📂 Dataset Description
- **Source:** Kaggle – BMW Worldwide Sales Records  
- **Time Period:** 2010–2024  
- **File Type:** Excel (.xlsx)

### Key Columns
- Model  
- Year  
- Region  
- Color  
- Fuel Type (Petrol, Diesel, Hybrid, Electric)  
- Transmission (Manual / Automatic)  
- Engine Size  
- Mileage (km)  
- Price (USD)  
- Sales Volume  
- Sales Classification (High / Low)

---

## 🛠 Tools & Technologies Used
- Microsoft Excel  
- Power Query  
- SQL  
- Pivot Tables & Charts  
- Data Cleaning & Transformation  

---

## 🧹 Data Cleaning & Modeling
- Checked and removed duplicates and null values  
- Standardized column names  
- Corrected numerical inconsistencies  
- Normalized categorical values and handled outliers  

### Data Model
- **Fact Table:** `sales_fact`  
- **Dimension Tables:** models, regions, fuel_types, transmissions, colors  

A **one-to-many star schema** was used for efficient analysis.

---

## 📊 Analysis & Insights

### 🔹 Market Trend Analysis
**Electric vs Petrol vs Diesel Sales**
- Electric vehicle sales increase steadily year over year
- Petrol and diesel show stagnation or decline
- Strong EV growth observed after 2020, indicating a shift in customer preference

---

### 🔹 Pricing Analysis
**Price Range by Region**
- Premium regions consistently sell higher-priced models
- Some regions are more price-sensitive
- Wide price variation reflects differences in purchasing power

**Average Price per Year**
- Gradual price increase over time
- Price peaks (e.g., 2016) indicate premium launches or inflation
- Price dips (e.g., 2015) suggest entry-level or budget models

---

### 🔹 Sales Performance Analysis
**Total Sales Volume per Year**
- Sales peaks indicate strong demand cycles (e.g., 2022)
- Declines reflect economic or supply-chain challenges (e.g., 2020)

**Revenue by Model**
- A few premium models dominate yearly revenue
- Revenue leaders change slightly each year
- High revenue driven by strong demand and premium pricing

**Top Regions by Sales Volume**
- Certain regions consistently contribute the highest volume
- Low-performing regions indicate growth opportunities

**Top 5 Models by Sales Volume**
- Repeated appearance of specific models
- Represents BMW’s core customer demand
- Competitive pricing supports high sales volume

---

### 🔹 Customer Preference Analysis
**Color Preference**
- Popular colors include white, silver, and red
- Customer preferences remain stable over time
- Special edition colors contribute minimal volume

**Transmission Preference**
- Manual transmission is preferred over automatic
- Trends align with driving habits and convenience

**Sales Volume by Fuel Type**
- Hybrid vehicles lead total sales volume
- Diesel declines due to regulations and shifting preferences
- Electric vehicles grow steadily but remain below hybrids

---

## 📌 Recommendations
1. **Strengthen Electric Vehicle Strategy**
   - Increase EV production in high-adoption regions
   - Offer EV-specific incentives

2. **Region-Based Pricing Strategy**
   - Promote premium models in high-income regions
   - Introduce affordable variants in price-sensitive markets

3. **Focus on High-Revenue Models**
   - Prioritize marketing and inventory for top-performing models
   - Introduce upgrades to sustain demand

4. **Improve Presence in Weak Regions**
   - Localized marketing campaigns
   - Dealer partnerships and regional promotions

5. **Align Inventory with Customer Preferences**
   - Stock more manual transmission vehicles
   - Focus on popular colors
   - Maintain hybrid strength while transitioning toward EVs

---

## 📁 Project Files
- `mini project.xlsx` – Cleaned dataset, SQL output, pivot tables, and analysis  
- `bmw sales project report.pdf` – Detailed project documentation  

---

## 🚀 Conclusion
The analysis reveals evolving customer preferences across regions, fuel types, and models. BMW’s future growth depends on accelerating electric vehicle adoption, optimizing regional pricing strategies, and leveraging high-revenue models. Aligning data-driven insights with business strategy will strengthen BMW’s global competitiveness and support sustainable expansion.

---

## 👤 Author
**FASNA**  
Data Analytics Intern  
Skills: Excel | SQL | Power BI | Tableau | Statistics
