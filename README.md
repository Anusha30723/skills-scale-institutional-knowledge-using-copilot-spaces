# OctoAcme Project Management Documentation

## Overview
OctoAcme runs projects through a clear lifecycle — Initiation, Planning, Execution, Release, and Retrospective — centered on delivering customer value iteratively. Initiation uses a lightweight one-pager to confirm the problem, stakeholders, success metrics, and go/no-go decisions. Planning turns approved initiatives into prioritized, shippable backlog items with clear acceptance criteria, estimates, and a Definition of Done so teams can align on scope and dependencies before work begins.

Workflows emphasize a project board flow (Backlog → Ready → In Progress → In Review → QA → Done) and a small-PR pull request practice with CI gating, acceptance criteria in PR descriptions, and at least one approval before merging. Backlog items follow a template (title, description, acceptance criteria, priority, estimate, owner). Sprint planning is timeboxed and capacity-aware. Risks and cross-team dependencies are tracked in a Risk Register and surfaced during weekly syncs for escalation when needed.

Roles and responsibilities are defined so ownership is unambiguous: Product Managers set outcomes and prioritize, Project Managers coordinate delivery and communications, Developers implement and test, QA validates acceptance criteria, and Stakeholders provide approvals and inputs. Persona definitions are used to set expectations for communications, reviews, and delivery responsibilities across the team.

Quality & Release practices require automated and manual checks: unit and integration tests, end-to-end smoke tests for critical flows, and security scanning in CI. Releases are classified (patch, minor, major) and require passing CI/security scans, release notes, a rollback plan, and smoke test verification before production deployment. Retrospectives capture learnings into prioritized action items that feed back into planning and continuous improvement.

## Quick Navigation Guide

### Getting Started with a New Project
- [Project Initiation Guide](octoacme-project-initiation.md) — Steps to validate and authorize work, align stakeholders, and create a lightweight plan

### Planning & Preparation
- [Project Planning](octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and backlog for delivery
- [Roles & Personas](octoacme-roles-and-personas.md) — Understand core team roles and responsibilities
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies

### Execution Phase
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Guidance for managing day-to-day execution and tracking progress toward project milestones

### Release & Deployment
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardized release practices and deployment checklist

### Closing & Continuous Improvement
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — How to run retrospectives and convert learnings into action

## Core Principles
- Customer-first: prioritize customer value and usability
- Iterative delivery: deliver small, testable increments
- Clear ownership: each project has a named PM and Product Lead
- Data-informed decisions: measure impact and iterate based on evidence
- Psychological safety: encourage feedback and learning

## Notes
- This README is intended as a single entry point for OctoAcme process docs. Keep links current and add new process docs under the docs/ folder so they are discoverable here.
