# Hi, I'm Matheus Moraes 👋

Software developer focused on **back-end engineering, business systems, process automation, AI-assisted solutions, and scalable web applications**.

My work combines **software engineering, automation, architecture, AI-assisted development, UX/UI, and business problem-solving**. I enjoy understanding real operational needs, translating them into technical solutions, and taking projects from requirements and architecture to implementation, deployment, maintenance, and continuous improvement.

I currently work with systems used in real business environments, developing applications, automating processes, supporting production solutions, and collaborating with technical and non-technical teams.

---

## What I Work With

### Software Engineering & Full-Stack Development

I build and maintain web applications, internal systems, ecommerce platforms, APIs, dashboards, and digital products using technologies such as:

- Node.js
- TypeScript
- PHP
- JavaScript
- Python
- PostgreSQL
- MySQL
- HTML & CSS
- Fastify
- CodeIgniter 4
- Prisma ORM
- REST APIs
- MVC Architecture
- Authentication and authorization
- Database modeling
- Production deployment and maintenance

### Automation & Process Improvement

I develop solutions focused on reducing manual work, improving operational efficiency, and connecting systems and business processes.

My work includes:

- Business process automation
- Workflow automation
- Internal tools
- Data processing
- System integrations
- Automation scripts
- Digital customer journeys
- Asynchronous processing
- Queue-based execution

### AI-Assisted Development

I use Artificial Intelligence as part of my engineering workflow to improve productivity, technical analysis, automation, and solution design while maintaining responsibility for understanding, reviewing, testing, and validating generated solutions.

Areas of application include:

- Code analysis and review
- Debugging
- Solution design
- Automation
- Technical research
- Documentation
- Refactoring
- AI-assisted workflows
- Structured classification and decision flows

I am currently deepening my knowledge in **AI agents, AI integrations, and intelligent automation**.

### Technical Leadership & Collaboration

Throughout my professional experience, I have worked across technology, operations, design, and business teams.

I have experience with:

- Requirements gathering
- Technical problem solving
- Project organization
- Prioritization of demands
- Backlog organization
- Knowledge sharing
- Supporting and guiding less experienced team members
- Communication with technical and non-technical stakeholders
- Continuous improvement of systems and processes
- Translating business needs into technical solutions

My current career direction is focused on expanding these skills toward **software architecture and technical leadership**.

---

## Tech Stack

### Languages & Core Technologies

<p align="left">
  <img src="https://skillicons.dev/icons?i=ts,nodejs,php,js,python,html,css,mysql,postgres" />
</p>

### Back-end & Architecture

- Fastify
- CodeIgniter 4
- Prisma ORM
- PostgreSQL
- MySQL
- Redis
- BullMQ
- REST APIs
- OpenAPI / Swagger
- JWT Authentication
- RBAC
- Multi-tenant Architecture
- MVC Architecture
- Database Modeling
- Asynchronous Processing
- Workflow Engines

### Infrastructure & Engineering

<p align="left">
  <img src="https://skillicons.dev/icons?i=docker,git,github,vscode" />
</p>

- Docker
- Docker Compose
- GitHub Actions
- CI/CD fundamentals
- Structured Logging
- Health & Readiness Checks
- Metrics
- OpenTelemetry fundamentals
- Automated Testing
- Architecture Decision Records

### Currently Deepening

- Software Architecture
- Back-end Architecture
- Automated Testing
- CI/CD
- Observability
- OpenTelemetry
- Application Security / OWASP
- AI Agents
- Event-driven Architecture
- Cloud Architecture
- Technical Leadership

---

# Featured Projects

## FlowPilot AI

A multi-tenant workflow automation platform designed to automate business processes using asynchronous execution, integrations, artificial intelligence, and conditional workflows.

The project was built as a back-end engineering case study focused on architecture, reliability, security, observability, and technical decision-making.

### Engineering Focus

- Modular Monolith Architecture
- Multi-tenancy
- REST API Design
- Asynchronous Processing
- Workflow Engine
- Conditional Branching
- Idempotency
- Queue Processing
- Authentication & RBAC
- AI Provider Abstraction
- HTTP Integrations
- Observability
- Application Security
- Automated Testing
- CI Pipeline
- Architecture Decision Records

### Tech Stack

Node.js, TypeScript, Fastify, PostgreSQL, Prisma, Redis, BullMQ, Docker, Vitest, OpenAPI and OpenTelemetry.

### Architecture Highlights

- API and worker separated by asynchronous queue processing
- PostgreSQL as the system of record
- Redis + BullMQ for background execution
- Workflow version snapshots
- Idempotent workflow execution
- JWT authentication with refresh token rotation
- Organization-level tenant isolation
- Safe HTTP integration layer with SSRF protections
- Mockable AI provider architecture
- Structured logging and request correlation
- Metrics, health and readiness endpoints
- Architecture decisions documented through ADRs

### Engineering Notes

During real Docker validation, a runtime logging issue was discovered where the production container attempted to load the development-only `pino-pretty` transport.

The logging architecture was corrected so development uses human-readable logs while production uses structured JSON logging.

A regression test was added and the fix was committed as:

`fix(logging): avoid pino-pretty dependency in production runtime`

**Repository:**  
https://github.com/iMoraies/flowpilot-ai

---

## 3D Line Ecommerce Platform

Full ecommerce platform designed for a personalized 3D printing business.

The project was structured as a real business application, covering customer experience, administration, product management, checkout, customization, and future integrations.

### Engineering Focus

- Full-Stack Development
- MVC Architecture
- Database Modeling
- Ecommerce Flows
- Authentication
- Administrative Tools
- Product Customization
- Business Rules
- Integration-ready Architecture

### Tech Stack

PHP 8+, CodeIgniter 4, MySQL, HTML, CSS, JavaScript, MVC.

### Main Features

- Product catalog and product detail pages
- Product variations and dynamic pricing
- Shopping cart and checkout
- Customer registration and account area
- Administrative dashboard
- Custom project request workflow
- Product reviews with image uploads
- Content/blog management
- WhatsApp customer relationship flow
- Architecture prepared for payment gateway integration
- Architecture prepared for freight service integration

**Repository:**  
https://github.com/iMoraies/3D-Line-E-Commerce-Project

---

## Smart Appointment Manager CLI

Python application that models the business logic of an appointment management system.

### Engineering Focus

- Business Rules
- Data Structures
- Application Flow
- Python Fundamentals
- CLI Architecture

### Tech Stack

Python 3

**Repository:**  
https://github.com/iMoraies/smart-appointment-manager

---

## Appointment Booking App

Web application for appointment scheduling and local data persistence.

### Engineering Focus

- Application State
- Business Logic
- Client-side Persistence
- User Flow
- Clean Code Organization

### Tech Stack

HTML5, CSS3, Vanilla JavaScript ES6

**Repository:**  
https://github.com/iMoraies/appointment-bookin-app

---

# Current Engineering Focus

I'm currently deepening my knowledge in:

- Software Architecture
- Back-end Architecture
- Node.js & TypeScript
- Docker
- Automated Testing
- CI/CD
- Observability
- Application Security
- AI Agents
- AI-powered Automation
- Event-driven Architecture
- Technical Leadership

My goal is to evolve toward roles where I can combine **hands-on software engineering, architecture, automation, AI, business understanding, and technical leadership**.

---

## Let's Connect

**Portfolio:**  
https://madebytheux.com

**LinkedIn:**  
https://www.linkedin.com/in/matheus-moraes-26a32622b/

**Email:**  
moraeesdeveloper@gmail.com

**GitHub:**  
https://github.com/iMoraies
