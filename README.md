Purchase Order Tracker | Microsoft Excel

A practical Excel workbook for tracking purchase orders, goods receipts, supplier information, delivery progress, and outstanding quantities.

Tool: Microsoft Excel
Project Type: Procurement & Purchase Order Monitoring
Data: Sample data for demonstration purposes

Project Overview

This project provides a structured Excel solution for monitoring purchase orders, recording goods receipts, maintaining supplier information, and tracking delivery performance.

It connects purchase orders with individual receipt records and supplier data, while automatically calculating order values, received quantities, remaining quantities, delivery status, and days late.

The dashboard provides a consolidated view of purchasing activity and highlights orders that may require follow-up.

Dashboard Preview

<p align="center">
  <img src="screenshots./Dashboard-sheet.png" width="950" alt="Purchase Order Dashboard">
</p>

The dashboard includes:

Total purchase orders

Total purchase order value (SAR)

Overdue orders

Completion rate

Order status distribution

Ordered, received, and outstanding quantities

Approximate value of received goods

Key Features

1. Purchase Order Tracking

<p align="center">
  <img src="screenshots./Purchase-Orders-sheet1.png" width="1000" alt="Purchase Orders - Order Details">
</p>

<p align="center">
  <img src="screenshots./Purchase-Orders-sheet2.png" width="1000" alt="Purchase Orders - Quantities and Status">
</p>

Record purchase order numbers, suppliers, item descriptions, categories, and delivery dates.

Retrieve supplier names using supplier IDs.

Calculate purchase order values automatically.

Track ordered, received, and remaining quantities.

Calculate the latest receipt date and days late.

Automatically assign order statuses.

Use filters to identify orders requiring follow-up.

2. Goods Receipt Tracking

<p align="center">
  <img src="screenshots./Receipts-sheet.png" width="900" alt="Goods Receipt Log">
</p>

Record each delivery as a separate receipt event.

Link each receipt to its corresponding purchase order.

Support multiple deliveries against one purchase order.

Aggregate received quantities automatically in the Purchase Orders worksheet.

3. Supplier Directory

<p align="center">
  <img src="screenshots./Suppliers-sheet.png" width="1000" alt="Supplier Directory">
</p>

Maintain unique supplier IDs and supplier names.

Store contact details and supply categories.

Record typical supplier lead times and sample supplier ratings.

Link suppliers to purchase orders using supplier IDs.

Workbook Structure

Worksheet

Purpose

Dashboard

Summarizes purchasing KPIs, order statuses, and quantity metrics.

Purchase Orders

Tracks order details, values, quantities, delivery dates, and status.

Receipts

Records individual goods receipt events.

Suppliers

Maintains supplier details and sample supplier information.

Read Me

Provides instructions and workbook assumptions.

Sample Data Snapshot

The workbook contains eight sample purchase orders and six sample goods receipt records.

Metric

Sample Result

Total Purchase Orders

8

Total PO Value

SAR 44,440.00

Total Ordered Quantity

694

Total Received Quantity

295

Total Outstanding Quantity

399

Approximate Received Value

SAR 18,125.00

These figures represent the included sample data and may change when records or delivery dates are updated.

Automated Order Status

The workbook uses predefined rules to classify purchase orders:

Status

Description

Scheduled

No goods have been received and the order is not overdue.

Partially Received

Some goods have been received and the order is not overdue.

Overdue

The promised delivery date has passed and no goods have been received.

Overdue - Partial

The order is overdue and remains partially received.

Complete

The full ordered quantity has been received without over-receipt.

Incomplete

Required information, such as ordered quantity or promised delivery date, is missing.

Over-received

Total received quantity exceeds the ordered quantity.

Status results depend on the workbook's predefined rules and Excel's current calculation date.

Excel Skills Demonstrated

SUMIF for aggregating receipt quantities by purchase order

INDEX and MATCH for retrieving supplier names

IF and IFERROR for status logic and error handling

MAX for remaining quantity and days-late calculations

Conditional formatting for visual status indicators

Data filtering for order review and follow-up

KPI reporting and dashboard development

How to Use

Open the workbook in Microsoft Excel 2019 or a compatible version.

Review the Dashboard worksheet for a summary of purchasing activity.

Add supplier records to Suppliers, ensuring supplier IDs are unique.

Enter purchase order details in Purchase Orders.

Record every delivery as a separate row in Receipts, using the matching purchase order number.

Review the calculated received quantity, remaining quantity, latest receipt date, and order status.

Filter orders by status to identify items requiring supplier follow-up.

Data-entry reminder: Use unique purchase order numbers and receipt IDs. Enter dates and quantities consistently, and ensure every receipt references the correct purchase order.

Scope and Assumptions

All included records are sample data for portfolio demonstration.

This is an Excel-based tracking tool, not an integrated ERP or procurement management system.

Dashboard results depend on the entered data and Excel calculation settings.

Received value is an approximate metric based on sample order prices and received quantities.

Supplier contact details and ratings are illustrative sample information.

Download the Workbook

Download the complete Excel workbook from this repository:

Download Purchase Order Tracker

Author

Bandar Al Radhi

This project was developed as a practical portfolio project demonstrating the application of Excel to procurement operations and purchase order monitoring.
