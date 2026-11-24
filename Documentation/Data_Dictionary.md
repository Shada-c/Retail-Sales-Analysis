# Data Dictionary – Retail Sales Analysis

This document describes the six datasets used in the Retail Sales Analysis project.

## 1. Orders Dataset
Contains information about customer orders.
- Order ID: Unique identification for each order.
- Customer ID: Identifies the customer.
- Order Date: Date when the order was placed.
- Order Status: Current status of the order.

## 2. Order Details Dataset
Contains product-level details for each order.
- Order Detail ID: Unique identification for each order item.
- Order ID: Connects the item to an order.
- Product ID: Identifies the purchased product.
- Quantity: Number of units purchased.
- Unit Price: Price per unit.

## 3. Customers Dataset
Contains customer information.
- Customer ID: Unique customer identification.
- Customer Name: Name of the customer.
- Gender: Customer gender.
- Age: Customer age.
- City: Customer city.
- State: Customer state.

## 4. Products Dataset
Contains product information.
- Product ID: Unique product identification.
- Product Name: Name of the product.
- Category: Product category.
- Brand: Product brand.
- Unit Price: Product selling price.

## 5. Stores Dataset
Contains information about retail stores.
- Store ID: Unique store identification.
- Store Name: Name of the store.
- City: City where the store is located.
- State: State where the store is located.

## 6. Payments Dataset
Contains payment-related information.
- Payment ID: Unique payment identification.
- Order ID: Connects payment to an order.
- Payment Method: Method used for payment.
- Payment Amount: Amount paid.
- Payment Status: Status of the payment.