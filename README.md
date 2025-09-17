# Golden Child

**Purpose**: Canonical source of truth for active projects, agents, and prompts.  
**Scope**: This repo centralizes canon (principles, memory, comms), projects, ops rituals, and curated knowledge.

## Quickstart

1. Read `canon/010-purpose.md` (why we exist).
2. Skim `canon/040-atp.md` (how we communicate).
3. Open a project folder and run with its README and PRD.

## Structure

.
├── CONTRIBUTING.md
├── README.md
├── canon
│   ├── 000-glossary.md
│   ├── 010-purpose.md
│   ├── 020-principles.md
│   ├── 030-memory-model.md
│   ├── 040-atp.md
│   └── 050-agentic-arch.md
├── knowledge
│   ├── briefs
│   └── inbox
├── ops
│   ├── launch-kits
│   │   └── RstudioLauchkit.md
│   ├── rituals.md
│   └── runbooks
│       └── Ops Runbook
└── projects
    ├── devops
    ├── finlit
    │   ├── ADR
    │   ├── PRD.md
    │   ├── README.md
    │   ├── prompts
    │   └── techstack.md
    └── grant-matcher
        ├── ADR
        ├── PRD.md
        ├── README.md
        ├── prompts
        └── techstack.md

- `canon/` — Truth layer (principles, memory, ATP, architecture).
- `projects/` — Executable work (PRDs, ADRs, prompts).
- `ops/` — Rituals, runbooks, launch kits.
- `knowledge/` — Notes → briefs.

## Contributing

- All decisions via ADRs.
- Issues must link to at least one canon file.
- PRs must update docs when behavior changes.

## License

TBD
