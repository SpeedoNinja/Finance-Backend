# Finance Dashboard Backend

## Overview
This is a Node.js/Express backend designed for a finance management system. It implements Role-Based Access Control (RBAC) to ensure data integrity across different user levels.

## Key Decisions
- **Architecture**: Used a Service-Controller pattern to keep business logic (like financial aggregations) separate from HTTP logic.
- **RBAC**: Implemented a flexible middleware that checks the `x-role` header to simulate authenticated roles (Admin, Analyst, Viewer).
- **Data Integrity**: Used Mongoose schemas with enums to prevent invalid categories or transaction types.

## Assumptions
- For this assessment, authentication is mocked via headers. In a production scenario, this would be replaced by JWT verification.
- The 'Viewer' role is restricted from any write/update/delete operations to maintain data security.

## How to Run
1. Run `npm install`
2. Configure `.env` with your MongoDB URI
3. Run `npm start`
