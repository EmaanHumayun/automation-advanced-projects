# Project Index — Level 3: Advanced

Detailed technical briefs for all projects in this tier.


---

### Project 11: Custom Integration Platform
- **Directory**: [`11-custom-integration-platform`](./11-custom-integration-platform)
- **Status**: `Planned`
- **Core Technology**: TypeScript, Node.js, Plugin Architecture, AES-256, SQLite/PostgreSQL
- **Summary**: Pluggable integration runtime engine with standardized connector interfaces, AES-256 encrypted credential vault, and execution telemetry.
- **Problem Solved**: Engineering teams lack an extensible, secure internal integration harness to register and execute custom third-party integrations cleanly.
- **Key Concepts**: Plugin architecture, interface segregation, symmetric credential encryption, standardized context passing, execution metrics.


---

### Project 12: Advanced Workflow Orchestration Engine
- **Directory**: [`12-advanced-workflow-orchestration-engine`](./12-advanced-workflow-orchestration-engine)
- **Status**: `Planned`
- **Core Technology**: TypeScript, Node.js, PostgreSQL, State Machine, Docker
- **Summary**: Directed Acyclic Graph (DAG) workflow engine supporting concurrent branches, dependency resolution, retries, and rollback compensation.
- **Problem Solved**: Linear script automation breaks down when business logic requires complex branch decisions, parallel tasks, and transactional rollbacks.
- **Key Concepts**: Topological sort, DAG cycle detection, persistent state machines, step retry policies, compensating transaction rollbacks.


---

### Project 13: Event-Driven Automation Platform
- **Directory**: [`13-event-driven-automation-platform`](./13-event-driven-automation-platform)
- **Status**: `Planned`
- **Core Technology**: Node.js/Go, RabbitMQ, AMQP 0-9-1, Docker, Prometheus
- **Summary**: High-throughput event bus decoupling ingestion from worker execution using RabbitMQ, topic exchanges, and dead-letter queues.
- **Problem Solved**: Direct webhook calls fail under sudden load spikes, overwhelming downstream internal APIs and causing catastrophic cascading failures.
- **Key Concepts**: AMQP topic routing keys, producer-consumer decoupling, prefetch limits, message acknowledgments (ACK/NACK), dead-lettering.


---

### Project 14: Data Synchronization and ETL Pipeline
- **Directory**: [`14-data-synchronization-and-etl-pipeline`](./14-data-synchronization-and-etl-pipeline)
- **Status**: `Planned`
- **Core Technology**: Python, SQLAlchemy, PostgreSQL, Redis, Pandas
- **Summary**: High-volume batch and streaming ETL pipeline extracting relational data, transforming schemas, and loading into an analytical warehouse.
- **Problem Solved**: Analytical reporting queries lock operational transaction tables, degrading customer-facing database performance.
- **Key Concepts**: High-watermark incremental sync, batch chunking, data schema validation, bulk upsert operations, pipeline failure alerting.


---

### Project 15: AI-Powered Business Automation System
- **Directory**: [`15-ai-powered-business-automation-system`](./15-ai-powered-business-automation-system)
- **Status**: `Planned`
- **Core Technology**: Python, OpenAI/Gemini API, Instructor/Pydantic, FastAPI, Docker
- **Summary**: Intelligent document extraction and routing pipeline utilizing LLM APIs with strict schema validation to parse invoices and customer emails.
- **Problem Solved**: Semi-structured invoices, contracts, and unstructured customer emails require expensive human hours to manually transcribe into ERP systems.
- **Key Concepts**: LLM structured output enforcement, prompt engineering, schema validation, confidence scoring, human-in-the-loop review queues.
