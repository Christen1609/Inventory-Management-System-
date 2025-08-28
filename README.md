# Inventory-Management-System-
Management Alert tool, built using the MongoDB, React and Nodejs.  This tool is used to manage the inventory of small-scale industry and  alert restock requirement



## Project Overview  
The **Management Alert Tool** is a full-stack web application built using **MongoDB, Express.js, React, and Node.js (MERN stack)**.  
It is designed for small-scale industries to manage their inventory efficiently and generate alerts when restocking is required.  

Key features include:  
- User authentication (admin login).  
- Inventory management (add, update, delete items).  
- Real-time alerts for low stock.  
- Sales tracking and billing.  
- Customer information management.  
- Dashboard with sales and inventory insights.  

---

## Repository Contents  
- **server.js** – Node.js backend server with Express and MongoDB schemas for products, users, customers, sales, and alerts.  
- **views/** – EJS templates for UI (Dashboard, Inventory, Sales, Billing, Alerts, Sign-in).  
- **public/css/** – Stylesheets for tables, dashboard, and inventory management.  
- **models/** – MongoDB schemas for `Product`, `User`, `Sale`, `Customer`, `Cart`, and `Alert`.  
- **routes/** – Handles inventory, billing, sales, and dashboard endpoints.  

---

## Project Workflow  
1. **Authentication** – Admin login via sign-in page.  
2. **Inventory Module** – Add, update, delete products; automatic stock updates.  
3. **Alert Module** – Alerts are triggered if item quantity falls below a threshold (≤ 5).  
4. **Billing Module** – Add items to a cart, checkout, and update stock automatically.  
5. **Customer Module** – Store customer details and purchased items.  
6. **Sales Module** – Track sales performance and profits.  
7. **Dashboard** – Display key statistics: total items, sales percentage, top-selling products, and alerts.  

---

## Technologies Used  
- **Frontend:** React.js, EJS templates, Bootstrap, CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Libraries:** Mongoose, Body-parser  

---

## How to Run the Project  
1. Clone the repository:  
   ```bash
   git clone <repository-url>
   cd management-alert-tool
2.Install dependencies:

    npm install


3.Start MongoDB server locally:

    mongod


4.Run the Node.js server:

    node server.js


5.Open in browser:

    http://localhost:3000

---

##Results & Highlights

Alerts: Automatic notifications for low-stock items.

Efficiency: Simplifies billing, customer tracking, and sales recording.

Dashboard: Real-time view of inventory status, alerts, and top-selling products.
    
