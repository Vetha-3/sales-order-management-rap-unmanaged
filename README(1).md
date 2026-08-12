# Sales Order Management Application – SAP ABAP RAP Unmanaged

## Overview

A Sales Order Management Application developed using SAP ABAP RESTful Application Programming Model (RAP) with an Unmanaged implementation approach.

The application manages Sales Order Header and Item data. In the unmanaged model, business logic and persistence are handled manually through ABAP behavior implementation and saver classes.

## Technologies

- SAP ABAP
- ABAP RESTful Application Programming Model (RAP)
- CDS Views
- Behavior Definitions
- Behavior Implementation Classes
- EML
- OData V4
- Fiori Elements
- Eclipse ADT

## Architecture

Database Tables
→ Interface CDS Views
→ Consumption CDS Views
→ Metadata Extensions
→ Behavior Definition
→ Behavior Implementation
→ Saver Class
→ Projection Behavior
→ Service Definition
→ OData V4 Service Binding
→ Fiori Elements Preview

## Main Features

- Sales Order Header and Item management
- Create, Read, Update and Delete processing
- Manual unmanaged behavior implementation
- Buffer/utility class for request data
- Draft support
- OData V4 service exposure
- Fiori Elements preview

## Repository Structure

```text
sales-order-management-rap-unmanaged/
├── README.md
├── documentation/
│   ├── SAP_RAP_Unmanaged_Project_Documentation.docx
│   └── SAP_User_Manual.pdf
├── screenshots/
└── src/
    ├── database/
    ├── cds/
    ├── behavior/
    ├── service/
    └── classes/
```

## Development Environment

Eclipse IDE with SAP ABAP Development Tools (ADT), connected to the required SAP system.

## Documentation

See `documentation/SAP_RAP_Unmanaged_Project_Documentation.docx` for the complete step-by-step project documentation.

## Screenshots

Add screenshots of:
- ADT project
- Database tables
- CDS views
- Behavior definition
- Behavior implementation
- Service definition
- Service binding
- Fiori Elements application

## Security

Do not commit SAP credentials, passwords, private system URLs, API keys, certificates or other confidential information.

## Author

**VETHATHIRI E**

B.E. Computer Science Engineering
