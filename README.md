# Multi-Agent Pacman Capture the Flag

Multi-Agent AI project developed for the *Multi-Agent Systems* course at Leiden University.  
The project focuses on designing intelligent agents for the Pacman Capture the Flag environment using Monte Carlo Tree Search (MCTS) and alternative decision-making strategies.

## Authors

- Lorenzo Madiai

---

# Project Overview

The objective of the project is to develop coordinated Pacman agents capable of:
- collecting food pellets,
- avoiding enemy ghosts,
- defending their territory,
- maximizing team score in a competitive multi-agent environment.

The environment is based on the classic Berkeley Pacman Capture the Flag framework. :contentReference[oaicite:1]{index=1}

The project investigates:
- Monte Carlo Tree Search (MCTS),
- heuristic-based evaluation functions,
- offensive and defensive coordination strategies,
- alternative non-tree-search agents,
- tournament-based evaluation.

---

# Environment

Two teams compete against each other:
- Red Team
- Blue Team

Each team controls:
- Pacman agents,
- Ghost agents.

The goal is to retrieve food from the opponent's side while defending your own territory. Power capsules temporarily weaken enemy ghosts and create additional strategic opportunities. :contentReference[oaicite:2]{index=2}

---

# Implemented Approaches

## Monte Carlo Tree Search (MCTS)

The main agent architecture is based on Monte Carlo Tree Search:
- selection,
- expansion,
- simulation,
- backpropagation.

The implementation explores:
- search depth,
- rollout strategies,
- exploration-exploitation trade-offs,
- state evaluation heuristics.

The project also investigates how MCTS behaves in:
- partially adversarial environments,
- dynamic multi-agent interactions,
- real-time decision-making settings.

---

# Alternative Agents

In addition to MCTS, alternative agents were implemented for comparison purposes, including:
- heuristic-based agents,
- reactive strategies,
- simplified offensive/defensive agents.

These baselines were used to evaluate the strengths and limitations of MCTS in competitive gameplay scenarios.

---

# Evaluation

Agents were evaluated through local tournaments using multiple performance metrics:
- win rate,
- average score,
- offensive efficiency,
- defensive effectiveness,
- overall team coordination.

Different MCTS parameter configurations were experimentally compared to analyze their impact on performance.

---

# Technologies

- Python
- Monte Carlo Tree Search (MCTS)
- Berkeley Pacman Capture the Flag Framework
- Multi-Agent Reinforcement & Search Techniques
