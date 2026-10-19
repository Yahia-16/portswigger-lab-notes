# PortSwigger Web Security Academy — Lab Notes

## About

This repository documents my hands-on learning with the [PortSwigger Web Security Academy](https://portswigger.net/web-security). It is a personal learning portfolio, **not** an official PortSwigger certification.

## Objectives

- Learn web application security and common web vulnerabilities.
- Document reproducible laboratory investigations.
- Study exploitation concepts together with remediation.
- Build a structured, honest cybersecurity learning portfolio.

## Repository Structure

```text
portswigger-lab-notes/
├── README.md
├── LAB-INDEX.md                 # central table of every lab
├── CONTRIBUTING.md              # how to add a lab
├── templates/lab-report-template.md
├── scripts/generate_lab_index.py
└── <Vulnerability-Category>/
    ├── README.md                # category index
    └── <lab-name>/
        ├── README.md            # lab report
        └── screenshots/         # evidence
```

## Vulnerability Categories

| Category | Labs |
|---|---|
| [SQL Injection](SQL-Injection/README.md) | 1 |

## Progress Summary

Counts reflect only what is present in this repository.

| Measure | Count |
|---|---|
| Lab directories | 1 |
| Labs with substantive documentation | 0 |
| Labs with credible solved evidence | 0 |
| Labs reported as solved but lacking evidence | 0 |
| Labs with incomplete documentation / unknown status | 1 |

The full list is in [LAB-INDEX.md](LAB-INDEX.md).

## Documentation Standards

- Each lab has its own directory containing a `README.md` report and a `screenshots/` folder.
- Reports follow a fixed structure (overview, methodology, solution, root cause, impact, remediation, evidence, references).
- Undocumented details are marked "Not documented"; nothing is filled in by guesswork.
- A lab is marked "Verified Solved" only when an authentic screenshot shows the solved state.
- Screenshots are never fabricated or edited to change their meaning, and secrets are removed before committing.

## Tools and Technologies

No specific tools are recorded in the current reports yet. Tools will be listed here as they are documented in individual labs.

## Disclaimer

All work concerns intentionally vulnerable labs that PortSwigger provides for authorized educational use. The techniques described must only be used on systems you are explicitly authorized to test. This repository is not affiliated with or endorsed by PortSwigger.

## Navigation

- [Lab Index](LAB-INDEX.md)
- [SQL Injection](SQL-Injection/README.md)
- [Contributing](CONTRIBUTING.md)
