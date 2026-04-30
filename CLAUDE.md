# tutu-public

Part of the Tutu School ecosystem.

For shared business context (10 schools across CA/CO/WA), DB connection conventions, and schema gotchas (especially: `db_structure.sql` is incomplete, `school_scorecard.date` is end-of-month, `purchases.canceled` is unused, `trials` columns differ from the SQL file), see:

`../TutuSchool/CLAUDE.md`

That file does **not** auto-cascade into this directory, so read it explicitly when this project touches the shared Postgres DB or references school data.
