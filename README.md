# 🛍️ E-commerce Database Design Project

## 📘 Overview

This project is part of a collaborative peer group assignment focused on designing and implementing a robust and scalable **e-commerce database** using MySQL. It includes a well-structured Entity-Relationship Diagram (ERD) and an SQL schema designed to support an e-commerce platform's core functionality like products, variations, images, attributes, and sizes.

---

## 🧑‍🤝‍🧑 Collaborators
- **Gerrykiptoo**

---

## 🗃️ Tables Included

The following tables are included in the schema:

1. **brand** – Stores brand-related data  
2. **color** – Manages available color options  
3. **product_category** – Classifies products into categories  
4. **product** – General product details including brand and category  
5. **product_image** – Stores image URLs or file references for each product  
6. **product_variation** – Links products to specific size and color variations  
7. **product_item** – Represents individual purchasable SKUs with stock and price  
8. **size_category** – Groups sizes (e.g., clothing, shoes)  
9. **size_option** – Specific size options like S, M, L, 42, etc.  
10. **attribute_category** – Groups custom attributes (e.g., physical, technical)  
11. **attribute_type** – Defines attribute data types (e.g., text, number)  
12. **product_attribute** – Stores custom product attributes (e.g., material, weight)

---

## 🗺️ ERD Diagram

The complete ERD has been designed using **MySQL Workbench** and exported as a PDF.

📎 [View ERD Diagram](ecommerce%20Diagram.pdf)

---

## 🧾 Setup Instructions

To set up the database locally:

1. Open your MySQL client or MySQL Workbench.
2. Run the SQL script file `ecommerce.sql` included in this repository.
3. This will create all tables and their relationships as per the ERD.

---

## 📬 Contact
For any queries related to this project, feel free to reach out via GitHub issues or contact the collaborators.

Let me know if you'd like me to generate the actual `ecommerce.sql` file based on your ERD too!

---

## 📂 Repository Structure

```plaintext
📁 E-COMMERCE-DATABASE-DESIGN/
├── ecommerce.sql               # SQL file to create the database schema
├── ecommerce Diagram.pdf       # Entity-Relationship Diagram
└── README.md                   # Project documentation


