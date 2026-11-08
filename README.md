# claude-app-builder-skill

A Claude Code skill for turning application ideas into scoped requirements, technical plans, project structures, and implementation workflows.

## Overview

This skill acts as an application-building orchestrator. It helps interpret a product request, identify the application type, choose a suitable technology stack, plan the project structure, and coordinate implementation work.

It is designed to support both new application scaffolding and feature development in existing repositories.

## Main Capabilities

- Detect the type of application from the requirements.
- Clarify users, goals, workflows, and constraints.
- Select a technology stack based on project needs.
- Plan architecture and directory structure.
- Coordinate multi-agent implementation where useful.
- Scaffold project foundations.
- Select a starter template for the application type.
- Plan and implement features incrementally.
- Handle validation, errors, and integration concerns.

## Supported Project Categories

The repository includes templates and guidance for several application types, including:

- Web applications and full-stack services.
- React and Next.js projects.
- Nuxt and other modern frontend applications.
- Express and FastAPI backends.
- Command-line tools.
- Browser extensions.
- Electron desktop applications.
- Flutter and React Native mobile applications.
- Monorepo structures.

Check the available template directory before selecting a starting point.

## Installation

```bash
git clone https://github.com/Brajesh31/claude-app-builder-skill.git ~/.claude/skills/app-builder
```

## Usage

Invoke the skill when planning or building an application:

```text
/app-builder
```

Describe the product, target users, core workflow, preferred stack if any, deployment environment, and delivery constraints.

## Recommended Workflow

1. Classify the project and inspect any existing codebase.
2. Clarify the user problem and core application workflow.
3. Separate essential requirements from optional features.
4. Choose a stack that fits the team's experience and deployment constraints.
5. Select the closest project template, if one exists.
6. Define the architecture and initial directory structure.
7. Build a narrow working foundation.
8. Implement features in small, verifiable steps.
9. Add tests, error handling, and security controls.
10. Validate the complete user journey before expanding scope.

## Reference Guide

| File | Purpose |
|---|---|
| `project-detection.md` | Identify application type |
| `tech-stack.md` | Compare stack choices |
| `agent-coordination.md` | Plan parallel implementation |
| `scaffolding.md` | Define project structure |
| `feature-building.md` | Add features to an existing project |
| `templates/SKILL.md` | Select a suitable starter template |

## Planning Checklist

- The target user and problem are clear.
- The first release has a manageable scope.
- The stack is justified by requirements.
- Data ownership and API boundaries are understood.
- Authentication and authorization are planned where needed.
- Deployment and environment configuration are considered.
- Testing and acceptance criteria are defined.
- The implementation plan has clear milestones.

## Repository Contents

- `SKILL.md`: Main application orchestration instructions.
- `references/` and supporting Markdown guides: Project detection, stack selection, coordination, scaffolding, and feature workflows.
- `templates/`: Starter structures for supported project categories.
- `README.md`: Overview and practical usage.

## Practical Advice

Do not start by generating a large application with every possible feature. Build the smallest end-to-end workflow that proves the product's core value, then expand based on validated requirements.
