# Architecture Decisions

---

## ADR-001

### Decision

The project will simulate a modern healthcare analytics platform instead of a simple tutorial dataset.

### Status

Accepted

### Reason

Provides a realistic enterprise scenario.

Supports advanced Analytics Engineering concepts.

Can evolve naturally as new technologies are introduced.

---

## ADR-002

### Decision

Docker will be used as the primary development environment.

### Status

Accepted

### Reason

Provides reproducible environments.

Supports Infrastructure as Code.

Matches modern Data Engineering practices.

---

## ADR-003

### Decision

PostgreSQL will be used as the analytical database.

### Status

Accepted

### Reason

Open-source.

Widely supported by dbt.

Excellent platform for learning modern Analytics Engineering.

---

## ADR-004

### Decision

Power BI will be used as the visualization layer instead of Metabase.

### Status

Accepted

### Reason

Aligns with existing professional experience.

Allows focusing on Analytics Engineering rather than learning another BI tool.

---

## ADR-005

### Decision

Learning takes priority over implementation speed.

### Status

Accepted

### Reason

The primary objective of the project is education.

Architectural understanding is more valuable than rapid implementation.

---

## ADR-006

### Decision

dbt Core will be used as the transformation framework.

### Status

Accepted

### Reason

SQL-first approach.

Industry standard for Analytics Engineering.

Version-controlled transformations.

Excellent integration with PostgreSQL.

Supports modular, testable and documented data models.
