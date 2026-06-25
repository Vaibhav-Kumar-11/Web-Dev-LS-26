# Django REST Framework — Turning Django Into a JSON API

[Home](../../README.md) > [Week 3](../README.md) > Django REST Framework

> Week 3 · Topic 4 of 6 · Prerequisites: [PostgreSQL](../03-Postgres/README.md), [React](../../Week-2/01-React/README.md)

---

## Why This Topic

Here's the pivot point of the entire week. Until now, when a Django View rendered a page, it rendered a Django **Template** — server-generated HTML. That worked fine when Django was the only thing in the picture. But your frontend is **React**, and React can't read a Django template — React renders its own HTML in the browser and only wants raw JSON data.
If you have seen the Django tutorial videos and have completed the REST API part in them you can skip this tutorial.

---

## Learning Path for This Topic

```
1. What is an API?
        |
        v
2. What is REST? (GET /posts = list, POST /posts = create, GET /posts/5 = get one, etc.)
        |
        v
3. What is serialization? (Python objects can't travel over HTTP — they must become JSON first)
        |
        v
4. Why DRF over manual JsonResponse views? (see the boilerplate DRF erases)
        |
        v
5. Hands-on: serializers -> ModelSerializer -> ViewSets -> Routers -> test in the Browsable API
```

---

## Resources

**Watch first (conceptual):**
- [RESTful APIs in 100 Seconds](https://www.youtube.com/watch?v=-MTSQjw5DrM) — The sharpest possible introduction to what an API is and what REST means

**Watch (main DRF course):**
- [Django REST Framework](https://www.youtube.com/watch?v=cJveiktaOSQ) — This should be more than enough to understand DRF **Start here.**
- [Django REST Framework Full Course](https://www.youtube.com/watch?v=4hrtQmFLTY0) — Goes deeper than the crash course above (you can see this if you have the time)

**Read:**
- [DRF Official Tutorial — Quickstart](https://www.django-rest-framework.org/tutorial/quickstart/) — The quickstart is 10 minutes and builds a working API

---


[Previous: PostgreSQL](../03-Postgres/README.md) | [Week 3 Overview](../README.md) | [Next: Auth — JWT & OAuth](../05-Auth/README.md)
