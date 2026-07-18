# Modules

## Purpose

This table gives judges a fast way to understand the Robo-T-Rader ecosystem without reading every document first.

## Module inventory

| Module | Type | Role | Why it matters |
|---|---|---|---|
| Dev | execution | experimental live intraday environment | primary research surface for live behavior and iterative learning |
| Dev-Hetzner | execution | remote twin of Dev | supports replication and operational comparison |
| Prod-Hetzner | execution | production-style multi-engine runtime | main operational face of the platform |
| Naked | execution | minimal-rule swing environment | simple baseline and contrast against more complex systems |
| F2 | execution | model-oriented environment | explores governed ML-style edge with distinct architecture |
| Horizon | execution | larger-candle intraday environment | extends beyond very short intraday radar |
| HorizonMD | execution | multiday short-oriented environment | tests slower, thesis-based exposure |
| CC | execution | newer governed robot | strongest example of formal edge contracts and horizon separation |
| MarketData Hub | shared data | common quotes, candles, readiness, mappings | reduces duplicated ingest logic and standardizes data semantics |
| Sim | learning | replay and validation environment | allows testing without touching live operation |
| MarketSim | learning | market and broker simulation support | enables controlled replay conditions |
| VFL | learning | visual forensic surface | turns raw trade and market behavior into something explorable |
| Opportunity Coach | learning | compares ideal opportunities versus actual robot behavior | helps isolate what the robot missed or misread |
| Gem Mining | learning | extracts candidate improvements from repeated findings | turns pain into structured hypotheses |
| Forensics | learning | stores and interprets operational evidence | makes losses and divergences auditable |
| Edge Discovery Engine | discovery | mines historical data for candidate edge | formalizes hypothesis generation |
| Incubator | discovery | keeps edges in paper mode until promotion | avoids backtest-to-live shortcuts |
| EPIC Atlas | discovery | scans NYSE candidates outside current watchlists | expands the search space for future edge |
| Graphify | governance | maps robots, edges, factors, blockers, and actions | translates operational noise into decisions |
| Guardian | operations | periodic system checkpoint layer | keeps the ecosystem operationally accountable |
| Dashboards | operations | status, balances, findings, pending work | compresses complexity into human-readable views |
| Postmortems | operations | structured trade and system review artifacts | preserve causal learning over time |

## Reading guide

If you only remember one thing:

Robo-T-Rader is valuable because these modules are coordinated as one platform, not because any single robot exists in isolation.
