# Amit Prakash

Senior Backend Engineer focused on **distributed systems, data pipelines, and database-heavy platforms**.

I enjoy building systems that move and process data reliably at scale. Most of my work lives close to the **data layer — databases, event streams, and backend services**.

Currently exploring deeper work in **system architecture, streaming platforms, and developer tooling powered by AI.**

---

## Engineering Philosophy

Good systems are:

- **Simple before clever**
- **Observable before scalable**
- **Reliable before fast**

I believe strong backend systems come from understanding **data flow, failure modes, and operational behavior**, not just writing services.

The problems I enjoy most involve:

- moving large volumes of data  
- designing event-driven architectures  
- building reliable backend services  
- exploring database internals  

---

## What I Work On

My work generally sits around **backend platforms and data movement systems**.

Typical architecture problems I work on include:

- **Event-driven microservices**
- **Change Data Capture pipelines**
- **Streaming data systems**
- **Backend service design**
- **Database performance tuning**

---

## Current Projects

### Text-to-SQL Engine

Natural language interface for relational databases.

**Goal**

Allow users to ask questions in plain English and automatically generate safe SQL queries.

**Stack**

- .NET
- PostgreSQL
- SQLCoder (self-hosted LLM)
- Prompt engineering
- Query validation layer

**Focus areas**

- schema reasoning
- query safety
- AI-assisted developer tooling

---

### Change Data Capture Streaming Platform

Real-time data pipeline for propagating database changes across services.

**Architecture**

```
SQL Server
   │
   │  CDC
   ▼
Debezium / Kafka
   │
   ▼
Streaming consumers (.NET)
   │
   ▼
CosmosDB / downstream services
```

**Engineering challenges**

- idempotent event processing
- schema evolution
- exactly-once semantics
- high throughput ingestion

---

### Anonymous Feedback Platform

Backend infrastructure for collecting anonymous feedback safely.

**Goals**

- protect user anonymity
- prevent abuse
- design scalable backend APIs

**Stack**

- .NET backend
- cloud storage
- secure submission pipeline

---

## Technology Stack

### Languages

- C#
- SQL
- JavaScript

### Backend

- .NET
- ASP.NET Core
- Background workers
- Dependency Injection

### Databases

- SQL Server
- PostgreSQL
- DynamoDB
- Cosmos DB

### Streaming

- Kafka
- RabbitMQ
- Debezium
- SQL Server CDC

### Cloud / Infrastructure

- AWS
- Docker

---

## Areas I Like Exploring

- distributed systems design
- database internals
- streaming architectures
- backend reliability
- data consistency models
- developer tooling

---

## Writing

Occasionally writing about:

- backend engineering
- database architecture
- system design
- engineering deep dives

---

## Current Direction

Long-term I want to focus on **architecture-level backend systems**, designing platforms that power **data-intensive applications**.

Particularly interested in solving engineering problems in:

- fintech
- aerospace
- large-scale product platforms

---

## Fun Engineering Question

A problem I often think about:

> What is the simplest architecture that can reliably move data between systems without losing consistency?

---

## Connect

If you enjoy discussing **backend architecture, databases, or distributed systems**, feel free to connect.

---

## Engineering Motto

> “Data is the system. Everything else is just transport.”
