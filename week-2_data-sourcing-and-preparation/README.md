# Week 2 — Data Sourcing, Import and Transformation

## Objective
Identify publicly available construction or infrastructure project
data and document a reproducible process for importing, profiling,
cleaning and transforming it using Power BI methodologies.

## Proposed Primary Source
MDoNER Projects Dashboard:
https://www.nesetu.mdoner.gov.in/projects/project-list

The dashboard provides project-level information including project
name, state, sector, sanctioned date, approved cost, scheduled
completion date, financial expenditure and present status.

The exact downloaded fields, data date and source conditions must be
verified and recorded during data acquisition.

## Data Scope
The initial dataset focuses on projects listed by the Ministry of
Development of North Eastern Region. It is not a nationwide
representation of all Indian construction projects.

## Workflow
1. Inspect the public source.
2. Download the available Excel export.
3. Preserve the original file.
4. Register source details and access date.
5. Import the file into Power BI.
6. Profile data quality.
7. Apply documented transformations.
8. Validate the resulting dataset.
9. Save the processed data for Week 3.

## Folder Contents
- `data-sources/` — source register and selection rationale
- `data/raw/` — original source file, if redistribution is permitted
- `data/interim/` — intermediate files
- `data/processed/` — cleaned dataset for later weeks
- `power-query/` — transformation documentation and M code
- `scripts/` — supplementary validation scripts
- `validation/` — quality checks and before/after comparison
- `visuals/` — screenshots and workflow diagrams

## Data Integrity
Raw files must remain unchanged. All cleaning decisions must be
documented. Missing values must not be replaced with invented values.

## Handoff to Week 3
The processed dataset, data dictionary and validation notes will form
the input to the Week 3 data model and DAX calculations.

## Status
Update this section after the dataset has been downloaded, transformed
and validated.