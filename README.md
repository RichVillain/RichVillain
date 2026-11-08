# Rich Villain

**Full-Stack Developer | Systems Architecture | AI & Agent Infrastructure | Product Engineering**

I design and develop software across full-stack applications, systems architecture, AI-assisted workflows, and creative technology.

My work focuses on turning complex requirements into structured, testable systems—with clear component boundaries, observable behavior, documented decisions, and explicit verification gates.

## Areas of focus

- **Full-stack product engineering** — application architecture, APIs, integrations, and responsive product experiences.
- **Systems architecture & verification** — lifecycle design, fail-closed change gates, evidence, and auditability.
- **AI and agent infrastructure** — routing, memory, tool integration, and coordinated workflows.
- **Creative technology** — music and creator tools, audio workflows, and interactive experiences.

## Selected work

Some projects are private or in active development. Their descriptions distinguish documented architecture from deployment or production status.

### Level0

**Simple:** A structured approach to governing and verifying changes across software workflows.

**Complex:** The Level0 project family includes a fail-closed Node.js change protocol and a persistent verifier. The protocol runs candidate changes in an isolated temporary worktree, executes configured gates, and records failures as open items. It does not merge, push, or deploy changes.

### LoBO

**Simple:** An AI-agent ecosystem for routing work, coordinating agents, and maintaining verifiable workflow memory.

**Complex:** The core architecture includes a routing supervisor, agent integrations, an append-only LORE record, job coordination, checkpoints, and verification-oriented tests. Individual deployment and runtime claims are kept separate from repository architecture.

### NDRAP

**Simple:** A creator-focused music platform exploring song-card collection, competitive battles, and creator participation.

**Complex:** The monorepo contains web application surfaces, a deterministic FastAPI engine, Supabase-backed state, exchange services, and Solidity contracts. Production readiness remains conditional on live infrastructure, security, deployment, device, load, backup, and restore verification.

### Space Bike

**Simple:** A mobile and edge transport companion for the LoBO ecosystem.

**Complex:** The vehicle-only service is designed to carry sessions, sealed checkpoints, and completed jobs between an edge device and the home system. It does not make routing decisions or own the authoritative ledger. The repository documents that it is not yet deployed.

## Engineering principles

- Verify behavior; do not infer it from a successful build or static wiring.
- Separate architecture, implementation, deployment, and production readiness.
- Prefer fail-closed gates for changes that cannot be verified.
- Preserve provenance and record meaningful decisions.
- Document known gaps instead of hiding them.

## Technologies represented in my project work

TypeScript · JavaScript · Node.js · Python · FastAPI · APIs · Supabase · PostgreSQL · Solidity · Playwright and automated testing

*This profile describes areas of work and selected projects. It does not imply that every project is public, commercially available, or production-deployed.*
