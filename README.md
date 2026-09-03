# PIBOB

### 5 AI agents. 2 chains. 1 trading system.

PIBOB is an experimental multi-agent trading system built around five specialized AI agents.

Each agent has a different role, working together to find opportunities, manage risk, execute trades and manage positions across Solana and Robinhood.

**The goal is simple: let the bots do the work.**

---

## The Crew

### P — Pedro
**Solana / Entry**

Finds potential entries and identifies opportunities.

### I — Ivan
**Robinhood / Execution**

Executes trades based on signals and decisions from the crew.

### B — Brian
**Solana / Risk**

Reviews opportunities and looks for reasons to kill bad setups.

### O — Oliver
**Robinhood / Macro**

Monitors broader market conditions and the tape.

### B — Benjamin
**Solana / Position Management**

Handles position sizing and exits.

---

## How PIBOB Works

Each agent has a specific responsibility.

```text
MARKET
   ↓
Pedro — Entry
   ↓
Brian — Risk
   ↓
Oliver — Macro
   ↓
Benjamin — Position
   ↓
Ivan — Execution

A trade can pass through multiple agents before anything happens.

One agent finds it.

Another challenges it.

Another checks the market.

Another manages the position.

Another executes it.

Tools

PIBOB is built around a growing set of tools and internal functions.

The agents can:

Analyze market conditions
Find trading opportunities
Evaluate risk
Reject bad setups
Execute trades
Manage positions
Determine position size
Handle exits
Coordinate decisions between agents

More tools are being added as PIBOB evolves.

Current Setup

5 AI agents

2 trading environments

Solana + Robinhood

24/7 operation

Human intervention: 0

Progress
Day 1

61 fills

9 vetoed

0 human intervention

Day 2

268 scanned

216 killed

29 kept

11% survival rate

Only the opportunities that survive the filters move further through the system.

Roadmap
Current
Multi-agent architecture
Specialized trading agents
Solana agents
Robinhood agents
Risk filtering
Position sizing
Exit logic
Automated execution
Next
More trading tools
Better agent coordination
Improved risk management
More market data
Advanced analytics
Public dashboards
More chains and markets
Philosophy

PIBOB isn't trying to build one perfect AI trader.

It's building a crew.

Five agents. Five responsibilities. One system.

Status

 PIBOB is actively being built.

New tools, logic and experiments are being added as the system evolves.

The experiment continues.

PIBOB is just getting started.

Disclaimer

PIBOB is an experimental project.

Nothing in this repository is financial advice. Trading involves risk, and the system can lose money.
