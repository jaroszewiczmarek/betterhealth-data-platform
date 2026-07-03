# Project State

## Project

**BetterHealth Data Platform**

Status: Active Development

Current Sprint: Sprint 1 – Development Environment

---

## Objective

Build a production-inspired Analytics Engineering project that simulates a modern Healthcare Data Platform while serving as a structured learning journey.

The primary goal is education, with the possibility of evolving selected components into portfolio assets or future commercial ideas.

---

## Current Technology Stack

Infrastructure
- Docker Desktop
- Docker Compose

Database
- PostgreSQL 17

Operating System
- Windows 11

BI
- Power BI Desktop

Version Control
- Git

Planned
- Git
- GitHub
- dbt Core
- Dagster (or Airflow)
- CI/CD
- Data Quality Framework
- Documentation

---

## Repository Structure

Current

betterhealth-data-platform/

- docker-compose.yml
- .env
- docs/
- handbook/

Planned

- dbt/
- dashboards/
- data/
- scripts/
- infrastructure/
- tests/

---

## Running Components

✅ Docker Desktop

✅ PostgreSQL 17

✅ Git

✅ Persistent Docker Volume

✅ Docker Network

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

- Docker-first development
- Infrastructure as Code
- Reproducible environments
- Version-controlled project
- Documentation-first mindset
- Learn by building
- Enterprise-inspired architecture

---

## Current Architecture Vision

Healthcare systems

↓

Data ingestion

↓

Raw Layer

↓

Staging Layer

↓

Intermediate Models

↓

Analytics Marts

↓

Power BI

↓

Future:
AI / APIs / Research

---

## Current Progress

Environment is operational.

PostgreSQL is running.

The project is ready for Git initialization and dbt installation.

No business data has been created yet.

The next milestone is building the first analytical data pipeline.