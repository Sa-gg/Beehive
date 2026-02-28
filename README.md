# Beehive

**Restaurant POS and Management System**

A full-stack restaurant point-of-sale and management application consisting of a React frontend and an Express/Prisma backend.

## Repository Structure

This repository uses **Git submodules** to organize the project:

```
Beehive/
├── BEEHIVE-FRONTEND/   # React + TypeScript + Vite
└── BEEHIVE-BACKEND/    # Express + TypeScript + Prisma + PostgreSQL
```

## Getting Started

### Clone with submodules

```bash
git clone --recurse-submodules https://github.com/Sa-gg/Beehive.git
```

If you already cloned without submodules:

```bash
git submodule update --init --recursive
```

### Update submodules to latest

```bash
git submodule update --remote --merge
```

## Submodule Repositories

| Module | Repository |
|--------|-----------|
| Frontend | [BEEHIVE-FRONTEND](https://github.com/Sa-gg/BEEHIVE-FRONTEND) |
| Backend | [BEEHIVE-BACKEND](https://github.com/Sa-gg/BEEHIVE-BACKEND) |

See each submodule's own `README.md` for setup instructions.

## License

Private
