# SolveWithExcel – Challenge #8
## Customer Contribution Analysis (Pareto / 80–20 Rule)

This challenge introduces customer contribution analysis, commonly known as the Pareto (80–20) principle. You will calculate how much each customer contributes to total revenue, build cumulative percentages, and identify the customers responsible for the majority of sales.

This pattern is widely used in sales strategy, key account management, and executive reporting.

Difficulty
Intermediate

Estimated Time
25–35 minutes

# The Problem

In many businesses, a small group of customers generates most of the revenue.
The challenge is to quantify that concentration clearly and accurately.

Your task is to:

Calculate each customer’s share of total sales
Build a cumulative contribution percentage
Identify customers that make up the first 80% of revenue

All calculations must be done using Excel formulas.

# Dataset

CustomerSales columns:

Customer
Total Sales

The dataset represents a realistic revenue distribution across multiple customers.

# Your Tasks

## 1. Calculate Contribution %

Add a column:

Contribution % = Customer Sales / Total Sales (All Customers)

Format the result as a percentage.

## 2. Sort by Impact

Sort customers by Total Sales (descending) so the highest contributors appear first.

## 3. Calculate Cumulative %

Add a Cumulative % column that:

Adds each customer’s contribution to the sum of all previous customers
Increases row by row
Approaches 100% at the bottom of the list

## 4. Flag Top 80%

Add a Top 80% Flag column:
"Yes" if the customer’s cumulative contribution is ≤ 80%
"No" otherwise

# Learning Objectives

By completing this challenge, you will practice:

Contribution and concentration analysis
Building cumulative calculations
Applying the Pareto principle in Excel
Identifying high-impact customers

# Files Included

solvewithexcel_challenge_8_solution_hidden.xlsx
→ Contribution, cumulative %, and flags left blank for learners
solvewithexcel_challenge_8_solution_revealed.xlsx
→ Fully implemented Pareto analysis

# Why This Matters

Customer contribution analysis is used in:

Key account prioritization
Revenue concentration risk analysis
Pricing and discount strategies
Strategic sales planning
This challenge helps you focus effort where it matters most.

# Next Challenge

In the next challenge, you will:

Visualize contribution data using a Pareto chart
Combine bar charts with cumulative lines
Move toward executive-ready analysis visuals

# About SolveWithExcel

SolveWithExcel focuses on solving real-world business problems using Microsoft Excel through structured, challenge-based learning.

Visit https://solvewithexcel.org
 to learn more.
