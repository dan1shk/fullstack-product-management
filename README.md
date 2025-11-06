# Fullstack Product Management System

**Tech Stack:** Angular 17, Node.js, Express, PostgreSQL

A production-ready product management system with advanced features including bulk upload, report generation, and comprehensive CRUD operations.

##  Core Requirements 

All assignment requirements completed:
-  User CRUD with JWT authentication
-  Category CRUD (hierarchical with status)
-  Product CRUD (16 comprehensive fields)
-  Bulk Upload (handles 10,000+ products, zero timeout)
-  Report Generation CSV/XLSX (streaming, no timeout)
-  Server-side pagination, sorting, search
-  Complete Postman collection

##  Quick Start

### Prerequisites
- Node.js 18+
- PostgreSQL 12+
- Angular CLI 17+

### Backend Setup
```bash
cd backend
npm install
cp .env.example .env
# Edit .env with your database credentials
createdb assessment_db
psql -U postgres -d assessment_db -f schema.sql
npm start
```

### Frontend Setup
```bash
cd frontend
npm install
ng serve
```

**Access:**
- Frontend: http://localhost:4200
- Backend: http://localhost:5000
