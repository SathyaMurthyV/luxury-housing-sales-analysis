**Luxury Housing Sales Analysis – Bengaluru**

**Overview :**

The Bengaluru real estate market has experienced rapid growth in the luxury housing segment. Understanding pricing trends, buyer preferences, and builder performance is crucial for developers, investors, and real estate analysts.

This project analyzes a large housing dataset to uncover insights related to market trends, booking patterns, and property demand. The analysis follows a complete data analytics pipeline involving Python-based data cleaning, SQL-based data storage and querying, and dashboard visualization.

**Tech Used :**

Python
Pandas
NumPy
SQL
Tableau

**Dataset :**

The dataset contains more than 100,000 records related to luxury housing sales in Bengaluru.
Key columns include:
Project_ID
Micro_Market
Builder
Ticket_Price_Cr
Configuration
Possession_Status
Amenity_Score
Booking_Status
Purchase_Quarter
Sales_Channel
Buyer_Type

**Project Workflow :**

**1. Data Cleaning (Python)**

Loaded dataset using Python
Handled missing values
Standardized text fields
Removed inconsistent entries
Generated cleaned dataset for analysis

**2. Data Storage and Querying (SQL)**

Created SQL tables for storing processed data
Inserted cleaned dataset into database
Executed analytical queries to understand trends and patterns

**3. Data Visualization (Tableau)**

Connected visualization tool to the processed dataset
Created interactive dashboards showing:
Market trends
Builder performance
Booking conversion rates
Configuration demand
Micro-market insights

**Business Use Cases :**

**Market Intelligence**
Identify high-performing micro-markets and understand luxury housing demand patterns.

**Builder Performance Analysis**
Compare builders based on pricing strategies and booking volumes.

**Buyer Behaviour Insights**
Analyze buyer types and booking preferences.

**Market Expansion Strategy**
Identify areas with potential growth opportunities.

**Key Insights :**
Certain micro-markets in Bengaluru show significantly higher demand for luxury housing.
3BHK configurations dominate booking preferences.
Builders with higher amenity scores tend to achieve better booking rates.
Specific builders consistently outperform competitors in high-ticket property sales.

**Repository Structure :**

Luxury-Housing-Sales-Analysis
│
├── Housing_Mini_Project.ipynb
├── Luxury Housing.twbx
└── README.md
