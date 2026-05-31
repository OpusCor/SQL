<div align="center">

# [SQLCor]

### A controlled SQL terminal for Creatio Cloud

Direct database access for administrators — safe, audited, in-platform.

[Documentation](https://sql.opuscor.com) · [Status](#status) · [Contact](#contact)

</div>

---

## The problem

Creatio Cloud administrators have no direct database access. The platform abstracts SQL away — which is fine for end users, but creates a daily bottleneck for admins who need to:

- Investigate data inconsistencies
- Audit configuration changes
- Verify data after imports and migrations
- Debug workflow and process issues
- Run quick operational and reporting queries

Without direct access, a thirty-second query becomes a two-day support ticket, a tedious UI reconstruction, or a heavy export into Excel or Power BI. None of these scale.

## What SQL Cor does

SQL Cor adds a controlled, audited SQL terminal directly inside Creatio. It gives administrators the database access the Cloud platform removes — without sacrificing security or traceability.

- **Direct SQL execution** against the Creatio database (PostgreSQL or MSSQL)
- **Graded access control** — Read-only / DML / DDL, assigned per user
- **Query blacklist** — block dangerous patterns system-wide, regardless of role
- **Full audit log** — every query logged with user, timestamp, result, and execution time
- **Safe defaults** — automatic row-limit injection on SELECTs, configurable timeouts
- **Dry-run mode** — preview affected rows before running a DML statement
- **Dark / light themes**, English and Ukrainian
- **Administration page** for managing access rules, blacklist entries, and viewing logs

## Why it's built the way it is

The goal was never "give everyone raw database access." It was to give the right people the right level of access, with everything logged.

| Layer | What it does |
|-------|--------------|
| **Access control** | Only authorized users run queries. Permissions graded per user. |
| **Query blacklist** | Dangerous patterns blocked at system level, above individual roles. |
| **Audit log** | Every query recorded — who, when, what, how long. |
| **Safe defaults** | Row limits, timeouts, dry-run previews to protect the environment. |

## Live demo

SQL Cor is currently running on a live, read-only demo environment as part of an open testing period.

Demo access (login credentials for a live Creatio instance) is shared through the beta announcement on LinkedIn — see [Contact](#contact) to connect.

For the full feature tour and documentation, visit **[sql.opuscor.com](https://sql.opuscor.com)**.

## Status

**🟡 In testing (beta).**

SQL Cor is currently in a testing period. The application is stable and running on the live demo above.

**The downloadable package is coming soon.** After the testing period, SQL Cor will be published here for installation as a standard Creatio package.

A live read-only demo is available during the testing period — access is shared via the beta announcement on LinkedIn. If you'd like to try the demo, run SQL Cor in your own environment, or you have questions, reach out — see [Contact](#contact).

## Installation

> Installation instructions will be published here when the downloadable package is released.

Full setup and configuration documentation is available now at **[sql.opuscor.com](https://sql.opuscor.com)**.

In short, once released: install as a standard Creatio package (drag-and-drop ZIP), configure access rules and blacklist on the administration page, and you're running. Self-contained, no external dependencies. Works on Creatio Cloud and on-premise.

## Documentation

Complete documentation — user guide, administration guide, configuration reference — lives at:

**👉 [sql.opuscor.com](https://sql.opuscor.com)**

## Contact

SQL Cor is built and maintained by Artem [Last Name], an independent Creatio specialist.

- Questions, early access during testing, or installation help: reach out via [LinkedIn]([LINKEDIN_PROFILE])
- Available for Creatio implementation projects and consulting

## License

> License will be specified at public release.

---

<div align="center">

**[SQLCor]** — SQL access for Creatio Cloud admins. Safe, audited, in-platform.

[sql.opuscor.com](https://sql.opuscor.com)

</div>
