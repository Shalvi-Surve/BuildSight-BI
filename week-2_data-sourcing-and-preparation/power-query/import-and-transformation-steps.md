# Power Query Import and Transformation

## Import
1. Open Power BI Desktop.
2. Select Get Data.
3. Select Excel workbook.
4. Choose the downloaded source file.
5. Select the relevant worksheet or table.
6. Select Transform Data.

## Profiling
1. Enable column quality, column distribution and column profile.
2. Inspect data types.
3. Review missing values.
4. Identify duplicate records.
5. Inspect date and numeric formatting.
6. Record unexpected categories and values.

## Transformation
The final steps must be updated to reflect the actual source.

Potential operations:
- Promote headers.
- Rename columns consistently.
- Trim and clean text fields.
- Convert date columns using the correct locale.
- Convert cost and expenditure fields to numeric types.
- Standardise category labels where justified.
- Handle missing values using documented rules.
- Investigate duplicate records before removal.
- Remove only records that meet a documented exclusion rule.

## Validation
Compare row counts and key field summaries before and after cleaning.
Confirm that the processed data has the expected types and columns.

## Evidence
Add screenshots of:
- Source import
- Data profiling
- Applied Steps
- Final processed table