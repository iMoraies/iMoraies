# Hi, I'm Matheus Moraes 👋

Software developer focused on **back-end engineering, business systems, process automation, AI-assisted solutions, and digital products**.

My work combines **software engineering, automation, architecture, UX/UI, and business problem-solving**. I enjoy understanding real operational needs, translating them into technical solutions, and taking projects from requirements and architecture to implementation, deployment, validation, and continuous improvement.

I currently work with systems used in real business environments, developing applications, automating processes, supporting production solutions, and collaborating with technical and non-technical teams.

---

## What I Work With

### Software Engineering & Full-Stack Development

I build and maintain web applications, internal systems, APIs, ecommerce platforms, dashboards, and digital products.

My current stack and project experience includes:

- Node.js
- TypeScript
- PHP
- JavaScript
- Python
- React
- PostgreSQL
- MySQL
- HTML & CSS
- Fastify
- CodeIgniter 4
- Prisma ORM
- REST APIs
- Authentication & Authorization
- Database Modeling
- Production Deployment & Maintenance

### Automation & Process Improvement

I develop solutions focused on reducing manual work, improving operational efficiency, and connecting business processes with technology.

My work and projects include:

- Business Process Automation
- Workflow Automation
- Internal Tools
- System Integrations
- Automation Scripts
- Digital Customer Journeys
- Asynchronous Processing
- Queue-based Execution
- Conditional Workflows

### AI-Assisted Development

I use Artificial Intelligence as part of my engineering workflow while maintaining responsibility for understanding, reviewing, testing, and validating the solutions produced.

I use AI for:

- Code Analysis & Review
- Debugging
- Solution Design
- Automation
- Technical Research
- Documentation
- Refactoring
- Intelligent Workflows
- Structured Classification

I'm currently deepening my knowledge in **AI integrations, AI agents, and intelligent automation**.

### Technical Leadership & Collaboration

Throughout my professional experience, I have worked across technology, operations, design, and business teams.

My experience includes:

- Requirements Gathering
- Technical Problem Solving
- Project Organization
- Backlog & Demand Prioritization
- Technical Decision-making
- Knowledge Sharing
- Supporting Less Experienced Team Members
- Communication with Technical and Non-technical Stakeholders
- Continuous Improvement
- Translating Business Needs into Technical Solutions

My current career direction is focused on expanding these skills toward **software architecture and technical leadership**.

---

## Tech Stack

### Languages & Core Technologies

<p align="left">
  <img src="https://skillicons.dev/icons?i=ts,nodejs,php,js,python,react,html,css,mysql,postgres" />
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
- Modular Monolith Architecture
- MVC Architecture
- Asynchronous Processing
- Workflow Engines

### Front-end

- React
- TypeScript
- Vite
- Responsive Interfaces
- API Integration
- Authentication Flows
- Operational Dashboards

### Infrastructure & Engineering

<p align="left">
  <img src="https://skillicons.dev/icons?i=docker,git,github,vscode" />
</p>

- Docker
- Docker Compose
- GitHub Actions
- CI/CD Fundamentals
- Automated Testing
- Structured Logging
- Health & Readiness Checks
- Metrics
- OpenTelemetry Fundamentals
- Architecture Decision Records

### Currently Deepening

- Software Architecture
- Back-end Architecture
- Automated Testing
- CI/CD
- Observability
- Application Security / OWASP
- AI Agents
- Event-driven Architecture
- Cloud Architecture
- Technical Leadership

---

# Featured Projects

## FlowPilot AI

A multi-tenant workflow automation platform built to automate business processes through **workflows, asynchronous processing, conditional logic, integrations, and Artificial Intelligence**.

FlowPilot started as a back-end engineering project and evolved into a complete demonstrable product with an operational web interface for managing workflows, executions, tasks, audit logs, and system health.

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

**Back-end:**  
Node.js, TypeScript, Fastify, PostgreSQL, Prisma, Redis and BullMQ.

**Web Interface:**  
React, TypeScript and Vite.

**Engineering:**  
Docker, Vitest, OpenAPI, OpenTelemetry and GitHub Actions.

### Architecture Highlights

- API and worker separated through asynchronous queue processing
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

### Web Operations Console

The project also includes a web interface designed to make the workflow engine easier to operate and understand.

The interface provides:

- Dashboard with operational information
- Workflow visualization and management
- Workflow execution
- Execution timeline and step results
- Task management
- Audit logs
- System health information
- Authentication and protected routes

### Engineering Notes

During the first complete Docker runtime validation, the API and worker failed because the logging configuration attempted to load `pino-pretty`, which was available only as a development dependency.

The logging configuration was corrected so:

- development uses human-readable logs;
- production uses structured JSON logs.

A regression test was also added.

This reinforced an important engineering lesson:

**A successful build and passing tests do not replace real runtime validation.**

**Repository:**  
https://github.com/iMoraies/flowpilot-ai

---

## 3D Line Ecommerce Platform

Full ecommerce platform designed for a personalized 3D printing business.

The project was structured as a real business application covering customer experience, administration, product management, checkout, customization, and future integrations.

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

PHP 8+, CodeIgniter 4, MySQL, HTML, CSS and JavaScript.

### Main Features

- Product catalog and detail pages
- Product variations and dynamic pricing
- Shopping cart and checkout
- Customer registration and account area
- Administrative dashboard
- Custom project request workflow
- Product reviews with image uploads
- Content and blog management
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

HTML5, CSS3 and Vanilla JavaScript ES6.

**Repository:**  
https://github.com/iMoraies/appointment-bookin-app

---

# Current Engineering Focus

I'm currently deepening my knowledge in:

- Software Architecture
- Back-end Architecture
- Node.js & TypeScript
- Automated Testing
- CI/CD
- Observability
- Application Security
- AI Agents
- AI-powered Automation
- Event-driven Architecture
- Cloud Architecture
- Technical Leadership

My goal is to evolve toward roles where I can combine **hands-on software engineering, architecture, automation, AI, business understanding, and technical leadership**.

---

## Let's Connect

**Portfolio:**  
https://madebytheux.com

**LinkedIn:**  
https://www.linkedin.com/in/moraies/

**Email:**  
moraeesdeveloper@gmail.com

**GitHub:**  
https://github.com/iMoraies
