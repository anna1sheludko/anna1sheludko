# Anna Sheludko

**she / her**

Data engineer. I move data from places where it's messy to places where it's useful.

Most of my job is convincing broken CSV files that they can, in fact, be parsed.
The rest is writing SQL that doesn't make the database cry.

Finishing a degree in **Data Engineering**  — 
which means I know the theory, and I'm now learning how much of it survives contact 
with production.

🌐 **Portfolio:** [anna1sheludko.github.io](https://anna1sheludko.github.io)

**Available for freelance work.** Remote, project-based, or ongoing retainers.
If you have data that needs moving, cleaning, or querying, we should talk.

## Things I use

![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-4169E1?logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-DB-F80000)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.2-150458?logo=pandas&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

## Full skill set

### Programming languages

- **Python** — main workhorse: Pandas, NumPy, psycopg2, SQLAlchemy
- **SQL / PL/SQL** — daily driver for anything database-related
- **C++** — object-oriented programming (studied, used in academic projects)
- **Java** — OOP and web applications (studied)
- **R** — statistical analysis and data exploration

### Databases & data warehousing

- **PostgreSQL** — schema design, indexes, `COPY`, query optimization
- **Oracle** — PL/SQL procedures, packages, triggers
- **MySQL / MS SQL Server** — relational design and administration
- **NoSQL** — document and key-value stores
- **Data warehouses** — dimensional modeling, star schema, ETL for BI
- **Graph & semantic databases** — RDF, SPARQL, relationship modeling
- **Big Data** — distributed storage and processing basics

### Data analysis & machine learning

- **Pandas / NumPy** — cleaning, transformation, aggregation
- **Statistics** — probability, hypothesis testing, forecasting, simulation
- **Machine learning** — regression, classification, clustering
- **Data mining** — pattern discovery, association rules
- **NLP** — text processing and analysis
- **Data visualization** — dashboards and reports that people actually read

### Infrastructure & tooling

- **Docker & Docker Compose** — reproducible environments
- **Git & GitHub Actions** — version control and CI/CD
- **Linux & Windows** — comfortable on both
- **Computer networks** — configuration basics (Cisco Academy)
- **Cloud & virtualization** — fundamentals of cloud computing and security

### Data quality & engineering practices

- **Pandera** — schema validation before data reaches the database
- **pytest** — unit testing for transform logic
- **ETL principles** — idempotency, retries with backoff, structured logging
- **YAML configuration** — declarative pipeline setup
- **Data security** — GDPR basics, data protection principles

### Business & soft skills

- **Project management** — Agile/Scrum basics
- **Economics & finance** — fundamentals of business context
- **Communication** — presenting, negotiating, writing clear technical docs
- **Innovation methods** — TRIZ, Design Thinking
- **Analytical tools** — advanced Excel (pivot tables, Power Query), GIS

## Projects

### [End-to-End ETL Pipeline with Python and PostgreSQL](https://github.com/anna1sheludko/end-to-end-pipeline)

A CSV → PostgreSQL pipeline for e-commerce data (~1.5M rows, 9 tables).
Extracts with retries, validates with Pandera, loads with `COPY` instead of `to_sql`
(because life is too short to wait for row-by-row inserts). Configured in YAML,
logged with rotation, tested with pytest, and runs in Docker.

**Stack:** `Python` `Pandas` `PostgreSQL` `Docker` `Pandera` `pytest` `GitHub Actions`

### [NBP Currency Rates ETL Pipeline](https://github.com/anna1sheludko/nbp-etl-pipeline)

A daily pipeline fetching official exchange rates from the National Bank of Poland
API into PostgreSQL. Incremental loading (no duplicates), retries on network failures,
scheduler for automatic twice-daily runs, and 11 unit tests.

**Stack:** `Python` `REST APIs` `PostgreSQL` `Docker` `pytest` `GitHub Actions`

---

More projects coming — unless I get distracted refactoring these two.
---

More projects coming — unless I get distracted refactoring this one.

## Contact

- **Email:** annasheludko152@gmail.com
- **GitHub:** [@anna1sheludko](https://github.com/anna1sheludko)
- **Portfolio:** [anna1sheludko.github.io](https://anna1sheludko.github.io)

Have a project in mind? The email works.
