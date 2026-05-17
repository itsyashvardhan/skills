---
name: spreadsheet-automation
description: Automate spreadsheet workflows across Excel, CSV, and workbook files. Use for repeatable data cleaning, workbook generation, formula insertion, sheet splitting, report refreshes, table formatting, imports, exports, and batch spreadsheet operations.
---

# Spreadsheet Automation

Build repeatable spreadsheet workflows that can be rerun safely.

## Workflow

1. Identify source files, destination files, and the exact transformation.
2. Preserve raw inputs and write outputs to new files unless instructed otherwise.
3. Normalize headers and data types before transformations.
4. Keep business rules explicit in code or a clearly named configuration section.
5. Generate deterministic outputs with stable sheet names, table names, and file names.
6. Validate row counts, totals, required columns, formulas, and expected sheets.

## Implementation Notes

- Use `pandas` for data transformations.
- Use `openpyxl` or equivalent libraries for Excel formatting, formulas, and workbook structure.
- Use CSV only when workbook features such as formulas, styles, and multiple sheets are not needed.
