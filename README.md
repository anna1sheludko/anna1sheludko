# Anna Sheludko

**she / her**

**Portfolio:** [anna1sheludko.github.io](https://anna1sheludko.github.io)

Data engineer. I move data from places where it's messy to places where it's useful.

Most of my job is convincing broken CSV files that they can, in fact, be parsed.
The rest is writing SQL that doesn't make the database cry.

Currently finishing my degree in databases and data processing — which means
I know the theory, and I'm now learning how much of it survives contact with production.

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

- **Languages & libraries:** Python (Pandas, psycopg2, SQLAlchemy), SQL, PL/SQL
- **Databases:** PostgreSQL, Oracle, MySQL
- **Data tools:** Excel (yes, Excel — it's not a crime), CSV, JSON
- **Infrastructure:** Docker, Git, GitHub Actions, YAML
- **Testing & validation:** pytest, Pandera

## Also know my way around

- Data modeling — normalization, star schema, indexes, and the eternal question
  of *"should this be a foreign key or should I just trust people?"*
- REST APIs and JSON, including the ones that return 200 with an error inside
- Airflow (basics)
- Linux command line — enough to be dangerous
- ETL principles: idempotency, retries, logging, and not deleting the production table by accident

## Projects

### [End-to-End ETL Pipeline with Python and PostgreSQL](https://github.com/anna1sheludko/end-to-end-pipeline)

A CSV → PostgreSQL pipeline for e-commerce data (~1.5M rows, 9 tables).
Extracts with retries, validates with Pandera, loads with `COPY` instead of `to_sql`
(because life is too short to wait for row-by-row inserts). Configured in YAML,
logged with rotation, tested with pytest, and runs in Docker.

**Stack:** `Python` `Pandas` `PostgreSQL` `Docker` `Pandera` `pytest` `GitHub Actions`

---

More projects coming — unless I get distracted refactoring this one.

## Contact

- **Email:** annasheludko152@gmail.com
- **GitHub:** [@anna1sheludko](https://github.com/anna1sheludko)

Have a project in mind? The email works.

<!--
**anna1sheludko/anna1sheludko** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
