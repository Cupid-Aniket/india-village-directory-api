# India Village Directory SaaS Engine

A professional-grade B2B SaaS platform designed for high-performance geographical data retrieval. This system manages over 550,000 Indian village records using a robust FastAPI backend and a serverless PostgreSQL architecture.

## Overview

This project demonstrates a complete SaaS lifecycle, including secure API development, database optimization, and a centralized management dashboard. It is engineered to provide sub-second latency for address validation and location-based services.

## Technical Specifications

### Backend Architecture
- **Framework:** FastAPI (Asynchronous Python)
- **Database:** PostgreSQL (Hosted via NeonDB)
- **ORM:** SQLAlchemy for efficient query execution
- **Security:** Header-based API Key Authentication (X-API-KEY)
- **Concurrency:** Managed via Uvicorn and nest-asyncio

### Frontend Interface
- **Dashboard:** Unified Command Center for system monitoring
- **Styling:** Tailwind CSS Utility-first framework
- **Visualization:** Real-time traffic monitoring using Chart.js
- **Integration:** Vanilla JavaScript for low-overhead API consumption

## Core Functionalities

1. **Secure Search API:** Protected endpoint `/search/village` that allows clients to search villages by name with ILIKE pattern matching.
2. **Usage Tracking:** Automatic request counting per API key to support tiered subscription models.
3. **B2B Autocomplete:** A pre-built frontend module for seamless integration into e-commerce checkout forms.
4. **Traffic Analytics:** Real-time visualization of API hits and quota consumption.

## Installation and Setup

### Prerequisites
- Python 3.8+
- Active PostgreSQL instance (or NeonDB connection string)

### Local Deployment
1. Clone the repository:
   ```bash
   git clone [https://github.com/Cupid-Aniket/india-village-directory-api.git](https://github.com/Cupid-Aniket/india-village-directory-api.git)
