# Architecture

## High-level idea

Robo-T-Rader is an ecosystem, not a single bot.

The system is organized in layers:

1. execution
2. shared data
3. learning and replay
4. discovery and incubation
5. governance and operations

## Layer 1 - Execution

Execution environments:

- Dev
- Dev-Hetzner
- Prod-Hetzner
- Naked
- F2
- Horizon
- HorizonMD
- CC

These environments represent different styles, horizons, and levels of maturity.

## Layer 2 - Shared data

MarketData Hub provides:

- quotes
- candles
- readiness
- mappings
- watchlist and universe products

This shared data plane reduces duplicated ingest logic and gives multiple consumers a common contract.

## Layer 3 - Learning and replay

These modules help the team understand and improve behavior without forcing every change directly into live execution:

- Sim
- MarketSim
- Forensics
- VFL
- Opportunity Coach
- Gem Mining

This is the part of the system that turns mistakes into structured learning.

## Layer 4 - Discovery and incubation

These modules search for and mature future edge:

- Edge Discovery Engine
- Incubator
- EPIC Atlas

Flow:

1. historical data is analyzed
2. candidate hypotheses are generated
3. candidates are incubated in paper mode
4. only sufficiently evidenced candidates can be promoted

## Layer 5 - Governance and operations

- Graphify
- Guardian
- dashboards
- postmortems
- parity and replay routines

These modules create operational visibility and make the system governable.

## Main operational story

The platform lets a team do the following:

1. operate live robots
2. centralize data semantics
3. replay and inspect failures
4. mine candidate improvements
5. discover and incubate new edges
6. promote validated ideas to production-style engines

That workflow is the core product being submitted to the competition.
