# Phase 1 — Initial observations

## Dataset dimensions
- 300 rows
- 19 columns
- 288 distinct User_ID values

## User groups
- Students: 158
- Professionals: 142

## Initial quality flags
- Missing values appear in 17 columns.
- 12 exact duplicate rows were detected.
- Repeated User_ID values were detected and should be investigated.
- Several text categories have inconsistent capitalisation or spelling.
- Numeric-looking fields contain text units or currency symbols.
- The supplied description mentions `AI_Experience_Years`, which is absent from the CSV.
- Currency for `Monthly_Income` is not specified in the supplied description.

## Caution
These are profiling observations, not cleaning decisions. No records have been removed or values changed.
