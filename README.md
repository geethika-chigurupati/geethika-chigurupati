# Hi, I'm Geya Geethika Chigurupati 👋

Backend software engineer focused on Python, event-driven systems, and APIs with real access control.
I have an M.S. in Computer Science from the University of Central Missouri.

## Projects

### [kafka-event-pipeline](https://github.com/geethika-chigurupati/kafka-event-pipeline)
An async Kafka pipeline that validates transaction events and writes them to PostgreSQL, with idempotent
inserts, retries with exponential backoff, and a dead-letter topic for bad messages.

### [payments-mcp-server](https://github.com/geethika-chigurupati/payments-mcp-server)
A mock payments MCP server built with FastMCP. Agents can create, look up, and refund payments, with
idempotency keys, strict decimal money handling, and JWT scope-based authorization.

### [inventory-api](https://github.com/geethika-chigurupati/inventory-api)
A FastAPI inventory service with JWT login, viewer/staff/admin roles, PostgreSQL storage, and a Redis cache
that keeps working if Redis goes down. Stock changes are atomic, and a concurrency test checks that stock
is never oversold.

All three include unit tests and CI on GitHub Actions.

## Tools I use in these projects

**Languages:** Python, SQL
**Backend and data:** FastAPI, SQLAlchemy, PostgreSQL, Redis, Kafka (aiokafka), FastMCP, Pydantic
**Quality and delivery:** pytest, ruff, Docker Compose, GitHub Actions
