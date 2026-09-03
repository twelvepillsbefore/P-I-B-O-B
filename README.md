# PIBOB

### 5 AI agents. 2 chains. 1 trading system.

PIBOB is an autonomous multi-agent trading system built around five specialized AI agents.

Instead of relying on a single agent to make every decision, PIBOB splits the process across a crew of agents — each with a specific role, strategy and responsibility.

The goal is simple:

**let the bots do the work.**

---

## The Crew

PIBOB is made up of five agents:

### P — Pedro
**Solana / Entry**

Finds potential entries and identifies opportunities.

### I — Ivan
**Robinhood / Execution**

Executes trades based on the signals and decisions passed to him.

### B — Brian
**Solana / Risk**

Reviews opportunities and decides whether a setup is a trap.

### O — Oliver
**Robinhood / Macro**

Reads the tape and broader market conditions.

### B — Benjamin
**Solana / Position Management**

Handles position sizing and exits.

---

## How PIBOB Works

The agents don't all do the same thing.

Each agent has a specific responsibility.

```text
                 ┌──────────────┐
                 │    PIBOB     │
                 └──────┬───────┘
                        │
          ┌─────────────┼─────────────┐
          │             │             │
       SOLANA       ROBINHOOD      SOLANA
          │             │             │
      Pedro          Ivan          Brian
      Entry        Execution        Risk
          │             │             │
          └─────────────┼─────────────┘
                        │
                     Oliver
                      Macro
                        │
                    Benjamin
                  Size / Exit
