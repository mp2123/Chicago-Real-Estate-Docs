# Chicago Real Estate Data Platform

> **Status:** Private documentation shell
> **Privacy Note:** The core source code containing private data-access configuration, production `.env` files, database schema details, and ingestion logic is maintained in a private repository. This repository serves as a **public documentation shell** to illustrate the system architecture and data engineering workflow.

## Project Overview

A full-stack data platform for processing, aggregating, and visualizing real estate datasets across the Chicago area. The platform uses a Python backend to ingest property data, run geospatial queries, and serve insights through an API.

### Key Capabilities

- **Automated Data Pipelines:** Built ETL scripts to collect and clean real estate data, then persist records into a normalized relational database.
- **RESTful API Service:** Developed a Python API with FastAPI to handle authentication, data filtering, and geospatial queries for the frontend client.
- **Data Visualization UI:** Built a responsive frontend dashboard for filtering property records by location, valuation, and historical trends.

## Related Public Proof Shells

This repository is a public-safe docs shell for a private data-platform project. It should be read as supporting data-engineering and full-stack analytics context, while the live portfolio and other docs shells carry the main recruiter-facing proof map. Private implementation repos, database files, data-access configuration, credentials, and production runtime state are intentionally not linked publicly.

- [Portfolio project library](https://www.michaelspanico.com/projects)
- [Portfolio Website Docs](https://github.com/mp2123/Portfolio-Website-Docs)
- [Michael Panico GitHub profile](https://github.com/mp2123)

## Tech Stack

- **Backend:** Python, FastAPI, SQLAlchemy, Alembic, Celery
- **Database:** PostgreSQL / SQLite
- **Architecture:** API Orchestration, Distributed Tasks, ETL Pipelines

## Sanitized Code Excerpts

To demonstrate coding style and structural organization without exposing sensitive credentials, select boilerplate files (e.g., API entry points) are provided in the `examples/sanitized-code-excerpts/` directory.
