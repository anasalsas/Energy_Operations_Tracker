# Energy Operations Tracker Dashboard

## Overview

This project demonstrates an operational reporting dashboard developed in Excel using advanced analytics features such as **Power Pivot, DAX Measures, PivotTables, VBA automation and Data Modelling**.

The objective of the project was to simulate a simplified operational reporting environment for an energy/utilities company, integrating CRM operational data with billing information to generate actionable KPIs and operational insights.

## Business Problem

Operational teams often struggle with fragmented information across systems, making it difficult to:

* Monitor operational tickets
* Track client workload
* Understand operational costs
* Identify data quality issues
* Produce management reporting efficiently

This dashboard was created to centralize operational and billing information into a single reporting view.

## Data Sources

### CRM Data

Contains operational ticket information:

* Ticket ID
* Date
* Client
* Issue Type
* Status
* Priority
* System

### Billing Data

Contains cost allocation information:

* Hours
* Cost
* Billing Status
* Client

## Data Ingestion

This dashboard is powered by two CSV files:

- CRM_EXPORT.csv
- BILLING_EXPORT.csv

For portfolio purposes, the CSV files were manually generated to simulate a realistic operational scenario for an energy/utilities environment.

The objective was to demonstrate how Excel can be used as a Proof of Concept (POC) for operational reporting, KPI monitoring and data modelling.


## Key KPIs

The dashboard includes several operational and financial KPIs:

* Total Cost
* Open Tickets
* Client Count
* Average Cost per Client
* Active Client Percentage
* Duplicate Check
* Monthly Ticket Trend
* Client Workload Overview

Additional KPI under development:

* Hourly Rate (€ / Hour)

## Excel Features Used

### Power Pivot

Used to build the data model and establish relationships between CRM and Billing datasets.

### Data Model

Created to connect multiple tables and support centralized KPI calculations.

### DAX Measures

Used to calculate dynamic KPIs such as:

* Total Cost
* Open Tickets
* Average Cost per Client
* Duplicate Detection

### Pivot Tables & Pivot Charts

Used to create dynamic reporting visuals.

### VBA Macro Automation

Created a macro to automatically export the dashboard into PDF format with timestamp versioning.

### Data Quality Controls

Implemented duplicate detection logic and KPI validation mechanisms.

## Dashboard Capabilities

* Dynamic KPI tracking
* Monthly operational trend analysis
* Ticket status monitoring
* Client workload visibility
* Billing overview
* PDF report generation

### VBA Macro Automation

A VBA macro was created to:

- Refresh dashboard data
- Update PivotTables and KPIs
- Export the dashboard automatically to PDF
- Generate timestamped report versions

This simulates a lightweight reporting automation workflow.


## Dashboard Preview

![Dashboard Preview](main/dashboard_preview.png)


## Future Improvements
* Power Query implementation for automated data cleaning
* Hourly rate anomaly detection
* Advanced data quality scoring
* Power BI migration
* UiPath automation for refresh and report distribution


## Skills Demonstrated

* Project Management Office (PMO)
* Reporting
* Data Analysis
* KPI Design
* Excel Advanced Analytics
* Power Pivot
* DAX
* Dashboard Design
* Process Improvement
* VBA Automation
* Operational Reporting

## Disclaimer

This project uses simulated data for demonstration and portfolio purposes.
