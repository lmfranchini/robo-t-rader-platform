# Devpost Submission

## Project name

Robo-T-Rader

## Category

Work & Productivity

## One-line summary

Robo-T-Rader is an AI-assisted platform for building, validating, governing, and operating autonomous trading systems through shared data, simulation, edge discovery, incubation, and multi-engine execution.

## Full description

Robo-T-Rader is a modular operating platform for autonomous trading systems.

Instead of treating trading automation as one opaque bot, Robo-T-Rader separates the work into coordinated layers:

- live execution environments
- a shared market data plane
- simulation and replay
- visual review and opportunity analysis
- gem mining and postmortem learning
- edge discovery and incubation
- governance and operational control

The platform exists to help a technical team turn trading ideas into governed autonomous systems with better discipline, better visibility, and a cleaner path from hypothesis to operation.

This is why the project fits Work & Productivity: the core value is not just market execution. The core value is a workflow platform that helps a team develop and operate autonomous systems more effectively.

## What existed before Build Week

Before OpenAI Build Week, Robo-T-Rader already included:

- multiple robot environments
- demo trading execution
- postmortem and replay practices
- infrastructure across robo-lab and Hetzner
- monitoring and operator control surfaces

This submission does not claim that the entire platform was built during Build Week.

## What was built or meaningfully extended during Build Week

The competition submission focuses on platform-level extensions, especially:

- stronger use of MarketData Hub as a shared contract surface
- EPIC Atlas integration as a 24/7 candidate scanner for new NYSE instruments
- read-only pilot activation and diagnostics for Atlas
- clearer edge discovery and incubation flow
- stronger competition-grade documentation, architecture, and evidence packaging
- a cleaner canonical repository for judges to understand the full ecosystem

## Main demo surface

The main operational face shown in the demo is:

- Prod-Hetzner

The supporting modules shown in the platform story are:

- MarketData Hub
- Sim / MarketSim
- VFL
- Opportunity Coach
- Gem Mining
- Graphify
- Edge Discovery Engine
- EPIC Atlas

## How Codex and GPT-5.6 were used

Codex and GPT-5.6 were used as engineering collaborators to:

- read and synthesize existing codebases
- design data and integration contracts
- refactor architectural boundaries
- debug runtime and infrastructure behavior
- structure edge discovery workflows
- package the system into competition-ready documentation

## Codex thread evidence

Primary thread:

- `Desarrollo`
- ID: `019e3cc2-773c-7bb0-9b29-79b83dbad1ba`

Supporting Build Week threads:

- `Diseña scanner EPIC 24/7`
- ID: `019f6726-5785-7c30-8220-9cc9e83713dc`

- `Diseñar escáner de EPICs`
- ID: `019f6721-a640-71c2-878c-7428a0ed5d87`

## Public repository

Canonical submission repo:

- `https://github.com/lmfranchini/robo-t-rader-platform`

## Supporting repositories

Several supporting modules exist as private repositories or private runtime modules behind the public submission story, including:

- EPIC Atlas
- MarketData Hub
- Edge Discovery Engine
- Graphify
- Prod runtime support repositories

For the submission, the public entry point remains the canonical platform repository. Private support modules are described as part of the ecosystem rather than required public browsing targets.

## Notes for final submission

Before pasting this into Devpost, fill in:

- public demo video URL
- any supporting public repositories you decide to expose
