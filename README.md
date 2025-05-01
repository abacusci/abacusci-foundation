# AbacusCI Foundation Repository

This repository defines the naming conventions and structural principles used across all AbacusCI GitHub repositories. It serves as the central reference point for contributors, instructors, and collaborators.

## Repository Naming Conventions

### 1. Module Definition Repositories

Repositories that describe the content, goals, and structure of a learning module use the following format:

```
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

---
### 2. Team Identifiers

A **Team** in AbacusCI is uniquely defined by the combination of the module, the start date, and the team code. The full identifier follows this format:

```
[module-name]-YYMM-[team-code]
```

Where:

- `[module-name]`: the name of the module in kebab-case (e.g. `python-basics`, `web-design`)
- `YYMM`: the start date of the module (e.g. `2503` = March 2025)
- `[team-code]`: composed of:
  - a level indicator:
    - `d` = Discovers (ages 11–12)
    - `e` = Explorers (ages 13–15)
    - `b` = Builders (ages 16+)
  - followed by a letter (`a`, `b`, `c`, etc.) to distinguish different teams within the same level and period

**Examples of full team identifiers:**
- `python-basics-2503-ba` → Team A of Builders working on Python Basics in March 2025
- `spreadsheet-basics-2505-eb` → Team B of Explorers working on Spreadsheet Basics in May 2025
- `web-design-2506-da` → Team A of Discovers working on Web Design in June 2025

These identifiers are used in team repository names to ensure uniqueness, clarity, and consistent ordering.

---

### 3. Team Repositories

Each team working on a specific module in a given month has its own repository. The naming format is:

```
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

---

## Purpose of This Repository

The `foundation` repo exists to document the core standards, principles, and practices of AbacusCI. Over time, it may include:

- Onboarding guides
- Pedagogical documentation
- Workflow processes
- Contribution and collaboration policies

For any new module or team, refer to this repository to ensure consistency across the platform.

