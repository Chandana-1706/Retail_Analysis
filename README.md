**Problem Statement:**

The objective of this project is to develop a Power BI dashboard using the Retail Database to provide comprehensive insights into the retail business's performance. The dashboard will focus on sales, product, customer, and demographic analysis, aiming to facilitate data-driven decision-making, optimize sales strategies, and enhance customer experiences. The goal is to empower retail stakeholders with actionable insights, enabling them to identify top-selling products, customer preferences, and target demographics. The dashboard will offer valuable insights and recommendations for targeted marketing, inventory optimization, and personalized customer experiences. The final deliverables will include a report and presentation showcasing the dashboard's findings and significance, serving as a powerful tool for retail stakeholders to improve business strategies and achieve success in the competitive retail market.

**Dataset Description:**

The retail dataset provided contains valuable information about a retail company, capturing various aspects of its operations. This dataset is essential for understanding and analyzing the company's offices, employees, customers, products, product lines, orders, order details, and payments.

**Table Explanations:**

  **Offices Table:**
This table stores information about the different offices of the retail company, including the office code, city, phone number, address, state, country, postal code, and territory. Each office is uniquely identified by its office code.

  **Employees Table:**

The employees table holds data about the company's employees. It includes fields such as employee number (a unique identifier for each employee), last name, first name, extension, email address, office code (identifying the office where the employee works), reportsTo (the employee number of the person to whom the employee reports), and job title.

  **Customers Table:**

This table contains information about the retail company's customers. It includes fields like customer number (a unique identifier for each customer), customer name, contact last name, contact first name, phone number, address, city, state, postal code, country, sales representative employee number (identifying the employee responsible for the customer), and credit limit.

  **Products Table:**

The products table stores details about the various products sold by the retail company. It includes information such as the product code (a unique identifier for each product), product name, product line (categorization of the product), product scale, product vendor, product description, quantity in stock, buy price, and Manufacturer's Suggested Retail Price (MSRP).

  **Product Lines Table:**

This table is used to describe the different product lines available in the company's inventory. It includes fields such as the product line name, text description, HTML description (for web-based content), and an image (stored as a BLOB) to represent the product line visually.

  **Orders Table:**

The orders table stores data related to customer orders. It includes information like the order number (a unique identifier for each order), order date, required date, shipped date, order status (using an ENUM for predefined statuses), comments, and customer number (identifying the customer who placed the order).

  **Order Details Table:**

This table contains information about the individual items (line items) included in each order. It includes fields such as the order number (linking to the orders table), product code (linking to the products table), quantity ordered, price per item, and order line number.

  **Payments Table:**

The payments table stores details about payments made by customers. It includes fields such as the customer number (linking to the customers table), check number, payment date, and the payment amount.

**Screen shots of PowerBi dashboard:**
![image](https://github.com/user-attachments/assets/af68c1fd-ae11-4848-9783-61caba98b84c)
![image](https://github.com/user-attachments/assets/aa7b5295-ac4f-4c3e-8b4d-a1bb942b702e)
![image](https://github.com/user-attachments/assets/8e20a20d-f21e-46d9-ba24-e2bb0cdb937e)
![image](https://github.com/user-attachments/assets/0eaa1023-1401-4624-baf6-38f648b32681)




