# BuildSight BI
### Construction Business Intelligence and Analytics Platform

BuildSight BI is a progressive business intelligence project focused on
analysing publicly available infrastructure and construction-related
project data. The project uses Microsoft Power BI for data modelling,
KPI development and interactive analytics, with a companion Streamlit
website planned for presenting selected project insights.

> **Project status:** In progress
> **Internship:** Virtual Construction Business Intelligence Intern
> **Duration:** 6 weeks
> **Author:** Shalvi Atul Surve

---

## 1. Problem Statement

Construction and infrastructure projects involve multiple performance
dimensions, including cost, expenditure, schedule and project status.
When these indicators are spread across different records or reports,
it can be difficult to obtain a consolidated view of project performance.

BuildSight BI aims to create a documented and reproducible analytical
workflow that transforms publicly available project information into
structured data, measurable KPIs and accessible visual insights.

The project uses public data only. It does not use confidential or
proprietary construction-company datasets.

## 2. Project Objectives

- Identify public datasets relevant to construction and infrastructure
  project monitoring.
- Import, inspect, clean and transform data using Power BI and Power Query.
- Develop a documented data model and reusable KPI calculations.
- Design interactive Power BI dashboards.
- Explore predictive analytics where the selected data supports it.
- Evaluate the analytical workflow and communicate its limitations.
- Develop a companion website using the repository's processed outputs.

## 3. Core Use Cases

1. **Project Performance:** Examine project status and scheduled timelines.
2. **Cost Analytics:** Compare approved cost and reported expenditure.
3. **Schedule Analysis:** Identify projects with relevant date or schedule
   information.
4. **Sector and Regional Analysis:** Compare projects across available
   sectors and locations.
5. **Risk Exploration:** Explore indicators associated with potential
   project risks, subject to data availability.

The final scope of each use case depends on the fields available in the
selected public dataset.

## 4. Technology Stack

- Microsoft Power BI
- Power Query
- DAX
- Python
- Pandas
- Streamlit
- Plotly
- Git and GitHub

## 5. Repository Structure

- `docs/` — project documentation, architecture and methodology.
- `reports/` — formal weekly Word submissions.
- `week-1-strategic-planning/` — project strategy and KPI framework.
- `week-2_data-sourcing-and-preparation/` — source register, data
  preparation and validation.
- `week-3_data-modelling-and-dax/` — data model and calculations.
- `week-4_dashboard-design/` — dashboard design and Power BI artefacts.
- `week-5_predictive-analytics/` — predictive methodology and outputs.
- `week-6_final-evaluation/` — final assessment and recommendations.
- `website/` — Streamlit companion application.
- `shared/` — reusable definitions and website-ready outputs.

## 6. Weekly Progress

| Week | Focus | Status |
|---|---|---|
| 1 | Strategic Planning | Report prepared |
| 2 | Data Sourcing and Preparation | In progress |
| 3 | Data Modelling and DAX | Not started |
| 4 | Interactive Dashboard | Not started |
| 5 | Predictive Analytics | Not started |
| 6 | Final Evaluation and Website | Not started |

## 7. Data Sources

The project prioritises publicly accessible sources. Each source will be
recorded with its publisher, URL, access date, available fields and
limitations.

The selected Week 2 dataset and its download instructions will be
documented in:

`week-2_data-sourcing-and-preparation/data-sources/`

## 8. Getting Started

Create and activate the project environment:
```bash
python -m venv .venv
```

# Windows PowerShell
```bash
.venv\Scripts\Activate.ps1
```

# Install dependencies
```bash
pip install -r requirements.txt
```
