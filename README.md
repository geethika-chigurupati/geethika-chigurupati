# Hi, I'm Geya Geethika Chigurupati 👋

Backend software engineer focused on Python, event-driven systems, and APIs that AI agents can use safely.
I have an M.S. in Computer Science from the University of Central Missouri.

## Projects

### [kafka-event-pipeline](https://github.com/geethika-chigurupati/kafka-event-pipeline)
An async Kafka pipeline that validates transaction events and writes them to PostgreSQL.
It uses idempotent inserts, retries with exponential backoff, and a dead-letter topic for bad messages.
Includes unit tests and CI.

### [payments-mcp-server](https://github.com/geethika-chigurupati/payments-mcp-server)
A mock payments MCP server built with FastMCP. Agents can create, look up, and refund payments,
with idempotency keys, strict decimal money handling, and JWT scope-based authorization.
Includes unit tests and CI.

## Tools I use in these projects

**Languages:** Python, SQL
**Backend and data:** Kafka (aiokafka), PostgreSQL (asyncpg), FastMCP, Pydantic
**Quality and delivery:** pytest, ruff, Docker Compose, GitHub Actions
