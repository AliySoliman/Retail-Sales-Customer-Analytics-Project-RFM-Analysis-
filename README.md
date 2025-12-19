🛒 Retail Sales & Customer Analytics Project (RFM Analysis)

📌 Project Overview

  This project is a complete end-to-end retail analytics and customer segmentation analysis using transactional data.
  The goal is to extract business insights from raw retail data by performing:

Data cleaning & preprocessing

Exploratory Data Analysis (EDA)

Sales & product performance analysis

Customer behavior analysis

RFM (Recency, Frequency, Monetary) segmentation

Visualization of customer and product insights

The project focuses on understanding customers and products, not just building models.

🎯 Business Objectives

The main objectives of this project are:

Identify top and least selling products

Analyze returned/refunded products

Understand customer purchasing behavior

Segment customers using RFM analysis

Identify:

Best customers

Loyal customers

Potential customers

Customers needing attention

Provide insights that support:

Marketing decisions

Customer retention strategies

Product quality investigation

📂 Dataset Description

The dataset consists of retail transaction records with features such as:

Invoice: Unique transaction identifier

StockCode: Product code

Description: Product description

Quantity: Number of units

Price: Unit price

InvoiceDate: Date of transaction

Customer ID: Customer identifier

TransactionType: Custom-labeled transaction type (Sale, Refund, Cancelled, etc.)

Each row represents one transactional event.

🧹 Data Cleaning & Preprocessing

Key cleaning steps applied:

Removed duplicated records

Removed invalid or unknown product descriptions

Handled negative quantities and prices correctly

Created a TransactionType label to distinguish:

Sales

Refunds

Cancelled requests

Cancelled completed

Anomalies

Created a Revenue column with proper business logic

Ensured consistency before analysis

📊 Exploratory Data Analysis (EDA)

EDA focused on understanding:

Distribution of quantities and prices

Revenue patterns

Sales trends over time

Customer purchasing frequency

Product-level behavior

Visualizations included:

Histograms

Bar charts

Heatmaps

Distribution plots

📦 Sales & Product Analysis
Sales Analysis

Filtered only valid sales transactions

Grouped by StockCode and Description

Computed:

Total quantity sold

Total revenue

Identified:

Most sold products

Least sold products

Refund & Returns Analysis

Analyzed returned products separately from sales

Included:

Refunded

Cancelled requested

Cancelled completed

Refund-related anomalies

Focused on product quantities, not revenue

Identified products that are:

Frequently returned

Potentially problematic

Comparison

Compared sold vs returned products

Identified products with:

High sales AND high returns

This supports quality and customer satisfaction analysis

👥 Customer Analysis – RFM Framework

RFM Analysis was applied to understand customer behavior:

RFM Metrics

Recency (R): Days since last purchase

Frequency (F): Number of purchases

Monetary (M): Total revenue generated

RFM Scoring

Customers were scored using quantile-based scoring (1–5)

Combined into an RFM_Score (e.g., 555, 444, etc.)

Customer Segmentation

Customers were categorized into business-friendly segments:

Segment	Description
Champions / Best	High value, frequent, recent buyers
Loyal	Regular repeat customers
Potential	Customers with growth potential
Needs Attention	Low engagement customers
📈 Visualizations

The project includes rich visualizations such as:

RFM distributions (Recency, Frequency, Monetary)

Customer segment distributions

Heatmaps of RFM scores

Top & bottom customer comparisons

Product sales vs returns comparisons

All visuals are designed for business interpretation, not just technical analysis.

🧠 Key Insights

A small percentage of customers generate a large share of revenue

Certain products are sold frequently but also returned frequently

RFM segmentation clearly distinguishes customer value groups

Business actions can be tailored per segment:

Retention for best customers

Re-engagement for inactive customers

Quality checks for high-return products
