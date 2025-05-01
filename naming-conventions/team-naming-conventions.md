# Team Identifiers

A **Team** in AbacusCI is uniquely defined by the combination of the module, the start date, and the team code. The full identifier follows this format:

```txt
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
