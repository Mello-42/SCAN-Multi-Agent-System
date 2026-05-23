# Self-Correcting Agent Network (SCAN)

**A safe, self-correcting multi-agent system with critical reasoning and content safety filtering.**

---

## What is SCAN?

The **Self-Correcting Agent Network (SCAN)** is a multi-agent reasoning system designed for safe, robust, and high-quality decision-making.

Its architecture consists of a **safety-first pipeline** followed by collaborative reasoning between specialized agents.

---

## System Architecture & Flow

1. **User Input** is first received by **Glitch**
2. **Glitch** acts as a **Content Safety Filter** — it checks the input for prohibited, harmful, or inappropriate content
3. If **forbidden content is detected** → Glitch responds with: *"I can't provide an answer to that."*
4. If the input is **clean** → it is forwarded to **Monty** and **ECHO**, who then engage in mutual critical discussion to generate a well-reasoned response

---

## System Components

| Agent     | Role                        | Function |
|-----------|-----------------------------|----------|
| **Glitch**    | Content Safety Filter      | First line of defense. Filters user input for prohibited content before any reasoning occurs |
| **Monty**     | Orchestrator & Mentor      | Leads the discussion, coordinates the reasoning process |
| **ECHO**      | Critical Thinker           | Challenges and refines Monty's proposals for logical soundness and quality |
| **NEXUS**     | Memory Compressor          | Compresses long-term memory to ≤ 100 words to maintain efficient context retention |

---

## Key Features

- **Safety-First Design** — All user inputs are filtered by Glitch before reaching the reasoning agents
- **Mutual Critical Reasoning** — Monty and ECHO actively debate and improve solutions together
- **Self-Correction Mechanism** — Built-in quality control through agent-to-agent feedback
- **Efficient Memory Management** — NEXUS ensures long-term context without excessive token usage
- **Responsible AI Principles** — Explicit safety layer demonstrates ethical and professional development practices

---

## Goals

- Build autonomous agents that can think critically while maintaining strict safety boundaries
- Demonstrate a production-ready multi-agent architecture with content moderation
- Create a foundation for scalable, trustworthy AI systems

---

## Current Status

🚧 **Active Development** — Core safety layer (Glitch) and agent collaboration (Monty + ECHO) are being implemented and tested.

---

*Developed by Mello • 2026*

**Open to opportunities** — Feel free to reach out via email or X.