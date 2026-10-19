# Contributing: Adding a New Lab

Every lab follows the same three-level layout:

```text
Category-Name/            # PascalCase-with-hyphens, one per PortSwigger topic
├── README.md             # category index table
└── official-lab-title/   # lowercase-hyphenated official lab title
    ├── README.md         # the lab report
    └── screenshots/      # authentic evidence only
```

## Steps

1. Create the category directory (e.g. `Access-Control/`) with a `README.md` if it does not exist yet.
2. Create the lab directory named after the official lab title in lowercase with hyphens.
3. Copy `templates/lab-report-template.md` to `<lab>/README.md` and fill it in. Write "Not documented" rather than guessing.
4. Add a `screenshots/` folder. Use descriptive names such as `initial-request.png`, `vulnerability-confirmed.png`, `solved.png`. If you have none, add a `screenshots/README.md` stating that evidence is missing.
5. Add a row for the lab in the category `README.md`.
6. Run `python3 scripts/generate_lab_index.py` to refresh `LAB-INDEX.md`.

## Evidence rules

- Only real, unedited screenshots of your own work.
- Remove or blur session cookies, tokens, emails and any personal data before committing.
- Use "Verified Solved" only when a screenshot shows the solved state; otherwise use "Reported Solved", "In Progress" or "Unknown".
