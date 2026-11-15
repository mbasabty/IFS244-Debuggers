# IFS244 Group Assignment 2026: OT Business Information System

University of the Western Cape, IFS244
Built with Oracle SQL, PL/SQL and Oracle APEX

## 1. Overview

This project is a business information system for OT, built on one Oracle database schema and exposed through two Oracle APEX applications:

| Application | App ID | Purpose |
|---|---|---|
| **O.T Company** | 200323 | Admin app with reports, interactive grids and analytics dashboards |
| **O.T Customer Portal** | 152107 | Customer-facing app where customers browse products and place orders |

Both applications run on the same schema, so an order placed in the Customer Portal appears immediately in the admin reports.

## 2. Login Details

### O.T Company (Admin)
- **URL:** https://oracleapex.com/ords/r/group_5_debuggers/o-t-company/login
- **Username:** `4540469@myuwc.ac.za`
- **Password:** `4540469@Mb!`

### O.T Customer Portal (Customer)
- **URL:** https://oracleapex.com/ords/r/group_5_debuggers/o-t-customer-portal/home


## 3. Features

### O.T Company (Admin)
- Reports on customers, products, orders and employees
- Interactive grids for viewing and editing data
- Analytics dashboard with charts and key business insights

### O.T Customer Portal
- Product browsing
- Order form for placing orders
- Order confirmation

## 4. Database

- Oracle SQL tables, constraints and relationships (see the data model in the report)
- PL/SQL procedures, functions and triggers supporting the business logic
- Shared schema used by both APEX applications

## 5. How to Run

1. Open the O.T Company URL in section 2 and log in with the admin details.
2. Open the O.T Customer Portal URL and log in with the customer details.
3. To test the full flow, place an order in the Customer Portal, then check it in the admin reports.

### 5.1 Importing the Applications (if needed)

1. In APEX, go to **App Builder → Import**.
2. Upload the exported application `.sql` file.
3. Install the supporting objects and run the database scripts in this order:
   1. Table creation script
   2. Data insert script
   3. PL/SQL objects script

## 6. Group Members

| Name |
|---|
| Mbasa |
| Sekwele |
| Dineo |
| Kealeboga |
| Thapelo |
