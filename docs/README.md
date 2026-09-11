# OctoAcme Project Management Docs

## Welcome

Welcome to the OctoAcme Project Management documentation hub. This repository contains comprehensive guides for managing projects across all phases of delivery—from initial ideation through retrospectives and continuous improvement.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle Overview

OctoAcme projects follow a structured lifecycle with five key phases:

1. **[Initiation](octoacme-project-initiation.md)** — Validate business need, align stakeholders, and create a lightweight plan with success metrics and resource needs
2. **[Planning](octoacme-project-planning.md)** — Break work into shippable increments, identify dependencies and risks, and establish the Definition of Done
3. **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day progress through daily standups, quality gates, and milestone tracking
4. **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardize the release process with pre-release checks, deployment procedures, and rollback plans
5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into measurable improvements

## OctoAcme Process Summary

OctoAcme follows a **structured, lifecycle-based approach** to project management that emphasizes customer value, iterative delivery, and clear ownership. The process begins with **Initiation**, where teams validate business needs and create a lightweight Project One-pager defining the problem, goal, and success metrics, with stakeholder alignment serving as the gate for moving forward. Once approved, **Planning** breaks work into shippable increments with prioritized backlogs, dependency mapping, and a clear Definition of Done.

**Execution and delivery** are driven by a disciplined team rhythm and quality-first mindset. Daily 15-minute standups focus on progress and blockers, while weekly delivery syncs track velocity and flag risks. Teams work in small, reviewable pull requests (≤400 lines), maintain comprehensive test coverage, run automated CI/CD checks, and conduct manual QA for feature acceptance. A GitHub Projects board organizes work through columns (Backlog, Ready, In Progress, In Review, QA, Done), providing transparency and enabling rapid feedback loops. Quality assurance is embedded throughout rather than deferred, with security scanning, smoke tests, and acceptance criteria validation built into the workflow.

**Risk management and communication** are central to keeping projects on track. OctoAcme maintains a formal Risk Register tracking impact, likelihood, owners, and mitigation strategies, reviewed weekly during syncs. Escalation follows a clear hierarchy (team → PM → Product Lead → Sponsor), ensuring blockers surface quickly. Stakeholders receive regular updates using consistent templates covering progress, next steps, risks, and decisions needed. Clear role definitions eliminate ambiguity: Product Managers own what is built and measure outcomes, Project Managers coordinate delivery and manage timelines, and Developers implement and validate quality.

**Release, continuous improvement, and institutional learning** complete the cycle. Before production deployment, teams verify that acceptance criteria are met, CI passes, security scans are clean, and rollback plans are documented. Post-release, structured retrospectives (45–75 minutes, focused on 2–3 action items) capture learnings and convert them into measurable improvements tracked in future backlogs. This emphasis on feedback loops, data-driven decisions, and iterative refinement creates a culture where teams learn from each project and systematically improve both process and product quality.

## Process Documents

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme approach, roles, and key artifacts
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate and authorize new work with stakeholder alignment
- **[Project Planning](octoacme-project-planning.md)** — Turn approved initiatives into actionable backlog and release plans
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day execution, stand-ups, quality gates, and reporting metrics
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, track, and communicate risks, dependencies, and stakeholder updates
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Release types, pre-release checks, deployment procedures, and rollback strategies
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Run retrospectives, track action items, and measure improvements
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Role definitions and responsibilities for Developers, Product Managers, and Project Managers

## Quick Start by Role

### New Project Manager?
Start with [Project Management Overview](octoacme-project-management-overview.md) to understand the framework, then dive into [Initiation](octoacme-project-initiation.md) and [Planning](octoacme-project-planning.md) for hands-on guidance.

### Product Manager?
Review [Project Management Overview](octoacme-project-management-overview.md) and [Roles & Personas](octoacme-roles-and-personas.md) to understand your responsibilities and how you fit into the delivery lifecycle.

### Developer?
See [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day workflows and [Roles & Personas](octoacme-roles-and-personas.md) to understand team expectations and quality standards.

### New to OctoAcme?
Start here with [Project Management Overview](octoacme-project-management-overview.md), then follow the Project Lifecycle Overview above to understand each phase.

## How to Use These Docs

- **Start a new project?** Use [Initiation](octoacme-project-initiation.md) to validate business need and create your One-pager
- **Need to plan delivery?** Follow [Planning](octoacme-project-planning.md) to create your backlog and release plan
- **Managing day-to-day work?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for team rhythm and quality gates
- **Ready to release?** Check [Release & Deployment](octoacme-release-and-deployment.md) for pre-release checklist and procedures
- **Project complete?** Run a [Retrospective](octoacme-retrospective-and-continuous-improvement.md) to capture learnings
- **Identifying or managing risks?** Use [Risk Management & Communication](octoacme-risks-and-communication.md) to track and escalate

## Contributing to Process Docs

Have ideas to improve these processes? Use the [Process Doc Update template](./../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose changes, new content, or clarifications.

---

**Last Updated:** September 2026  
**Maintained by:** OctoAcme Project Management Team
