# SQL Injection Lab 01 (official title not yet verified)

> **Review required.** The original notes (`Lab-01`) did not record which PortSwigger lab was solved. The official title, URL and difficulty must be confirmed by the author, after which this directory should be renamed to match the official title (for example `SQL-Injection/<official-lab-title>/`).

## Overview

- Platform: PortSwigger Web Security Academy
- Official lab URL: Unknown
- Vulnerability category: SQL Injection (as recorded in the original notes)
- Official difficulty: Unknown
- Documentation status: Incomplete
- Completion status: Unknown
- Evidence status: Missing

The original notes state that this lab concerned a SQL injection vulnerability in an authorized PortSwigger lab environment. No further lab-specific details were documented.

## Learning Objectives

Not documented. The original notes give the general objective: "Understand and exploit the vulnerability in the authorized lab environment."

## Vulnerability Explanation

General background (external reference, not an original observation): SQL injection occurs when user-controlled input is incorporated into a SQL query in a way that changes the query's structure, allowing an attacker to read or modify data the application did not intend to expose. See the [PortSwigger SQL injection topic](https://portswigger.net/web-security/sql-injection).

## Initial Investigation

Not documented.

## Methodology

The original notes state only: "I investigated the application's behavior and tested inputs to identify the vulnerability." The specific requests, parameters and observations were not recorded.

## Exploitation and Solution

Not documented. No payload, request or result was recorded in the original notes, so none is included here.

## Root Cause

Not documented for this specific lab. Generally, SQL injection results from building queries by string concatenation with untrusted input instead of using parameterized queries.

## Security Impact

Demonstrated impact: Not documented.

Potential impact (general, hypothetical): unauthorized data disclosure, authentication bypass, or data modification, depending on the vulnerable query.

## Remediation

- Use parameterized queries (prepared statements) for all database access.
- Validate input against allow-lists where structural values (such as column names or sort order) must be dynamic.
- Run the database account with least privilege.

## Evidence

Evidence is **missing**. The original notes refer to a "Screenshot of the solved lab", but no screenshot file exists in the repository. See [screenshots/README.md](screenshots/README.md).

## Key Takeaways

Not documented. The original "What I learned" section contained template text only.

## Original Notes (preserved verbatim)

```text
# SQL Injection Lab 01

## Platform
PortSwigger Web Security Academy

## Vulnerability
SQL Injection

## Objective
Understand and exploit the vulnerability
in the authorized lab environment.

## Methodology
I investigated the application's behavior
and tested inputs to identify the vulnerability.

## Evidence
Screenshot of the solved lab.

## What I learned
Explain what you learned from this lab.
```

## References

- [PortSwigger Web Security Academy: SQL injection](https://portswigger.net/web-security/sql-injection)
- [OWASP SQL Injection Prevention Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/SQL_Injection_Prevention_Cheat_Sheet.html)

## Disclaimer

This work concerns intentionally vulnerable, authorized educational labs provided by PortSwigger. The techniques described must only be used on systems you are explicitly authorized to assess.
