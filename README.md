# Data Lake Architecture for Lyft

A data warehousing project that designs a Data Lake architecture for Lyft, a mid-size
business in the transportation industry, using AWS services.

> **Note on dates:** This project was originally completed in 2019 as a BAN 622 Data
> Warehousing group project during my MS in Business Analytics at California State
> University, East Bay. It was uploaded to GitHub in June 2026 after my previous GitHub
> account was deleted. Commit dates are set to reflect the original completion date.

## Overview

The objective of this group project was to design a Data Lake architecture for a
mid-size business outside of retail and hotel. We chose **Lyft** in the transportation
industry. The report describes how structured and unstructured data flow through the
architecture and how AWS services support storage, streaming, and analytics.

## Architecture Summary

The design assumes two primary stores:

- **Unstructured data:** Amazon DynamoDB, Amazon Kinesis, Amazon Redshift, Auto Scaling,
  and Amazon EC2 Container Registry
- **Structured data:** MySQL

### Data Sources

- **Transactional data:** driver and rider details, vehicle details, locations, trip
  duration and cost, and encrypted payment data
- **User (rider/driver) data:** personal account information, vehicle information, and
  driver registration details such as SSN
- **CRM systems data:** Salesforce Pardot and Sales Cloud used to identify prospects,
  convert leads, and drive customer loyalty
- **Human resource management data:** HR activity records

## Tech Stack

AWS (DynamoDB, Kinesis, Redshift, EC2 Container Registry, Auto Scaling), MySQL,
Salesforce CRM, data lake and data warehousing concepts.

## Files

- `BAN 622 Project.pdf` - full project report describing the Data Lake architecture

## Author

Kedar Patil - MS Business Analytics, California State University, East Bay
(group project)
