# SAP S/4HANA Cloud – End-to-End Manufacturing & Business Processes Simulation

This repository documents an end-to-end discrete manufacturing and supply chain simulation implemented on **SAP S/4HANA Cloud (Plant 1710 / US Model Company)**. The project serves as a portfolio case study demonstrating standard ERP business processes, master data structures, and operational workflows.

---

## 🏭 Project Overview
The objective of this project is to simulate and document standard ERP implementation steps—from raw material management to finished goods production and sales execution—using SAP's best practices environment.

* **System Environment:** SAP S/4HANA Cloud (Trial / Model Company)
* **Plant Location:** Plant 1 US (`1710`)
* **Industry Sector:** Discrete Manufacturing & Assembly (Bikes & Industrial Equipment)

---

## 📂 Repository Structure

```text
├── 01-Master-Data/
│   └── Product-Lists.xlsx         # Material Master Data (ROH, HALB, FERT)
├── 02-Business-Processes/
│   ├── Procure-to-Pay (P2P).md    # Raw material procurement workflows
│   ├── Make-to-Stock (MTS).md     # BOM, Routings, and Production Orders
│   └── Order-to-Cash (O2C).md     # Sales order creation to delivery & billing
└── 03-Analytics/
    └── Fiori-Reports.md           # Operational and analytical Fiori dashboard screenshots
