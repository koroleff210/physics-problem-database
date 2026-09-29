# V4 Physics Question Bank

This repository contains the shareable V4 question bank only. It includes
canonical question records, referenced image assets, schemas, migration and
review logs, and prebuilt database exports. It does not include earlier bank
versions, source collections, analysis workspaces, or internal review reports.

## Contents

- `problems/`: one JSON record per canonical problem.
- `assets/`: image files referenced by problem records.
- `build/questionbank.sqlite`: ready-to-query SQLite database.
- `build/questions.jsonl`: newline-delimited JSON export.
- `migration/`: provenance, review, duplicate-decision, and revision logs.
- `schema/`: JSON schemas for records and logs.

There are 2,966 problem records and 1,522 image assets in this release. Image
references in records use content-addressed asset IDs; keep the `assets/`
directory alongside the problem files when using them.

The migration logs retain source identifiers for provenance, but do not contain
older-version problem banks. This repository is a data release; migration and
validation tooling remains in the separate development workspace.
