---
name: project-specification
description: Maintain a single, authoritative SPEC.md that captures the complete, current state of a project containing all mandatory sections 1 to 12 (Overview, Requirements, User Experience, Architecture, Technology Stack, Backend, Frontend, Data Model, API, Configuration, Testing, Deployment) so another coding agent can recreate the project from scratch without the original conversation. Defines what a project specification is and how to write it. Use when the user asks to create, update, or review SPEC.md, or when bootstrapping a new project from an existing SPEC.md.
---


### Required Content

Every created or updated `SPEC.md` must strictly contain **all sections 1 to 12**. No section from 1 to 12 may be omitted:

```markdown
# Project Specification

## 1. Overview
What the application does and its main goal.

## 2. Requirements
Complete functional requirements.

## 3. User Experience
UI, workflows, user interactions, and behavior.

## 4. Architecture
System architecture and major components.

## 5. Technology Stack
Languages, frameworks, libraries, databases, infrastructure, and tools.

## 6. Backend
Backend structure, services, APIs, business logic, and integrations.

## 7. Frontend
Pages, components, state management, styling, and client-side behavior.

## 8. Data Model
Entities, schemas, relationships, indexes, and persistence.

## 9. API
Endpoints, request/response formats, authentication, and errors.

## 10. Configuration
Environment variables, configuration files, secrets, and external dependencies.

## 11. Testing
Required tests and testing strategy.

## 12. Deployment
Build, deployment, infrastructure, and runtime requirements.
```