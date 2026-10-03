# Data Quality Report

## Dataset
TO_FILL

## Source
TO_FILL

## Access Date
TO_FILL

## Validation Summary

| Check | Raw Result | Processed Result | Treatment |
|---|---|---|---|
| Row count | TO_FILL | TO_FILL | Document |
| Duplicate records | TO_FILL | TO_FILL | Document |
| Missing project names | TO_FILL | TO_FILL | Document |
| Missing cost values | TO_FILL | TO_FILL | Document |
| Invalid date values | TO_FILL | TO_FILL | Document |
| Numeric data types | TO_FILL | TO_FILL | Document |
| Distinct sectors | TO_FILL | TO_FILL | Document |
| Distinct project statuses | TO_FILL | TO_FILL | Document |

## Validation Rules
- Do not replace missing cost with zero unless the source defines it so.
- Do not remove duplicate-looking projects without checking their keys.
- Do not infer completion from a scheduled date.
- Do not interpret expenditure as physical progress.
- Record the number of rows affected by each transformation.

## Conclusion
Complete this section after the actual validation has been performed.