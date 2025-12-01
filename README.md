# Weekly Assignment — Delta Lake–Based Data Storage (ShopEZ)

This project implements a **Delta Lake–based data storage system** on **Databricks Serverless** for an e-commerce company called **ShopEZ**.  
It demonstrates how to build a **scalable, reliable, and optimized** data architecture using Delta Lake features such as partitioning, ACID transactions, schema evolution, time travel, and performance tuning.

---

## 📌 Project Overview

ShopEZ generates **millions of orders daily** across different countries.  
To store and manage this massive data efficiently, Delta Lake on Databricks is used to:

- Store data in cloud storage using **Delta format**
- Partition data by **country** and **order_date**
- Support **ACID transactions**
- Allow **Time Travel** to older data versions
- Enable **Schema Evolution**
- Perform **Updates** and **Deletes**
- Optimize performance using **OPTIMIZE** and **ZORDER**
- Demonstrate and fix the **small-file problem**

The project is fully implemented on:

- ✔ Databricks Free Edition (Serverless)
- ✔ Unity Catalog Volumes
- ✔ PySpark / Spark SQL

---
