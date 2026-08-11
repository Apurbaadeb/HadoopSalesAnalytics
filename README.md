# Hadoop-Based Sales Analytics for Business Performance Analysis
Hadoop-based sales analytics project using HDFS, YARN, and MapReduce to analyze sales trends, regional performance, product categories, and sales channels.

## Overview
This project demonstrates a Hadoop-based Big Data solution for analyzing sales transactions using HDFS, YARN, and MapReduce.

## Problem Statement
The goal is to process sales transaction data at scale and identify:
- Monthly sales trends
- Regional sales performance
- Category-wise sales totals
- Channel-wise sales totals

## Technologies Used
- Hadoop
- HDFS
- YARN
- MapReduce
- Java
- Linux

## Dataset
The dataset contains 10,000 sales transaction records with fields such as:
- TransactionID
- Date
- CustomerID
- Product
- Category
- Region
- Quantity
- UnitPrice
- Sales
- PaymentMethod
- Channel

## HDFS Input Path
`/sales/input/sales.csv`

## Outputs
- `/sales/monthly-output`
- `/sales/region-output`
- `/sales/category-output`
- `/sales/channel-output`

## Key Findings
- Highest monthly sales: October 2026
- Highest-performing region: North
- Dominant category: Electronics
- Highest-performing sales channel: Online

## Future Scope
- Automated ingestion
- Larger datasets
- Real-time analytics
- Dashboards
- Predictive analytics
