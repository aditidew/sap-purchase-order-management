# SAP ABAP Purchase Order Management — Case Study

**A comprehensive SAP ABAP sprint evaluation exploring Purchase Order management, enterprise data handling, service integration, and modern ABAP development.**

## About the Project

This project was completed as part of an SAP ABAP sprint evaluation. The case study focuses on Purchase Order management and the challenge of bringing together header-level and item-level information for better tracking, data handling, and analysis of procurement operations.

The implementation was performed within the SAP development environment. The project covers multiple SAP ABAP concepts, from custom table creation and classical reporting to OData services, CDS Views, and the RESTful ABAP Programming Model (RAP).

This repository documents the project scope, implemented modules, technologies explored, and evaluation presentation. The ABAP source code is not included because the development was performed directly in the SAP environment and the source files are not available in this repository.

## Problem Statement

Purchase Order management requires access to information across different data structures, including Purchase Order headers, items, purchasing history, and supplier details.

Without a consolidated view, tracking procurement activities and analyzing purchasing information can become difficult.

The objective of this case study was to explore a structured solution using SAP ABAP to organize and present Purchase Order information while demonstrating different reporting, integration, and application development techniques.

## Project Objectives

- Create custom database tables for Purchase Order and supplier-related information.
- Maintain and display data using SAP table maintenance and ABAP programs.
- Develop interactive ALV reports for structured data presentation.
- Generate formatted documents using Adobe Forms.
- Expose and manage data through OData CRUD operations.
- Explore CDS Views and extension views for reusable data modeling.
- Implement different RAP scenarios, including read-only, managed, and unmanaged operations.
- Integrate standard business operations using BAPIs.
- Explore email notifications, singleton-based editing, and OData client proxy consumption.

## Technologies and Concepts

| Technology | Application in the Case Study |
|---|---|
| SAP ABAP | Core development and business logic |
| Table Maintenance Generator (TMG) | Custom table maintenance |
| ABAP Objects and ALV Grid | Interactive report development |
| Adobe Forms | Structured document output |
| SAP Gateway and OData | Data exposure and CRUD operations |
| BAPI | Standard business function integration |
| CDS Views | Data modeling and reusable data access |
| CDS Extension Views | Extending existing CDS definitions |
| RAP Read-Only | Read-only data access |
| RAP Managed | Framework-managed transactional operations |
| RAP Unmanaged | Custom transactional implementation |
| RAP with BAPI | Business operation integration |
| RAP Actions and Email | Action-triggered email functionality |
| RAP Singleton | Singleton-based editing and multi-record updates |
| OData Client Proxy | Consumption of an OData service from ABAP |

## Modules Implemented

### 1. Database Tables and Table Maintenance
Created custom tables for Purchase Order header data, item data, purchasing history, and supplier information. Explored table maintenance using TMG.

### 2. Table Output
Developed programs to retrieve and display data from the custom tables.

### 3. Object-Oriented ALV
Worked with an object-oriented ALV report to present Purchase Order information in a structured and interactive format.

### 4. Adobe Forms
Designed and demonstrated formatted Purchase Order output using Adobe Forms.

### 5. OData CRUD Services
Explored Create, Read, Update, and Delete operations to expose and manage backend data through OData services.

### 6. BAPI Function Call
Worked with a BAPI to demonstrate standard SAP business functionality through an ABAP program.

### 7. CDS View and Extension View
Created a CDS View and an extension view to explore reusable data modeling and extending existing definitions.

### 8. RAP Read-Only
Implemented a read-only RAP scenario for retrieving data without modifying the underlying records.

### 9. RAP Managed
Explored framework-managed transactional operations using the managed RAP scenario.

### 10. RAP Unmanaged
Implemented an unmanaged RAP scenario to explore custom control over transactional behavior.

### 11. RAP Material Creation Using BAPI
Integrated a BAPI-based material creation operation into a RAP application scenario.

### 12. RAP Email Notification
Explored sending email notifications through RAP-based functionality.

### 13. RAP Singleton with Multi-Record Editing
Demonstrated a singleton-based RAP scenario involving multi-record editing and integration with table maintenance concepts.

### 14. OData Client Proxy
Explored consuming an OData service from ABAP using the client proxy approach.

## Project Documentation

The repository includes the case study presentation documenting the project problem statement, modules, implementation evidence, and output screenshots captured during the evaluation.

**Presentation:** `docs/SAP-ABAP-Purchase-Order-Case-Study.pdf`

The presentation serves as the primary project documentation because the implementation was performed in the SAP environment and the source code is not available for publication here.

## Key Learning Outcomes

Through this case study, I explored:

- Classical ABAP development and object-oriented reporting.
- Custom table design and data presentation.
- SAP Gateway and OData service operations.
- CDS-based data modeling and extensions.
- Differences between managed and unmanaged RAP scenarios.
- Integration of BAPIs with ABAP and RAP.
- Adobe Forms and formatted document generation.
- Consumption of external services through the OData client proxy approach.

## Repository Structure

```text
sap-purchase-order-management/
├── README.md
└── docs/
    └── SAP-ABAP-Purchase-Order-Case-Study.pdf
```

## About Me

**Aditi Dewangan**

SAP ABAP Developer | Interested in SAP S/4HANA, enterprise application development, service integration, and AI-driven automation.

This project represents my practical learning and implementation experience across different SAP ABAP development concepts.

---

*Note: This is a documentation-based portfolio repository. The original development was performed in an SAP environment; source code and executable project files are not included. The project presentation is shared subject to applicable academic and organizational permissions.*
