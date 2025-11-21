# 📊 Marketing Performance Dashboard (Power BI)

This project analyzes marketing campaign data to measure performance, ROI, customer segments, and channel effectiveness.  
It demonstrates my skills in **Power BI, Excel, Power Query, KPIs, data modeling, business insights, and data storytelling**.

---

## 🔍 **Project Objective**

Marketing teams often struggle to understand:
- Which channels bring the highest ROI  
- Which campaigns drive conversions  
- Which customer segments generate the most revenue  
- How performance changes over time  

This dashboard provides a clear, interactive way to answer these questions.

---

## 🛠️ **Tools Used**

- **Power BI** (main dashboard)
- **Excel** (data cleaning + source files)
- **Power Query** (transformations)
- **DAX** (KPIs & measures)
- *(Optional)* SQL for additional queries

---

## 📁 **Dataset**

The dataset includes:
- Campaigns  
- Channels (Social, Email, Search, Display, etc.)
- Spend  
- Impressions  
- Clicks  
- Conversions  
- Revenue  
- Customer segments  
- Dates  

> I will upload a cleaned Excel sample dataset (synthetic) for demonstration.

---

## ⚙️ **Process & Steps**

### **1. Data Preparation (Excel + Power Query)**
- Removed duplicates  
- Standardized date formats  
- Cleaned channel labels  
- Created calculated columns (CTR, CPC, CPA etc.)  

### **2. Power BI Modeling**
- Built a star schema  
- Created fact table for performance metrics  
- Built dimension tables: Campaign, Channel, Date, Customer Segment  

### **3. DAX Measures**
- Total Revenue  
- ROI  
- Conversion Rate  
- Cost per Acquisition (CPA)  
- Click-Through Rate (CTR)  
- Revenue by Segment  

### **4. Dashboard Pages**
#### 📌 *Page 1: Executive Summary*
- Total Revenue  
- Total Conversions  
- ROI  
- Top 5 Campaigns  
- Performance trends  

#### 📌 *Page 2: Channel Analysis*
- CPA by channel  
- Revenue by channel  
- Conversion rate comparison  

#### 📌 *Page 3: Customer Segmentation*
- Revenue by segment  
- Conversion rate by segment  
- Retention / repeat customers (if available)

---

## 📸 **Screenshots (Coming Soon)**

I will add exported PNG images from:
- Executive Summary  
- Channel Analysis  
- Segment Overview  

---

## 📦 Repository Structure

```text
marketing-performance-powerbi/
│
├── data/
│   └── marketing_data_sample.xlsx   (sample dataset)
│
├── reports/
│   ├── dashboard_screenshot_1.png
│   ├── dashboard_screenshot_2.png
│   └── dashboard_screenshot_3.png
│
├── pbix/
│   └── marketing_dashboard.pbix
│
└── README.md
