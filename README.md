# Wumpus World Knowledge-Based Agent

An interactive **Artificial Intelligence project** that implements a **Knowledge-Based Agent** for the classic **Wumpus World problem** using **Propositional Logic**, **Conjunctive Normal Form (CNF)**, **Resolution Refutation**, and **Breadth-First Search (BFS)**.

The agent navigates an unknown environment, infers safe cells through logical reasoning, avoids hazards, and searches for gold intelligently.


---

## GitHub Repository

🔗 [Repository Link](https://github.com/MHassan05/wampus-agent)

---

## Project Overview

The **Wumpus World** is a classic Artificial Intelligence environment used to demonstrate logical reasoning under uncertainty.

In this project, the agent:

- Starts with no prior knowledge of hazards
- Perceives environmental clues
- Updates its Knowledge Base
- Applies logical inference
- Determines safe movement paths
- Attempts to reach the gold

---

## Features

### Knowledge-Based Reasoning
The agent makes decisions using logical inference rather than hardcoded movement.

### Resolution Refutation
Used to prove whether a cell is safe.

### Dynamic Grid Generation
Customizable grid size and pit count.

### Intelligent Pathfinding
Uses **Breadth-First Search (BFS)** to find shortest safe paths.

### Interactive Visualization
Real-time visual representation of:

- Agent movement
- Knowledge Base updates
- Resolution steps
- Performance metrics

---

## Environment Components

| Component | Description |
|----------|-------------|
| 🤖 Agent | Starts at (1,1) |
| 🌀 Pit | Hazardous cell |
| 👹 Wumpus | Dangerous creature |
| 🏆 Gold | Goal state |
| 💨 Breeze | Adjacent Pit indicator |
| 💀 Stench | Adjacent Wumpus indicator |

---

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript

---

## AI Concepts Implemented

- Knowledge-Based Agents
- Propositional Logic
- Conjunctive Normal Form (CNF)
- Resolution Refutation
- Logical Inference
- Breadth-First Search (BFS)

---

## How It Works

### 1. Perception
The agent detects:

- Breeze
- Stench
- Glitter

---

### 2. Knowledge Base Update
Percepts are converted into logical clauses.

Example:

```logic
B(1,1) → P(1,2) ∨ P(2,1)
```

---

### 3. Resolution Inference
The system proves whether cells are safe using contradiction.

---

### 4. Movement
The agent:

- Moves to inferred safe cells
- Uses BFS for shortest path
- Takes risks only when necessary

---

## Performance Metrics

The system tracks:

- Inference Steps
- Agent Moves
- Knowledge Base Clauses
- Safe Cells Inferred

---

## Project Structure

```plaintext
wampus-agent/
│
├── index.html
├── README.md
```


## Challenges Faced

- Implementing Resolution Refutation
- Dynamic CNF clause handling
- Synchronizing UI with reasoning engine
- Designing intelligent inference logic

---

## Learning Outcomes

This project strengthened understanding of:

- Logical reasoning systems
- AI decision-making
- Search algorithms
- Knowledge representation

---

## Author

**Ahmad Khan**

Artificial Intelligence / Computer Science Student

---

## License

This project is developed for academic purposes.
