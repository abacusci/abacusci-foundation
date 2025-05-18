# Repository Naming Conventions

## Module Repositories

Repositories that describe the content, goals, and structure of a learning module use the following format:

```txt
mod-[module-name]-YYMM-[team-id]
```

- `mod-`: fixed prefix
- `[module-name]`: lowercase, kebab-case name of the module
- `YY`: last two digits of current year
- `MM`: current month number
- `[team-id]`: the team code defined above

**Examples:**

- `mod-python-basics-2509-e1`
- `mod-spreadsheet-basics-2512-e2`
- `mod-web-design-2511-b1`

## Team Repositories

Each team working on a specific module in a given month has its own repository. The naming format is:

```txt
team-[module-name]-YYMM-[team-id]
```

- `team-`: fixed prefix
- `[module-name]`: in kebab-case
- `YYMM`: start date of the module (2-digit year + 2-digit month)
- `[team-id]`: the team code defined above

**Examples:**

- `team-python-basics-2503-ba` → Builders Team A, March 2025
- `team-spreadsheet-basics-2505-eb` → Explorers Team B, May 2025
- `team-web-design-2506-da` → Discovers Team A, June 2025

Each team repository includes:

- A working space for student projects
- A wiki with progress logs, feedback, and evaluations
- Any collaborative material created during the module
