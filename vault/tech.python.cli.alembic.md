---
id: ulIDF3xiWsnEVBi52du6l
title: Alembic
desc: ""
updated: 1637606454944
created: 1637261207176
---

### Show history

`PYTHONPATH=. poetry run alembic history`

### New empty revision update

`PYTHONPATH=. alembic revision -m "Comment relevant to change"`

### New model or update via autogenerate

`PYTHONPATH=. alembic revision --autogenerate -m "Comment relevant to change"`
