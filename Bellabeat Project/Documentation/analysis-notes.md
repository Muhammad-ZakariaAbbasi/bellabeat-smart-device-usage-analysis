# Analysis Notes

## Workflow
The analysis was performed in Google Sheets. The repository documents the spreadsheet-based workflow and includes exported CSV files for reproducibility.

### Data preparation
- Reviewed the daily activity and sleep datasets.
- Identified three duplicate rows in the original sleep dataset.
- The cleaned sleep export contains 410 records.
- Kept original source files separate from the cleaned sleep export.
- Excluded spreadsheet helper/check columns from the cleaned analysis-ready CSV.

### Analysis and findings
The project presentation reports:
- Average sedentary time: 956 minutes (approximately 15.9 hours).
- Average steps: 8,319.
- Highest average steps: Tuesday (8,949) and Saturday (8,947).
- Lowest average steps: Sunday (7,627).
- Steps/calories correlation: r = 0.56.
- Sedentary minutes/sleep duration correlation: r = -0.60.
- Average time in bed: 458 minutes; average time asleep: 419 minutes.

## Interpretation cautions
Correlation does not demonstrate causation. The sample is small, dates from 2016, and lacks age and gender information. Findings should be validated against a larger, more recent customer dataset before making business decisions.
