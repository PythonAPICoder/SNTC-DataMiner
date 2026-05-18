# SNTC DataMiner

## Overview

SNTC DataMiner is a Python-based enterprise automation platform designed to simplify large-scale Cisco Smart Net Total Care (SNTC) data collection, reporting, and operational analysis.

By leveraging Cisco Services APIs, SNTC DataMiner automates the retrieval of Smart Net Total Care inventory, contract coverage, lifecycle, and installed base data across multiple customers and environments.

This enables partners, customers, support teams, renewals specialists, and operational stakeholders to replace time-consuming manual reporting processes with scalable, repeatable, and audit-friendly automation.

---

## Key Benefits

* Automates Smart Net Total Care inventory and services data collection
* Reduces manual operational overhead
* Improves customer asset visibility
* Accelerates contract and coverage analysis
* Supports lifecycle and renewal planning
* Standardizes reporting across customer environments
* Enables scalable partner and customer success workflows
* Provides structured exports for downstream analysis

---

## Business Value

### Partners

* Improve customer support readiness
* Accelerate installed base analysis
* Strengthen renewal opportunities
* Standardize recurring customer reports
* Increase operational efficiency

### Customers

* Gain better visibility into asset inventory
* Improve lifecycle planning
* Identify coverage gaps faster
* Support compliance and risk management
* Improve operational decision-making

### Internal Teams

* Support customer success initiatives
* Streamline technical support workflows
* Enable proactive risk identification
* Enhance sales and renewals intelligence

---

## Core Features

* Cisco Services API integration
* OAuth-secured authentication
* Automated customer and inventory data retrieval
* Smart Net Total Care installed base collection
* Contract and coverage analysis
* Pagination support
* Rate limiting and retry logic
* Configurable customer targeting
* CSV and JSON export support
* Summary reporting
* Modular configuration
* Multi-threaded scalable execution

---

## Technical Stack

* Python 3.10+
* Requests
* Pandas
* OpenPyXL
* PyYAML
* REST APIs
* OAuth2
* Multi-threading

---

## Use Cases

* Smart Net Total Care inventory reporting
* Installed base analysis
* Contract coverage validation
* Lifecycle and renewal planning
* Customer success operations
* Partner support automation
* Asset visibility improvement
* Compliance and risk assessment
* Cross-customer reporting

---

## Why SNTC DataMiner

Manual SNTC reporting is often:

* Slow
* Fragmented
* Labor-intensive
* Difficult to scale
* Inconsistent across teams

SNTC DataMiner solves these issues by providing:

### Faster Data Collection

Automates large-scale Cisco Services data retrieval.

### Better Visibility

Centralizes customer inventory, contract, and lifecycle data.

### Operational Efficiency

Reduces repetitive engineering and support tasks.

### Improved Business Intelligence

Enables proactive planning, renewals, and customer success.

---

## Installation

```bash
pip install requests pandas openpyxl pyyaml
```

---

## Basic Setup

1. Clone the repository:

```bash
git clone https://github.com/CiscoSteve/SNTC-DataMiner.git
```

2. Configure API credentials in `config.ini`

3. Run:

```bash
python SNTC_DataMiner.py
```

---

## Output

SNTC DataMiner generates:

* Smart Net Total Care inventory reports
* Installed base summaries
* Contract coverage exports
* Lifecycle analysis reports
* CSV datasets
* JSON datasets
* Error logs
* Audit-ready execution history

---

## Ideal Users

* Cisco Partners
* Customers
* Customer Success Engineers
* Support Teams
* Asset Management Teams
* Sales Teams
* Renewals Specialists
* Technical Operations Teams
* Automation Engineers

---

## Disclaimer

SNTC DataMiner is an independent automation solution and is not an officially supported Cisco product.

Users are responsible for:

* API credential management
* Compliance with Cisco API policies
* Responsible API usage
* Internal governance
* Operational validation

---

## Bottom Line

SNTC DataMiner transforms Cisco Smart Net Total Care data into actionable business intelligence by helping organizations:

### Save Time

### Improve Visibility

### Strengthen Renewals

### Reduce Manual Effort

### Scale Operational Reporting

It converts complex Cisco Services API data into practical customer, partner, and business value.
