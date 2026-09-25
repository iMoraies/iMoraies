# Hi, I'm Matheus Moraes 👋

### Software Engineering | Automation & AI | Technical Leadership

Software developer focused on **back-end engineering, business systems, process automation, AI-assisted solutions, and digital products**.

My work combines **software engineering, architecture, automation, UX/UI, observability, and business problem-solving**. I enjoy understanding real operational needs, translating them into technical solutions, and taking projects from requirements and architecture to implementation, deployment, validation, and continuous improvement.

I currently work with systems used in real business environments, developing applications, automating processes, supporting production solutions, and collaborating with technical and non-technical teams.

---

## About Me

- 🎓 Graduate in **Systems Analysis and Development**
- 💻 Working with **software development, automation, systems, and digital products**
- 🧠 Deepening my knowledge in **Software Architecture, AI, Observability, Security, and Technical Leadership**
- 🏗️ Building portfolio projects focused on real engineering problems
- 🤝 Experience collaborating with technical, operational, design, and business teams
- 📍 Rio de Janeiro, Brazil

---

## Tech Stack

### Core Technologies

<p align="left">
  <img src="https://skillicons.dev/icons?i=ts,nodejs,php,js,python,react,html,css,mysql,postgres" />
</p>

### Back-end & Architecture

<p align="left">
  <img src="https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/BullMQ-FF4F4F?style=for-the-badge" />
  <img src="https://img.shields.io/badge/REST_API-005571?style=for-the-badge" />
  <img src="https://img.shields.io/badge/OpenAPI-6BA539?style=for-the-badge&logo=openapiinitiative&logoColor=white" />
</p>

- Modular Monolith Architecture
- Multi-tenant Architecture
- Authentication & Authorization
- JWT + Refresh Token Rotation
- RBAC
- REST API Design
- Asynchronous Processing
- Workflow Engines
- Database Modeling
- API Integrations

### Infrastructure & Engineering

<p align="left">
  <img src="https://skillicons.dev/icons?i=docker,git,github,vscode" />
</p>

<p align="left">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/CI%2FCD-222222?style=for-the-badge" />
  <img src="https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white" />
  <img src="https://img.shields.io/badge/Observability-2F74C0?style=for-the-badge" />
</p>

- Docker & Docker Compose
- Automated Testing
- Structured Logging
- Metrics
- Health & Readiness Checks
- OpenTelemetry fundamentals
- GitHub Actions
- Architecture Decision Records
- Application Security

---

## What I Work With

### Software Engineering

I build and maintain applications, internal systems, APIs, dashboards, and digital products with focus on maintainability, reliability, and business value.

### Automation & AI

I develop solutions focused on reducing manual work, connecting systems, automating workflows, and applying AI in a controlled and useful way.

### Architecture & Reliability

I am deepening my work around architecture decisions, observability, incident management, security, testing, and operational reliability.

### Technical Leadership

My professional direction is focused on combining hands-on engineering with:

- Technical decision-making
- Requirements analysis
- Backlog prioritization
- Knowledge sharing
- Architecture discussions
- Stakeholder communication
- Continuous improvement
- Supporting less experienced professionals

---

# Featured Engineering Projects

## FlowPilot AI

### Workflow Automation Platform

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=000" />
</p>

A multi-tenant workflow automation platform designed to automate business processes through **asynchronous execution, conditional logic, integrations, task orchestration, and Artificial Intelligence**.

FlowPilot started as a back-end engineering project and evolved into a complete product with an operational web interface.

### Product Capabilities

- Workflow creation and management
- Conditional workflow execution
- AI-based classification
- Asynchronous job processing
- Task generation and management
- Execution tracking
- Audit logs
- Role-based access control
- Multi-tenant isolation
- System health monitoring
- Operational dashboard

### Engineering Highlights

- Modular Monolith Architecture
- Redis + BullMQ queue processing
- API and worker separation
- Idempotent workflow execution
- Workflow version snapshots
- JWT authentication with refresh token rotation
- RBAC and tenant isolation
- HTTP integration layer with SSRF protections
- AI provider abstraction
- Structured logging
- Metrics and health checks
- OpenTelemetry
- Automated tests
- CI pipeline
- ADR documentation

### Engineering Note

During real Docker runtime validation, the API and worker failed because the logging configuration attempted to load `pino-pretty`, which was available only as a development dependency.

The runtime configuration was corrected so:

- development uses human-readable logs;
- production uses structured JSON logs.

A regression test was added after the fix.

> **A successful build and passing tests do not replace real runtime validation.**

**Repository:**  
https://github.com/iMoraies/flowpilot-ai

---

## OpsBoard

### Incident Management & Reliability Platform

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=000" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
</p>

A platform focused on **incident management, service health, availability, MTTR, postmortems, auditability, and operational reliability**.

OpsBoard was built to explore how engineering teams can monitor services, respond to incidents, track reliability metrics, and document operational decisions.

### Product Capabilities

- Service management
- Service health tracking
- Incident creation and lifecycle
- Incident severity management
- Incident timeline
- Acknowledge / Investigate / Mitigate / Resolve flow
- Postmortems
- Audit logs
- Availability tracking
- MTTR calculation
- Role-based access control
- Multi-tenant isolation
- System health dashboard

### Engineering Highlights

- Modular Monolith Architecture
- Incident state machine
- Availability calculation
- MTTR calculation
- RBAC
- Tenant isolation
- JWT authentication
- Refresh token rotation
- Structured logging
- Prometheus-compatible metrics
- OpenTelemetry foundation
- Health & readiness checks
- Dockerized environment
- Automated testing
- CI pipeline
- Architecture Decision Records

### Architecture Decision

BullMQ was evaluated for asynchronous metrics recalculation, but was intentionally not added.

The current workload can be handled synchronously without introducing unnecessary queue complexity.

This decision was documented as a trade-off between:

**simplicity, operational cost, and future scalability.**

**Repository:**  
https://github.com/iMoraies/opsboard

---

# Current Engineering Focus

I'm currently deepening my knowledge and practice in:

- Software Architecture
- Back-end Architecture
- System Design
- Automated Testing
- CI/CD
- Observability
- Reliability Engineering
- Incident Management
- Application Security
- AI Agents
- AI-powered Automation
- Event-driven Architecture
- Cloud Architecture
- Technical Leadership

My goal is to evolve toward roles where I can combine:

**hands-on software engineering + architecture + automation + AI + reliability + business understanding + technical leadership**

---

## GitHub Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=iMoraies&show_icons=true&hide_border=true&theme=github_dark" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=iMoraies&layout=compact&hide_border=true&theme=github_dark" />
</p>

---

## Connect With Me

<p align="left">

<a href="https://www.linkedin.com/in/moraies/">
  <img src="https://img.shields.io/badge/LinkedIn-Matheus_Moraes-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<a href="https://github.com/iMoraies">
  <img src="https://img.shields.io/badge/GitHub-iMoraies-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

<a href="https://madebytheux.com">
  <img src="https://img.shields.io/badge/Portfolio-madebytheux.com-111111?style=for-the-badge&logo=googlechrome&logoColor=white" />
</a>

<a href="mailto:moraeesdeveloper@gmail.com">
  <img src="https://img.shields.io/badge/Email-moraeesdeveloper%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

</p>
