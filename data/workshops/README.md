# Workshop Data

> Qualitative data collected through stakeholder workshops, supplementing the on-chain quantitative metrics.

## Overview

This folder contains structured exports from governance workshops conducted as part of the Beyond MVG research initiative. Each workshop session has its own dated subfolder containing raw data, visuals, and source links.

## Folder Structure

```
workshops/
  YYYY-MM-DD-<topic>/          # One folder per workshop session
    README.md                  # Workshop metadata and summary
    raw-data/                  # CSV exports from Google Sheets
    visuals/                   # Exported images/PDFs from Miro boards
    sources.md                 # Links to original Google Sheets and Miro boards
```

## Data Index

| ID | Topic | Data Types | Folder |
|----|-------|-----------|--------|
| MS2 | Aggregated Workshops, Surveys & Interviews | 9 surveys, 5 interview sets, 4 workshop sessions, 7 Miro boards | [`ms2-workshops-surveys-interviews/`](ms2-workshops-surveys-interviews/) |

### Template

Use [`YYYY-MM-DD-topic/`](YYYY-MM-DD-topic/) as a template when adding new workshop data.

## Schema for Agent Consumption

Each workshop `README.md` contains YAML front matter with structured metadata:

```yaml
---
type: workshop
date: YYYY-MM-DD
topic: "<Workshop topic>"
participants: <number>
facilitator: "<Name>"
metrics_covered:
  - "M3-X-X Metric name"
tags:
  - governance
  - qualitative
data_formats:
  - csv
  - png
---
```

Agents can parse these front matter blocks to discover, filter, and cross-reference workshop data with on-chain metrics in `../On-chain-measurements-epoch-537-609/`.

## Data Conventions

- **Raw data**: Export Google Sheets as `.csv` (UTF-8 encoding). One CSV per sheet/tab. Keep the original sheet name in the filename.
- **Visuals**: Export Miro boards as `.png` (for quick viewing) or `.pdf` (for print quality). Use descriptive filenames.
- **Sources**: Always record the original Google Sheet and Miro board URLs in `sources.md` so data provenance is traceable.
- **Naming**: Use lowercase kebab-case for folder names: `YYYY-MM-DD-short-topic-description`
