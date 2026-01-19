# ☕ Coffee Shop Sales Analysis Dashboard

![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-4285F4?style=for-the-badge&logo=google-analytics&logoColor=white)
![Dashboard](https://img.shields.io/badge/Dashboard-FF6B35?style=for-the-badge&logo=chartdotjs&logoColor=white)

## 📋 Project Overview

This project presents a comprehensive Coffee Shop Sales Analysis Dashboard built in Microsoft Excel to analyze sales performance, customer behavior, and product trends across multiple store locations. The interactive dashboard provides actionable insights for optimizing operations, inventory management, and revenue generation.

### 🎯 Business Objective

To analyze coffee shop sales data and identify key performance indicators (KPIs), peak business hours, top-performing products, and location-based trends to support data-driven decision-making for business growth and operational efficiency.

---

## 📊 Key Performance Indicators (KPIs)

### Overall Business Metrics
- **Total Sales Revenue:** $698,812.33
- **Total Footfall:** 149,116 customers
- **Average Bill per Person:** $4.69
- **Average Orders per Person:** 1.44 orders

**Insight:** Strong customer base with consistent order patterns, indicating good customer loyalty and repeat business.

---

## 🔍 Dashboard Components

### 1. Quantity Ordered Based on Hours ⏰
**Hourly Sales Pattern Analysis:**
- **Peak Hours:** 8 AM - 10 AM (25,000+ orders)
  - Morning rush drives maximum business
  - Highest order volume at 10 AM (~27,000 orders)
- **Secondary Peak:** 7 AM (8,000+ orders)
  - Early morning customers
- **Declining Trend:** After 10 AM, steady decrease throughout the day
- **Low Activity:** Post 3 PM (under 5,000 orders)

**Business Recommendations:**
- Staff more employees during 7-10 AM window
- Optimize inventory for morning products
- Consider promotional offers during low-activity hours (post 3 PM)
- Evaluate opening hours and potential for earlier start time

---

### 2. Categories % Distribution Based on Sales 🥐

**Product Category Performance:**

| Category | Sales % | Business Impact |
|----------|---------|-----------------|
| Coffee | 39% | Core product - highest revenue generator |
| Tea | 28% | Second largest category |
| Bakery | 12% | Complementary items |
| Drinking Chocolate | 10% | Seasonal/specialty item |
| Branded | 6% | Premium products |
| Coffee beans | 2% | Retail opportunity |
| Packaged Chocolate | 1% | Low performer |
| Loose Tea | 1% | Niche market |
| Flavours | 1% | Minimal contribution |

**Key Insights:**
- Coffee and Tea represent 67% of total sales
- Bakery items show good cross-selling potential (12%)
- Opportunity to increase coffee beans and packaged goods sales
- Consider expanding drinking chocolate offerings

**Strategic Actions:**
- Bundle coffee with bakery items for increased sales
- Develop marketing campaigns for underperforming categories
- Expand coffee and tea variety based on customer preferences

---

### 3. Size Distribution Based on Orders 📏

**Order Size Preferences:**

| Size | Order % | Customer Preference |
|------|---------|-------------------|
| Large | 30% | Premium segment |
| Regular | 31% | Most popular choice |
| Small | 9% | Economy option |
| Not Defined | 30% | Data quality issue |

**Insights:**
- Regular and Large sizes dominate (61% combined)
- Small size underperforming - possible pricing issue
- 30% "Not Defined" indicates data entry gaps

**Recommendations:**
- Improve data collection for accurate size tracking
- Investigate small size low adoption (pricing/marketing)
- Create size-based combo deals to upsell to Large
- Train staff on proper order recording

---

### 4. Footfall Over Various Store Locations 📍

**Location-Based Performance:**

| Store Location | Footfall | Performance |
|----------------|----------|-------------|
| Lower Manhattan | 230,057 (47,782 avg) | TOP PERFORMER |
| Hell's Kitchen | 236,511 (50,735 avg) | HIGHEST TRAFFIC |
| Astoria | 232,243 (50,699 avg) | CONSISTENT |

**Analysis:**
- Hell's Kitchen leads with highest average footfall (~50,735)
- All three locations show strong and balanced performance
- Lower Manhattan slightly lower but still robust
- Minimal variance suggests successful multi-location strategy

**Location Strategy:**
- Investigate Hell's Kitchen's success factors for replication
- Ensure consistent quality and service across all locations
- Consider expansion in similar demographic areas
- Benchmark operations between locations

---

### 5. Top 5 Products Based on Sales 🏆

**Best-Selling Products:**

| Rank | Product | Revenue | Performance |
|------|---------|---------|-------------|
| 1 | Barista Espresso | $91,406.20 | Leading revenue generator |
| 2 | Brewed Chai Tea | $77,081.95 | Strong tea segment |
| 3 | Hot Chocolate | $72,416.00 | Seasonal favorite |
| 4 | Gourmet Brewed Coffee | $70,034.60 | Premium coffee performer |
| 5 | Brewed Black Tea | $47,932.00 | Consistent seller |

**Total Top 5 Revenue:** $358,870.75 (51% of total sales)

**Product Insights:**
- Espresso-based drinks dominate revenue
- Diverse product mix in top 5 (coffee, tea, chocolate)
- Significant gap between #1 and #5 products
- Premium products (Gourmet, Barista) perform exceptionally well

**Product Strategy:**
- Feature top performers in marketing campaigns
- Create variants of Barista Espresso (flavored versions)
- Bundle slow-moving items with top sellers
- Seasonal promotions for Hot Chocolate year-round
- Develop loyalty programs around favorite products

---

### 6. Orders on Weekdays 📅

**Day-of-Week Performance:**

| Day | Footfall Range | Pattern |
|-----|----------------|---------|
| Monday | 21,643 | Week start - moderate |
| Tuesday | 21,202 | Slight dip |
| Wednesday | 21,310 | Mid-week recovery |
| Thursday | 21,854 | Rising trend |
| Friday | 21,701 | PEAK - weekend prep |
| Saturday | 21,036 | Weekend dip |
| Sunday | 20,510 | LOWEST - rest day |

**Weekly Insights:**
- Consistent weekday traffic (21,000-22,000 range)
- Weekend shows lower footfall (especially Sunday)
- Thursday-Friday show highest activity
- Minimal variance suggests stable customer base

**Operational Recommendations:**
- Weekend promotions to boost Saturday/Sunday traffic
- Adjust staffing levels for Sunday (lowest day)
- Target office workers during weekdays
- Create weekend family/group packages
- Leverage Thursday-Friday momentum with special offers

---

## 🛠️ Tools & Technologies

- **Microsoft Excel:** Primary tool for data analysis and dashboard creation
- **Data Processing:** Data cleaning, transformation, and preprocessing
- **Pivot Tables:** Dynamic data summarization and analysis
- **Charts & Visualizations:** Line charts, pie charts, bar charts, and KPI cards
- **Conditional Formatting:** Visual data highlighting
- **Excel Formulas:** SUMIF, AVERAGEIF, COUNTIF, VLOOKUP, and more

---

## 📈 Advanced Excel Features Utilized

### Formulas & Functions
```excel
# Total Sales
=SUM(Sales[Amount])

# Average Bill per Person
=AVERAGE(Sales[BillAmount])

# Category Distribution
=SalesAmount/TotalSales*100

# Peak Hour Identification
=MAX(HourlyOrders)

# Top Products Ranking
=LARGE(ProductSales,1)
```

### Data Analysis Techniques
- **Pivot Tables:** Multi-dimensional data analysis
- **Slicers:** Interactive filtering by Month and Day
- **Dynamic Charts:** Auto-updating visualizations
- **Conditional Formatting:** Highlighting key metrics
- **Data Validation:** Ensuring data quality

---

## 🎯 Key Business Insights & Recommendations

### 💰 Revenue Optimization
1. **Focus on Peak Hours (8-10 AM)**
   - Increase staffing during morning rush
   - Optimize quick-service items for speed
   - Pre-prepare popular morning items

2. **Product Mix Strategy**
   - Promote high-margin items (Barista Espresso, Gourmet Coffee)
   - Create coffee + bakery combo deals
   - Expand tea variety based on strong performance (28% of sales)

3. **Underperforming Categories**
   - Develop marketing for Packaged Chocolate and Flavours
   - Consider discontinuing non-performing items
   - Introduce seasonal variations

### 📍 Location Management
1. **Hell's Kitchen Success Replication**
   - Study customer demographics
   - Analyze service efficiency
   - Replicate best practices to other locations

2. **Balanced Multi-Location Strategy**
   - Maintain consistency in quality
   - Share inventory across locations
   - Cross-train staff between stores

### 👥 Customer Experience
1. **Weekend Engagement**
   - Launch weekend-specific promotions
   - Host events or tastings on Sundays
   - Create family-friendly packages

2. **Loyalty Programs**
   - Reward frequent morning customers
   - Points system for top 5 products
   - Size upgrade incentives

### 📊 Data Quality Improvement
1. **Fix "Not Defined" Issue in Size Distribution**
   - Implement mandatory size selection in POS
   - Train staff on data entry protocols
   - Regular data audits

---

## 📁 Project Structure

```
Coffee-Shop-Sales-Data-Analysis/
│
├── Data/
│   ├── Raw_Sales_Data.xlsx           # Original dataset
│   └── Cleaned_Data.xlsx             # Processed data
│
├── Dashboard/
│   └── Coffee_Shop_Dashboard.xlsx    # Main Excel dashboard
│
├── Analysis/
│   ├── Hourly_Analysis.xlsx          # Time-based insights
│   ├── Product_Performance.xlsx      # Product analysis
│   └── Location_Comparison.xlsx      # Store-wise metrics
│
├── Images/
│   └── dashboard_preview.png         # Dashboard screenshot
│
└── README.md                          # Project documentation
```

---

## 🚀 How to Use This Dashboard

### Prerequisites
- Microsoft Excel 2016 or later (Excel 365 recommended)
- Basic understanding of Excel navigation
- Enable macros if any automation is included

### Steps to Access
1. **Clone or Download Repository**
   ```bash
   git clone https://github.com/Pritpatel0712/Coffee-Shop-Sales-Data-Analysis.git
   ```

2. **Open the Dashboard**
   - Navigate to `Dashboard/Coffee_Shop_Dashboard.xlsx`
   - Open with Microsoft Excel

3. **Interactive Features**
   - **Month Filter:** Select specific months (January-June available)
   - **Day Filter:** Analyze specific days of the week
   - **Hover:** View detailed values on charts
   - **Click:** Charts are interactive and cross-filter

4. **Refresh Data**
   - Update raw data in the Data folder
   - Click "Refresh All" in the Data tab
   - Dashboard automatically updates

---

## 📊 Data Dictionary

| Field Name | Description | Data Type |
|------------|-------------|-----------|
| Transaction_ID | Unique identifier for each sale | Text |
| Date | Transaction date | Date |
| Month | Month of transaction | Text |
| Day | Day of week | Text |
| Hour | Hour of transaction (24-hour format) | Number |
| Store_Location | Coffee shop location | Text |
| Product_Category | Type of product sold | Text |
| Product_Type | Specific product name | Text |
| Size | Order size (Small/Regular/Large) | Text |
| Quantity | Number of items ordered | Number |
| Unit_Price | Price per unit | Currency |
| Total_Amount | Total transaction value | Currency |

---

## 📈 Dashboard Preview

![Coffee Shop Sales Dashboard](./Images/dashboard_preview.png)

*Interactive Excel dashboard showcasing comprehensive coffee shop sales analytics*

---

## 🔄 Future Enhancements

### Phase 1: Data Expansion
- [ ] Add customer demographic data
- [ ] Include seasonal weather data correlation
- [ ] Track inventory levels and waste

### Phase 2: Advanced Analytics
- [ ] Predictive sales forecasting using regression
- [ ] Customer segmentation analysis
- [ ] Product affinity analysis (basket analysis)
- [ ] Profit margin analysis by product

### Phase 3: Automation
- [ ] Automate data refresh from POS system
- [ ] Email reports to stakeholders
- [ ] Real-time dashboard updates

### Phase 4: Integration
- [ ] Migrate to Power BI for advanced visuals
- [ ] Connect to database for live data
- [ ] Mobile-responsive dashboard

---

## 💡 Key Learnings

Throughout this project, I developed expertise in:
- **Excel Dashboard Design:** Creating visually appealing and functional dashboards
- **Data Cleaning:** Handling missing values, duplicates, and data inconsistencies
- **Business Analytics:** Translating data into actionable business recommendations
- **Visualization Best Practices:** Choosing appropriate chart types for different data
- **Stakeholder Communication:** Presenting insights in a clear, non-technical manner
- **Time-Series Analysis:** Understanding patterns over time (hourly, daily, monthly)

---

## 🎓 Skills Demonstrated

### Technical Skills
- Advanced Excel formulas and functions
- Pivot table creation and manipulation
- Data visualization and chart design
- Dashboard design and UX principles
- Data preprocessing and cleaning

### Business Skills
- Retail analytics and KPI tracking
- Sales trend analysis
- Product performance evaluation
- Location-based business intelligence
- Strategic business recommendations

---

## 🤝 Contributing

Found an insight I missed or have suggestions for improvement? Contributions are welcome!

- Open an issue for discussion
- Submit pull requests for enhancements
- Share your own analysis findings
- Suggest additional visualizations

---

## 📧 Contact

**Prit Patel**  
Data Analyst | Rajkot, Gujarat, IN

[![LinkedIn](https://www.linkedin.com/in/-prit-patel-)
[![Email](pritardeshna07@gmail.com)
[![GitHub](https://github.com/Pritpatel0712)
[![Portfolio](https://www.datascienceportfol.io/pritpatel2031)

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙏 Acknowledgments

- Coffee shop data analysis best practices from retail analytics community
- Excel dashboard design inspiration from data visualization experts
- Thank you to all contributors and viewers!

---

<div align="center">

### ☕ "Good coffee, great data, better decisions!"

**If you found this analysis helpful, please consider giving it a ⭐!**

**Made with ☕ 📊 and 💻 by Prit Patel**

</div>
