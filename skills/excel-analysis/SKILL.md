---
name: excel-analysis
description: Analyze Excel workbooks and spreadsheet data. Use for .xlsx/.xls files, worksheets, formulas, pivot-style summaries, charts, financial models, tabular cleaning, anomaly detection, KPI analysis, and generating clear findings from spreadsheet data.
---

# Excel Analysis

Analyze spreadsheet data with attention to workbook structure, formulas, and business meaning.

## Workflow

1. Inspect workbook sheets, dimensions, headers, formulas, hidden sheets, merged cells, and data types.
2. Identify the analysis grain: row, account, transaction, period, customer, product, or another entity.
3. Clean data explicitly and preserve raw inputs.
4. Use formulas only when they are the right deliverable; use scripts/dataframes for repeatable analysis.
5. Cross-check totals, date ranges, nulls, duplicates, and outliers.
6. Summarize findings with assumptions, caveats, and reproducible steps.

## Tools

- Python: `pandas`, `openpyxl`, `xlrd` when needed for legacy `.xls`.
- Excel output: preserve formulas and formatting when editing an existing workbook.

## Guardrails

- Do not trust displayed values without checking formulas when accuracy matters.
- Do not overwrite source workbooks unless explicitly requested.
