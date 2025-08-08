# Backend SWE Take-Home Assignment (Tic-Tac-Toe)

## Overview

This is a **4-hour take-home assignment**. You will implement a Tic-Tac-Toe game backend API. Your assignment is tailored: a randomized (but reproducible) set of TODOs, features, and bugs has been embedded inline.

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

```bash
npm ci
```

### Running the Application

```bash
npm run build
npm run dev
```

### Running Tests

```bash
npm test
```

### Running the Simulation

```bash
npm run simulation
```

## Project Structure

```
src/
├── models/
├── services/
├── routes/
├── middleware/
└── utils/
```

## What You Need to Implement

### Selected Tasks

#### TODOs
- Add Go integration tests for routes (health/games)
- Implement and validate core game logic (join/move/win/draw)
- Add unit tests for GameModel and PlayerModel
- Implement Go models for Game and Player with in-memory store
- Implement services in Python to orchestrate models

#### Feature Requests

#### Bugs To Fix

Additionally, look for inline TODOs in `src/routes/*`, `src/services/*`, `src/models/*`, and `src/index.ts`. These indicate precise changes to make.

> Focus on correctness, quality, and clarity. If you finish early, feel free to polish or extend.

## Notes

- Inline TODOs are your primary guide. GitHub Issues are intentionally disabled.
- Keep commits small and frequent with clear messages.
- You may add libraries if they help you implement tasks cleanly.

- A `.gitignore` and `.dockerignore` are included to keep your repo and Docker context clean.

## Submission

1. Ensure tests pass
2. Run the simulation script
3. Update this README with any setup notes
4. Submit your repository URL

Good luck! 🚀


