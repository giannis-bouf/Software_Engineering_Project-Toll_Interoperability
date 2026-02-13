# Back-End - Toll Interoperability System

## Overview

The back-end component provides the core server-side functionality for the Toll Interoperability System. It implements a comprehensive RESTful API for managing toll operations, vehicle records, pass tracking, and toll station data.

## Technology Stack

- **Runtime**: Node.js
- **Architecture**: RESTful API
- **API Documentation**: Swagger/OpenAPI
- **Database**: SQL-based persistence
- **Data Format**: CSV for imports/data management

## Project Structure

### Core Files

- **`server.js`** - Main server application file containing all API endpoints and core business logic
- **`swagger.js`** - Swagger/OpenAPI configuration for API documentation
- **`tollstations2024.csv`** - Dataset containing toll station information for 2024

### Build Scripts

- **`build.bat`** - Windows batch script for building/running the backend
- **`build_modules.bat`** - Script for building/installing required modules

### Directories

- **`api_documentation/`** - API endpoint documentation and specifications
- **`db_scripts/`** - Database initialization and management scripts (SQL dumps, migrations)
- **`testing_api/`** - API testing files and test cases
- **`uploads/`** - Directory for handling file uploads from clients

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager
- Database system (MySQL, PostgreSQL, or similar)

### Installation

1. Navigate to the back-end directory:
   ```bash
   cd back-end
