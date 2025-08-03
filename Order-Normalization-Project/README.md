# Order Normalization Project

📘 **Course:** CS726 – Relational Database Design  
📁 **Activity 7.2** – Normalization from 1NF to 3NF and ERD construction

## ✍️ Description

This project walks through a multi-step normalization of an unnormalized order data set.  
It identifies:
- Functional dependencies (partial and full)
- Transformation to 1NF, 2NF, and 3NF
- Final schema design
- ERD reflecting normalized tables

## 🛠️ Concepts Used
- Primary keys and composite keys
- Functional and transitive dependencies
- Normal forms: 1NF → 2NF → 3NF
- ERD modeling

## 📎 Artifacts
- `Activity 7.2 Solutions.pdf` – Full write-up including tables, functional dependencies, and final ERD

## ✅ Final Normalized Tables

- Order (OrderID, OrderDate)  
- Customer (CustomerID, CustomerName, CustomerState)  
- Product (ProductID, ProductName)  
- OrderCustomerProduct (OrderID, CustomerID, ProductID, Qty)
