# **Museum Database System**  
**COSC 3380 - University of Houston**  

## **Authors**
- Madeline Adair  
- Zeel Engineer  
- Kenny Nguyen  
- Chase Cotton  
- Shafnuddin Mohammad  

---

## **📌 Project Overview**
This project is a **full-stack web application** developed for the **Museum of Fine Arts, Houston (MFAH)** to manage their **art collections, exhibitions, ticket sales, gift shop revenue, and donations**. It consists of:
- A **frontend web client** for user interaction.
- A **backend API** to manage museum data.
- A **MySQL database** for persistent storage.

The system supports **user authentication, data entry, triggers, and complex queries** to facilitate museum operations and generate financial reports.

---

## **🖥️ Tech Stack**
| Component       | Technology |
|----------------|-----------|
| **Frontend**   | React.js, JavaScript |
| **Backend**    | Node.js, Express.js |
| **Database**   | Azure SQL Database |
| **Auth**       | JWT (JSON Web Tokens) |
| **Deployment** | Netlify (Frontend), Heroku (Backend) |

---

## **🏛️ Museum Features**
✔️ **User Authentication** (Role-based access control)  
✔️ **Data Entry Forms** (Create, update, delete museum records)  
✔️ **Database Triggers** (Automatic actions based on museum activity)  
✔️ **Data Queries & Reports** (Generate sales, artwork, and financial reports)  
✔️ **E-commerce Functionality** (Gift shop purchases and donations)  
✔️ **Ticketing System** (Buy museum tickets for exhibitions)  
✔️ **Admin Dashboard** (Different admin roles with specific permissions)  

---

## **🎯 Project Requirements**
### **📌 Triggers**
- ✅ **15% Discount** applied to shopping cart when total reaches **$100** (Customer view).  
- ✅ **Low Stock Alert** triggered when **stock levels reach 5** (Shop Manager view).  

### **📊 Data Reports**
- 📍 **Exhibition Sales Report** (Curator, Manager view).  
- 📍 **Financial Reports** for a specific time period (Director view).  
- 📍 **Artworks & Artists** added during a specific time period (Director, Manager view).  
- 📍 **Department Reports** for a specific period (Director view).  

### **🔍 Data Queries**
- 🔎 **Retrieve artworks** within a specific **collection, department, or exhibition**.  
- 🔎 **List employees** under a specific **manager or department** (Manager view).  
- 🔎 **Find artworks, exhibitions, and collections** under a specific **department** (Manager view).  
- 🔎 **Track artworks and exhibitions** curated by a **specific curator** (Curator view).  

---

## **👤 User Roles & Permissions**
| **Role**      | **Permissions** |
|--------------|----------------|
| **Director** | Full access & modification of all museum data. |
| **Manager** | Modify data under their department. |
| **Shop Manager** | Modify shop catalog, manage transactions, track sales. |
| **Curator** | Manage exhibitions & collections they oversee. |
| **Customer** | Purchase tickets, make donations, use gift shop, view order history. |

### **📝 Editable Data Categories**
- **Employees**  
- **Gift Shop Items**  
- **Exhibitions**  
- **Artworks**  
- **Collections**  
- **Departments**  

---
