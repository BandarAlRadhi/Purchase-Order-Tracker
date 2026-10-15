Purchase Order Tracker | Microsoft Excel

An Excel-based tool for monitoring purchase orders, goods receipts, supplier information, and delivery progress.

Tool: Microsoft Excel
Data: Sample data for demonstration purposes

Overview

This project streamlines purchase order monitoring by connecting order records, goods receipts, and supplier information in one workbook. Automated calculations track order values, received and outstanding quantities, delivery status, and days late, helping users identify orders that require follow-up.

Dashboard

<p align="center">
  <img src="screenshots./Dashboard-sheet.png" width="950" alt="Purchase Order Tracker Dashboard">
</p>

Key Features

Purchase Order Tracking

<p align="center">
  <img src="screenshots./Purchase-Orders-sheet1.png" width="1000" alt="Purchase Order Details">
</p>

<p align="center">
  <img src="screenshots./Purchase-Orders-sheet2.png" width="1000" alt="Purchase Order Quantities and Status">
</p>

Automatic calculation of purchase order values and remaining quantities.

Supplier name lookup using supplier IDs.

Automated order status and days-late calculations.

Filters and conditional formatting to support delivery follow-up.

Goods Receipt Tracking

<p align="center">
  <img src="screenshots./Receipts-sheet.png" width="900" alt="Goods Receipt Log">
</p>

Records each delivery separately, supports multiple receipts per purchase order, and aggregates received quantities automatically.

Supplier Directory

<p align="center">
  <img src="screenshots./Suppliers-sheet.png" width="1000" alt="Supplier Directory">
</p>

Maintains supplier details, contact information, supply categories, typical lead times, and sample supplier ratings.

Sample Results

The included dataset contains eight purchase orders and six goods receipt records.

Metric

Result

Total purchase order value

SAR 44,440.00

Total ordered quantity

694

Total received quantity

295

Total outstanding quantity

399

Approximate received value

SAR 18,125.00

These figures reflect the sample data and change as records are updated.

Automated Order Status

The workbook classifies orders as Scheduled, Partially Received, Overdue, Overdue - Partial, Complete, Incomplete, or Over-received, based on predefined rules and the recorded delivery information.

Excel Skills Demonstrated

SUMIF · INDEX · MATCH · IF · IFERROR · MAX · Conditional Formatting · Data Filtering · Dashboard Reporting

How to Use

Open the workbook in Microsoft Excel 2019 or a compatible version.

Maintain supplier records in Suppliers.

Enter purchase orders in Purchase Orders.

Record each delivery as a separate row in Receipts, using the matching purchase order number.

Review calculated quantities, delivery statuses, and dashboard metrics.

Note: Use unique purchase order and receipt IDs, and ensure each receipt references the correct purchase order.

Scope

This is an Excel-based portfolio project using illustrative sample data. It is not an integrated ERP system. Supplier contact details and ratings are fictional, and the received value is an approximate metric based on sample order prices and received quantities.

Download

Download the Excel Workbook

Author

Bandar Al Radhi
