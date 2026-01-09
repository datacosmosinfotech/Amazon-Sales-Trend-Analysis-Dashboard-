# 📊 Amazon Sales Trend Analysis Dashboard
## 📌 Overview
This Power BI dashboard provides a descriptive analysis of Amazon product demand trends using product-level data. The dashboard focuses on understanding purchase contribution, category-level performance, and key attributes influencing demand through interactive visuals and a decomposition tree.
The analysis is exploratory and avoids causal assumptions.

## Dashboard Preview:
![Dashboard Screenshot](https://raw.githubusercontent.com/datacosmosinfotech/Amazon-Sales-Trend-Analysis-Dashboard-/main/Dashboard.png)

## 📁 Dataset Links
### Raw Dataset
👉 https://drive.google.com/file/d/1TEeOzgKxEf6Ul4J0GS9UNjf2O09IU3gv/view?usp=drive_link
### Cleaned Dataset
👉 https://docs.google.com/spreadsheets/d/1jtBl7j8On_ciOydGonOUSbsjVEIGSiO_/edit?usp=drive_link&ouid=102958371086507088368&rtpof=true&sd=tr
### 🎥 Demo Video
👉 https://drive.google.com/file/d/1n7pcrHkBTk7kXmu6inW-6Coz0Iwyda2G/view?usp=drive_link

## 🎯 Objectives
Analyze overall product demand using purchase metrics

Understand drivers of purchases across product attributes

Compare demand patterns by category, rating, sponsorship, and badges

Enable interactive exploration through slicers and drill down visuals

## 📂 Dataset Description
Each row in the dataset represents a single product and includes:

Product title

Product category

Rating

Review Count

Best seller tag

Buy Box availability

Sponsored tag

Sustainability tags

Purchased last month

Original Price

Discounted Price

Discount Percentage

Coupon

Note: purchased last month represents demand per product.

## 📈 Key KPIs
Total Products

Average Rating

Total Purchases (Last Month)

## 📊 Dashboard Visuals

### 1️⃣ Decomposition Tree – Drivers of Purchases (Last Month)

Analyze: Sum of purchased last month

Explain by:

Product Category

Buy Box Availability

Best Seller Tag

Sponsored Tag

Rating

Used to identify major contributors to total demand.

### 2️⃣ Purchases by Product Category

Visualizes how demand is distributed across categories

Highlights high demand categories

### 3️⃣ Price Comparison

Compares sum of original price vs discounted price by product category

Helps understand pricing distribution

### 4️⃣ Sponsorship Analysis

Shows average purchases by sponsored vs organic products

Used to compare demand performance at a per product level

### 5️⃣ Buy Box Availability Analysis
Displays total purchases grouped by Buy Box availability

Highlights the importance of Buy Box presence

### 6️⃣ Sustainability Tags Analysis

Analyzes average purchases by sustainability tags

Provides insight into demand patterns for eco related product labels

### 7️⃣ Rating Based Demand Distribution

Shows how purchases are distributed across rating bands

Helps assess whether higher ratings align with more demand

# 🎛️ Interactivity
Product Category slicer for focused analysis

Visual level interactions applied to control slicer impact

Decomposition tree reflects dominant contributors within the selected filter context

## ▶️ How to Run This Project
Install Power BI Desktop
https://powerbi.microsoft.com/desktop/

Download the cleaned dataset
👉https://docs.google.com/spreadsheets/d/1jtBl7j8On_ciOydGonOUSbsjVEIGSiO_/edit?usp=drive_link&ouid=102958371086507088368&rtpof=true&sd=tr

Open the .pbix file in Power BI Desktop

If prompted:

Go to Transform Data

Update the dataset path

Click Close & Apply

Use slicers and visuals to explore the dashboard

## 🛠️ Tools Used

Power BI Desktop

DAX for calculated measures

Data preprocessing using Python

## 🔍 Key Insights

✔Demand is concentrated in a few categories.

✔Buy Box availability strongly impacts demand.

✔Non badge products drive substantial purchases.

✔Best Seller status is not a demand guarantee.

✔Organic products dominate total purchases.

✔Sponsored products have limited overall impact.

✔Higher ratings generally align with higher demand.

✔Ratings alone do not explain demand.

✔Sustainability impact varies by segment.

## 💼 Business Recommendations

➡️Focus more on products and categories that have higher purchases.

➡️Ensure products have Buy Box availability to improve demand.

➡️Do not depend only on Best Seller badges to judge product performance.

➡️Use sponsored listings carefully where organic demand is low.

➡️Consider ratings along with other factors like category and availability when analyzing demand.

## 👤 Author
Asma Sirkhot

Data Analyst | Datascientist

LinkedIn:https://www.linkedin.com/in/asma-sirkhot-85b841362?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app

📍Mumbai India
