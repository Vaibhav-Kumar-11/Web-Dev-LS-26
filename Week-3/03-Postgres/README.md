# PostgreSQL

[Home](../../README.md) > [Week 3](../README.md) > PostgreSQL

> Week 3 · Topic 3 of 6 · Prerequisites: [Django Basics](../02-Django/README.md)

---

## Why This Topic

You just built models, ran migrations, and saw data in the Django admin — all running on SQLite. That's great for learning, but SQLite handles only one write at a time, has no real permission system, and is not what any serious production app runs on. This topic has two jobs:

## What You Will Learn

- **Relational vs Non-Relational Databases** — why we're choosing a relational model at all
- **Raw SQL Basics** — enough `psql` to understand what the ORM is abstracting away
- **The ORM as a Translator** — `Model = Table`, `Field = Column`, `Instance = Row`
- **Migrations, Properly Understood** — versioned, Git-like history for your database schema
- **Connecting Django to Postgres** — `psycopg2`, environment variables, never hardcoding credentials

---

## Resources

**Watch (conceptual hook — start here):**
- [7 Database Paradigms](https://www.youtube.com/watch?v=W2Z7fbCLSTw) — Covers relational, document, key-value, and graph databases in 10 minutes. You'll leave understanding *why relational databases exist*.

**Watch (the ORM, specifically):**
- [CS50W Lecture 4 — SQL, Models and Migrations](https://www.youtube.com/watch?v=YzP164YANAU) — Covers SQL fundamentals → Django models → migrations in a single lecture. This is the single best resource for this entire topic.

**Watch (Postgres hands-on):**
- [PostgreSQL Tutorial for Beginners](https://www.youtube.com/watch?v=SpfIwlAYaKk) — Covers installation, the `psql` CLI, tables, CRUD, joins, and constraints. Watch this and you will have a good understanding of SQL.

**Read:**
- [What is an ORM? — freeCodeCamp](https://www.freecodecamp.org/news/what-is-an-orm-the-meaning-of-object-relational-mapping-database-tools/) — The best beginner ORM explainer, with a raw-SQL-vs-ORM comparison.
- [Django Migrations — Official Docs](https://docs.djangoproject.com/en/5.0/topics/migrations/) — The official explanation of how migrations work.
- [PostgreSQL Tutorial — postgresqltutorial.com (via Neon)](https://neon.com/postgresql/tutorial) — The best written Postgres reference on the internet.

**Watch (connecting Django to Postgres):**
- [Django with PostgreSQL](https://www.youtube.com/watch?v=HEV1PWycOuQ) — The most current connection tutorial available through the railway app.

---

[Previous: Django Basics](../02-Django/README.md) | [Week 3 Overview](../README.md) | [Next: Django REST Framework](../04-REST-APIs/README.md)
