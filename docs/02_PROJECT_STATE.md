# Project State

## Project

**BetterHealth Data Platform**

Status: Active Development

Current Sprint: Sprint 2 – Foundation Data Platform

---

## Objective

Build a production-inspired Analytics Engineering project that simulates a modern Healthcare Data Platform while serving as a structured learning journey.

The primary goal is education, with the possibility of evolving selected components into portfolio assets and demonstrating modern Analytics Engineering practices.

---

## Current Technology Stack

### Infrastructure

* Docker Desktop
* Docker Compose

### Database

* PostgreSQL 17

### Analytics Engineering

* dbt Core

### Programming

* Python 3.12
* Virtual Environment (.venv)

### Version Control

* Git
* GitHub

### Database Tools

* DBeaver Community

### BI

* Power BI Desktop

### Planned

* Dagster (or Airflow)
* CI/CD
* Data Quality Framework
* Documentation Site
* Automated Testing

---

## Repository Structure

Current

betterhealth-data-platform/

* docker-compose.yml
* .env
* docs/
* handbook/
* dbt/
* .venv/

Planned

* dashboards/
* data/
* scripts/
* infrastructure/
* tests/

---

## Running Components

✅ Docker Desktop

✅ PostgreSQL 17

✅ Git

✅ GitHub

✅ Python

✅ dbt Core

✅ DBeaver

---

## Database

Engine:
PostgreSQL 17

Current Database:
lab_db

Current User:
Marek

Connection:
localhost:5432

Persistence:
Docker Volume

---

## Development Principles

* Docker-first development
* Infrastructure as Code
* Version-controlled project
* Documentation-first mindset
* Learn by building
* Enterprise-inspired architecture
* Explain architectural decisions
* Prefer understanding over memorization

---

## Current Architecture Vision

Healthcare Systems

↓

Data Ingestion

↓

Raw Layer

↓

Staging Layer

↓

Intermediate Layer

↓

Analytics Marts

↓

Power BI

↓

Future APIs / AI / Research

---

## Current Progress

Development environment is fully operational.

Git and GitHub are configured.

dbt is connected to PostgreSQL.

The project is ready to transition from environment setup into building the actual analytical platform.

The next milestone is implementing the first production-inspired data pipeline.
