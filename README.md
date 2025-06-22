# Excel-Project
A data analysis project to explore user behavior, subscription trends, and content engagement patterns for a fictional streaming service using Microsoft Excel.
 Project Overview
This project investigates key metrics such as revenue generation, user engagement, genre preferences, device usage, and regional behavior. The goal is to derive actionable insights that can support decision-making for improving user retention and business performance.

# 📄 Data Description
The dataset (streaming_service_data.csv) includes 24 columns describing user attributes, engagement, preferences, and account settings. Key fields include:

Column Name	Description
User_ID	Unique user identifier
Join_Date	Date of subscription start
Last_Login	Last access date
Monthly_Price	Subscription fee
Watch_Hours	Total hours watched
Favorite_Genre	Most-watched genre
Active_Devices	Devices linked to account
Profile_Count	Number of user profiles
Total_Movies_Watched	Movies viewed
Total_Series_Watched	Series viewed
Country	User’s location
Payment_Method	e.g., Credit Card, PayPal
Has_Downloaded_Content	Whether downloads were made
Membership_Status	Active / Cancelled
Loyalty_Points	Points earned
Age_Group	User age category
Primary_Watch_Time	Preferred time of day (e.g., Evening)
# 🧹 Data Cleaning
Removed rows with missing or inconsistent subscription prices.
Converted date fields to proper datetime format.
Standardized categorical values (e.g., payment methods, watch times).
Handled nulls in engagement metrics like Watch_Hours, Loyalty_Points.
#📈 Key Analyses
1. Subscription & Revenue
Revenue breakdown by subscription tier
User distribution by plan and geography
2. Engagement Metrics
Avg. watch hours per user
Movie vs. series engagement
Impact of recommended content
3. Demographics & Behavior
Genre preferences by age group
Device usage trends
Peak watch hours (Morning, Evening, Late Night)
4. Retention & Loyalty
Active vs. cancelled memberships
Loyalty point distribution
Download behavior by user group
5. Payment & Regional Patterns
Most-used payment methods by country
Language preferences vs. engagement
Country-wise subscription volume
#📊 Deliverables
✅ Streaming_Service_Data_Dashboard.xlsx: Interactive Excel dashboard with slicers and charts
✅ streaming_service_data.csv: Cleaned dataset
📌 Presentation summarizing findings and recommendations
🧠 Insights Summary
Users aged 25–34 and 35–44 are the most active; Drama and Action are top genres.
Most active users watch during Evening hours and prefer mobile devices.
Credit Cards are the most used payment method globally; PayPal popular in Europe.
Countries with multilingual content options show higher engagement.
#🛠 Tools Used
Microsoft Excel (Pivot Tables, Conditional Formatting, Slicers)
Charts & Graphs (Bar, Pie, Line, Heatmaps)
Data Validation and Cleaning
