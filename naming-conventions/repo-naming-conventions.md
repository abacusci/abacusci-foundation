# Repository Naming Conventions

## Module Definition Repositories

Repositories that describe the content, goals, and structure of a learning module use the following format:

```txt
module-[module-name]
```

- `module-`: fixed prefix
- `[module-name]`: lowercase, kebab-case name of the module

**Examples:**

- `module-python-basics`
- `module-spreadsheet-basics`
- `module-web-design`

Each module repo includes:

- A detailed syllabus
- Project examples
- Calendar and schedule
- Educational resources
- Grading rubric

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