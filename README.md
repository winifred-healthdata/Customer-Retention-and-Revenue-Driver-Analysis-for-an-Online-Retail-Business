# Customer-Retention-and-Revenue-Driver-Analysis

## Project Background

An international online retailer wants to understand the factors driving revenue growth and long-term business performance.
Management is interested in determining whether revenue is primarily driven by customer retention, product performance, 
market expansion, or a small group of high-value customers. 
They also want to understand customer purchasing behaviour and assess the financial impact of product returns on the business.
To support strategic decision-making, a comprehensive analysis was conducted using transactional retail data.

## Business Questions

This analysis was conducted to answer the following business questions:

1. Are repeat customers driving revenue, or is revenue primarily coming from new customers?

2. Which products generate the most revenue, and how concentrated is revenue across products?

3. Which countries contribute the most revenue and orders to the business?

4. What is the average order value (AOV), and how does it vary across customers and countries?

5. Is revenue evenly distributed across customers, or is it driven by a small group of high-value customers?

6. Which products experience the highest return activity, and how much revenue is lost through refunds?

## Dataset Overview

The dataset contains transactional sales records from an international online retail company. 
It captures information about the products customers purchased, including the quantity bought, the price paid, and the country from which the order originated.
Each row in the dataset represents a single product line within an invoice rather than an entire order. As a result, a single invoice may appear multiple times if a customer purchased several different products within the same transaction.
The data covers transactions made between December 2010 and December 2011.

### Key Variables

- **InvoiceNo** – Unique identifier for each transaction. Some invoiceNo starts with C. This means that the order was cancelled.
- **StockCode** – Unique product code assigned to each item.
- **Description** – Name or description of the product purchased.
- **Quantity** – Number of units purchased in each transaction. Quantity with negative number represents returned products.
- **InvoiceDate** – Date and time when the transaction occurred.
- **UnitPrice** – Selling price per unit of the product.
- **CustomerID** – Unique identifier assigned to each customer.
- **Country** – Country where the customer is located.
