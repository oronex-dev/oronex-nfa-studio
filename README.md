# ORONEX NFA Studio

**Design logic. Visualize possibilities.**

A modern, interactive visual workspace for designing, simulating, and understanding **nondeterministic finite automata (NFAs)**.

Built for Computer Science students, educators, and learners who want to explore automata theory through intuitive visual interactions.

![ORONEX NFA Studio Preview](docs/images/hero-banner.png)

## About the Project

ORONEX NFA Studio aims to transform abstract automata concepts into a practical, interactive learning experience.

Rather than defining an NFA entirely through handwritten diagrams and transition tables, users can construct states, connect transitions, configure alphabets, and observe how a machine processes input.

The project focuses on standard NFAs without epsilon transitions.

## Project Goals

- Make automata theory more approachable.
- Provide a reliable interactive NFA editor.
- Demonstrate nondeterministic string processing.
- Connect graphical representations to mathematical definitions.
- Provide a polished, accessible learning experience.

## Main Features

*Update this section to match the verified release.*

- **Visual Automaton Builder** — Create and connect states using an interactive diagram.
- **Configurable Alphabet** — Define input symbols and transition rules.
- **NFA Simulation** — Follow reachable state sets while testing strings.
- **Transition Table** — Explore the automaton's transition function.
- **Formal Definition** — Examine the machine's five-tuple representation.
- **Learning Examples** — Experiment with common automata problems.
- **Import and Export** — Save and exchange automata using JSON.
- **Diagram Export** — Download visualizations for reports or learning materials.
- **Responsive Interface** — Work across compatible screen sizes.
- **Accessible Controls** — Use alternative editing and navigation methods.

## Application Preview

### Interactive Editor

![Automaton Editor](docs/images/editor-desktop.png)

### String Simulation

![String Simulator](docs/images/simulation-studio.png)

### Transition Table

![Transition Table](docs/images/transition-table.png)

### Dark Theme

![Dark Mode](docs/images/dark-mode.png)

### Responsive Layout

![Mobile Interface](docs/images/mobile-view.png)

## Mathematical Foundation

An NFA is defined by the five-tuple:

M = (Q, Σ, δ, q0, F)

Where:

- Q — Finite set of states
- Σ — Input alphabet
- δ — Transition function
- q0 — Initial state
- F — Set of accepting states

The machine accepts a string if at least one valid computation ends in an accepting state after consuming the complete input.

## Technology Stack

- Vue 3
- Vite
- JavaScript / TypeScript, as implemented
- Tailwind CSS
- Browser-based project storage

## Local Development

```bash
git clone <YOUR_FINAL_REPOSITORY_URL>
cd oronex-nfa-studio
npm ci
npm run dev
```

For a production build:

```bash
npm run build
```

## Documentation

- Architecture
- NFA Specification
- User Guide
- Accessibility
- Testing
- Deployment

## Project Status

**In development — modernization and implementation in progress.**

Features listed as goals should not be treated as production-ready until implemented and verified.

## Attribution

This project began as an exploration of an existing NFA application. Any permitted reuse of the original source must retain appropriate license and attribution notices.

See `docs/ATTRIBUTION.md` for the original project and its contribution to this work.

## Developer

**ORONEX — Personal Developer Brand**

Frontend Engineering · Interactive Web Applications · UI/UX Design · Educational Technology

Designed to make complex computing concepts more understandable through thoughtful interfaces and reliable software.
