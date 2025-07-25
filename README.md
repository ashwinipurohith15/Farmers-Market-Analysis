# Farmers-Market-Analysis Using Power BI

## Project objective

Fresh Connect is a conceptual or prototype grocery delivery application designed to connect customers with local vendors and fresh produce. This project focuses on the robust data infrastructure required to power such an application, including managing vendors, products, inventory, customer orders, and market schedules.

## Project Overview

Fresh Connect aims to provide a seamless experience for ordering groceries from multiple local vendors, potentially simulating a farmer's market experience delivered directly to the customer's door. This repository primarily showcases the design and interaction of the underlying datasets that support such an application, including how product availability, vendor management, and customer purchases are tracked and managed.

## Features

- Vendor & Booth Management: Organize vendors and their assigned physical or virtual "booths" within a market.

- Comprehensive Product Catalog: Categorize and manage a wide range of products, including details like price, unit, and description.

- Dynamic Inventory Tracking: Monitor real-time (or near-real-time) product availability from each vendor.

- Customer & Purchase Management: Store customer profiles and their historical order data.

- Market Scheduling: Handle the operational dates and times for various market events.

- Data-Driven Insights (Potential): The structured data can be used for analytics on popular products, peak ordering times, vendor performance, etc.


## Process

The application leverages these datasets to simulate a comprehensive grocery delivery service:

- Market & Vendor Setup: market_date_info defines when markets are active. vendor and booth information is used to set up sellers, and vendor_booth_assignments links them to specific market instances.

- Product Management: product and product_category create the product catalog.

- Inventory Updates: vendor_inventory is dynamically updated by vendors to reflect their available stock and current pricing for each product at a given market.

- Customer Interaction: Customers (customer) browse products, add them to a cart, and place orders.

- Order Processing: When an order is placed, customer_purchases records the transaction details, debiting from vendor_inventory.

- Data Analysis: The collected data across all these tables enables powerful analytics on sales trends, popular products, vendor performance, and customer behavior.

## Future Enhancements

- Real-time Inventory Sync: Implement APIs for vendors to update inventory directly.

- Delivery Logistics Module: Develop features for route optimization and delivery agent management.

- Payment Gateway Integration: Securely process online payments.

- User Authentication & Profiles: Robust user login and profile management.

- Recommendation Engine: Suggest products to customers based on past purchases and seasonal availability.

- Admin Dashboard: A web-based interface for market organizers to manage vendors, products, and view sales reports.

- Mobile App Interface: Develop a frontend for customers and delivery agents.

## Dashboard

   <img width="1313" height="806" alt="Farmers Dashboard" src="https://github.com/user-attachments/assets/86f0e096-0cd3-4aaf-9f10-b3cb85ffa924" />

   
