# OctoAcme Project Management Docs

## Overview

This repository contains process documentation for the OctoAcme approach to project management. OctoAcme operates a structured yet iterative framework centered on five core principles: customer-first delivery, incremental development, clear ownership, data-informed decisions, and psychological safety.

## Project Management Process Summary

OctoAcme employs a five-stage project lifecycle that spans from initiation through planning, execution, release, and retrospective closure. The organization defines distinct roles with clear responsibilities—including Project Managers (coordination and delivery), Product Managers (defining scope and measuring outcomes), Developers (implementation and quality), and QA/Testing (validation and acceptance)—to drive accountability and efficiency.

**Execution and Quality** are managed through a disciplined day-to-day rhythm supported by structured workflows, a pull request process favoring small reviewable changes (≤400 lines), and a multi-layered testing strategy that includes unit tests, integration tests, end-to-end smoke tests, and security scanning within CI pipelines. Progress tracking leverages velocity metrics, burndown reporting, and success dashboards.

**Communication and Risk Management** are woven throughout the project lifecycle via regular syncs (weekly PM-PdM alignment, twice-weekly delivery standups, monthly stakeholder updates), a risk register that tracks identification through monitoring, and standardized status update templates. Escalation paths flow from team to PM to Product Lead to Sponsor, ensuring rapid issue resolution and organizational transparency.

**Continuous Improvement** is embedded through sprint retrospectives, incident blameless reviews, and documented action items that inform future iterations. This combination of structured workflows, clear personas, continuous monitoring, and deliberate communication enables OctoAcme to deliver customer value reliably while maintaining team alignment and organizational learning.

## Process Docs Index

- [Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme principles, roles, and key artifacts
- [Roles & Personas](./octoacme-roles-and-personas.md) — Detailed descriptions of Project Managers, Product Managers, Developers, and their responsibilities
- [Project Initiation](./octoacme-project-initiation.md) — Steps to identify a need, form a team, and kick off a project
- [Project Planning](./octoacme-project-planning.md) — Breaking work into shippable increments, estimating, and creating release plans
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Daily standups, PR workflows, testing strategies, and progress reporting
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Risk registers, stakeholder communication, and escalation paths
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardized release types, pre-release checklists, and rollback procedures
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and driving organizational improvements

## Quick Start for New Team Members

1. Start with [Project Management Overview](./octoacme-project-management-overview.md) for the big picture
2. Review [Roles & Personas](./octoacme-roles-and-personas.md) to understand your role and others
3. Reference the specific process docs based on your project phase (planning, execution, release, etc.)
4. Keep the Risk Register and Status Updates current throughout your project

## Using These Docs in Copilot Spaces

Add process-specific docs to `.copilot/` in your project repository if you want Copilot Spaces to use them as context for AI-assisted guidance tailored to your project phase and role.
