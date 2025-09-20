# Incident-Ticket-Managment
Java + MySQL ticketing tool to log, prioritize, assign, and close incidents with SLA monitoring and simple reports (MTTR, backlog).

## Features
- Ticket CRUD, priority queues, status workflow
- SLA hour tracking; breach flag
- Reports: MTTR, open vs closed, backlog ageing

## Setup
1) DB:
```bash
mysql -u root -p < sql/schema.sql
