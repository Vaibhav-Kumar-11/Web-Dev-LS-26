# Django Basics

[Home](../../README.md) > [Week 3](../README.md) > Django Basics

> Week 3 · Topic 2 of 6 · Prerequisites: [Backend Foundations](../01-Backend-Foundations/README.md), [Python for Web Dev](../../Week-1/04-Python-Web-Dev/README.md)

---

## What You Will Learn

- **What a Web Framework Actually Solves** — the raw-Python-vs-framework gap
- **Django vs Flask vs FastAPI**
- **MTV Architecture (Model-Template-View)** — Django's version of the request/response loop from Topic 1
- **URLs, Views, and Templates** — routing a request to the code that handles it
- **Models & Migrations** — defining your data shape in Python, letting Django generate the database structure
- **The Django Admin Panel** — a free, auto-generated interface to manage your data

---

## Learning Path for This Topic

```
1. What problem does a framework solve? (raw Python vs Django, side by side)
        |
        v
2. Why Django over Flask/FastAPI? (batteries-included vs DIY vs API-first)
        |
        v
3. The request lifecycle: Browser -> URL dispatcher -> View -> Model (DB) -> Template -> Response
        |
        v
4. Hands-on: project setup, first app, first model, first migration, admin panel
```

## Resources
- [Flask vs Django vs FastAPI](https://www.youtube.com/watch?v=nnyVoqfcAl8) — Covers the philosophy and tradeoffs of all three.

**Watch (main course — pick one as your primary, use the others as reference):**
- [Python Django Full Course for Beginners](https://www.youtube.com/watch?v=Rp5vd34d-z4) — The best single-video Django starter. Covers MTV, models, migrations, admin, and forms in one sitting. **Start here.**
- [Python Django 7-Hour Course](https://www.youtube.com/watch?v=PtQiiknWUcI) — The most-watched Django beginner project course on YouTube. Explicitly opens with "what problem does Django solve?" before touching code. Builds a real app from scratch. - **For hands on project practice**
- [Django Tutorials Playlist (16 videos)](https://www.youtube.com/playlist?list=PL-osiE80TeTtoQCKZ03TU5fNfx2UY6U4p) — The gold-standard per-topic reference when you get stuck on something specific. This covers almost all the topics related to Django. If you have the time to complete all the 16 videos this is the **best** one

**Read (For those who prefer reading over watching videos):**
- [Django Official Tutorial — Parts 1–4](https://docs.djangoproject.com/en/5.0/intro/tutorial01/) — Covers project setup, models, views, and the admin panel and always contains the latest updates
- [Django Web Framework Tutorial Series](https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Server-side/Django) — Good for students who learn better by reading than watching.

---

[Previous: Backend Foundations](../01-Backend-Foundations/README.md) | [Week 3 Overview](../README.md) | [Next: PostgreSQL](../03-Postgres/README.md)
