# Finance-Backend
Scalable Finance Dashboard Backend built with Node.js &amp; Express.js . Feature role based access control (RBAC) , MongoDB Aggregation for real time analytics , and layered services-controller architecture . 


# Finance Data Processing & RBAC Backend

A professional-grade backend system designed for managing financial records with strict access control. Built with **Node.js**, **Express**, and **MongoDB**.

## 🚀 Key Features
- **User & Role Management**: Supports Admin, Analyst, and Viewer roles with distinct permission levels.
- **Financial CRUD**: Full lifecycle management of income and expense entries.
- **Advanced Analytics**: Dashboard summary API using MongoDB Aggregation for total income, expenses, and net balance.
- **Secure RBAC**: Custom middleware to enforce role-based restrictions on sensitive endpoints.
- **Data Integrity**: Schema-level validation and centralized error handling.

## 🏗️ Architecture
I followed the **Service-Controller-Repository** pattern to ensure a clean separation of concerns:
- **Controllers**: Handle HTTP requests and responses.
- **Services**: Contain the core business logic and database aggregations.
- **Models**: Define data structures and validation rules.
- **Middleware**: Manages authentication and role authorization.

## 🛠️ Tech Stack
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB (Mongoose ODM)
- **Environment**: Dotenv for secure configuration

## 🚦 Getting Started

### Prerequisites
- Node.js (v14+)
- MongoDB (Local or Atlas)
