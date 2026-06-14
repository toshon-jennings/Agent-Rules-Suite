# Agent Rules Suite

Reusable Markdown templates and operating docs for AI-assisted projects.

This repo is for project context that humans and coding agents can both use: source maps, handoffs, working rules, rulings, runbooks, and lightweight coordination docs that make a repo easier to enter and continue.

## What you will find

| Area | Contents |
| --- | --- |
| Project orientation | Templates that tell an agent what a repo does, where the important files live, how to run it, and what risks to watch. |
| Continuity | Handoff docs for active work, interrupted tasks, known blind spots, and next steps. |
| Agent behavior | Shared operating rules for coding agents, including how to edit, ask questions, manage state, and avoid unnecessary churn. |
| Human rulings | Append-only decisions that prevent agents from re-asking settled questions. |
| Local coordination | Port and service notes for avoiding development-environment conflicts. |

## Current docs

| File | Description |
| --- | --- |
| [templates/SUMMARY.md](./templates/SUMMARY.md) | Reusable starter template for a project source map. |
| [AGENTS.md](./AGENTS.md) | Repo-level rules for coding agents working here. |
| [HITL.md](./HITL.md) | Human-in-the-loop rulings and escalation boundaries. |
| [PORTMASTER.md](./PORTMASTER.md) | Port assignment and local service coordination notes. |
| [SUMMARY.md](./SUMMARY.md) | Source map for this repository. |
| [HANDOFF.md](./HANDOFF.md) | Active task state and continuity notes for this repository. |

## How to use it

Start by copying [templates/SUMMARY.md](./templates/SUMMARY.md) into another repo as `SUMMARY.md`, then fill in the project purpose, source map, runbook, conventions, and known risks. Add project-specific handoff, HITL, or agent-rule docs when the work needs more continuity.

More supplemental Markdown templates will be added here over time.
