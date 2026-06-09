# Chicago Real Estate Data Platform

> **Status:** Active
> **Privacy Note:** The core source code containing proprietary data access tokens, production `.env` files, database schema details, and ingestion logic is maintained in a private repository. This repository serves as a **public documentation shell** to illustrate the system architecture and data engineering workflow.

## Project Overview

A robust, full-stack data platform designed to process, aggregate, and visualize real estate datasets across the Chicago area. The platform utilizes a Python backend to ingest property data, execute complex geospatial queries, and serve insights via an API.

### Key Capabilities

- **Automated Data Pipelines:** Engineered ETL scripts to routinely harvest and clean raw real estate data, persisting records into a normalized relational database.
- **RESTful API Service:** Developed a high-performance Python API (FastAPI) to handle authentication, data filtering, and geospatial queries for the frontend client.
- **Data Visualization UI:** Deployed a responsive frontend dashboard allowing users to filter property records by location, valuation, and historical trends.

## Tech Stack

- **Backend:** Python, FastAPI, SQLAlchemy, Alembic, Celery
- **Database:** PostgreSQL / SQLite
- **Architecture:** API Orchestration, Distributed Tasks, ETL Pipelines

## Sanitized Code Excerpts

To demonstrate coding style and structural organization without exposing sensitive credentials, select boilerplate files (e.g., API entry points) are provided in the `examples/sanitized-code-excerpts/` directory.
