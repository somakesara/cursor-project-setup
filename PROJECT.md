# Project

## What This Is
<!-- One paragraph: what problem does this project solve, for whom, and at what scale. -->
TODO

## Tech Stack
<!-- Link to .cursor/rules/stack.mdc for the canonical list. Summarise the key choices here. -->
TODO

## Entry Points
<!-- Where does execution start? List the main binaries, scripts, or services. -->
TODO

## Key Flows
<!-- Describe 2–5 critical user or data flows end-to-end (e.g., "user signs up", "order is processed"). -->
TODO

## Folder Layout
<!-- High-level map of the repository. Update when structure changes significantly. -->
```
.
├── .agent/          # Agent working files (Planner / Implementer / Reviewer)
├── .cursor/rules/   # Cursor MDC rules loaded by all agents
├── .githooks/       # Local git hooks (register with: git config core.hooksPath .githooks)
├── docs/            # Architecture docs, glossary, domain notes
├── features/        # Feature specs or vertical slices (project-specific)
└── PROJECT.md       # This file
```

## Local Setup
<!-- Steps a new developer follows to run this project locally. -->
```sh
# 1. Clone the repo
# git clone <url> && cd <repo>

# 2. Register git hooks
# git config core.hooksPath .githooks
# chmod +x .githooks/pre-commit

# 3. Install dependencies
# TODO

# 4. Configure environment
# cp .env.example .env
# # Fill in required values

# 5. Run
# TODO
```
