# Collated VB Report — Two-Source Reporting Automation

A browser-based utility for combining two raw reporting exports into one standardized output, reducing repetitive spreadsheet reconciliation.

## Why I built it

A recurring operational report required information from two sources. Preparing it manually involved lookups, duplicate removal, and repeated formatting in Excel. I wanted a repeatable workflow that other team members could use.

## Workflow

1. Obtain the two required raw exports from their original sources.
2. Open `index.html` and upload each file through its corresponding input.
3. Use the merge/download action to generate the standardized output.
4. Review the generated report for data quality before sharing or using it.

## Outcome

For the workflow this tool was designed for, manual report preparation typically took **20–25 minutes**. After the input exports were available, the merge and export step took **under 30 seconds**.

These durations compare manual preparation with the automated processing step; they do not include downloading files from upstream systems.

## Product value

- Reduces repeated manual lookup and deduplication work.
- Makes the report format consistent across reporting cycles.
- Enables a self-service process instead of reconstructing the same Excel workflow.
- Illustrates operational problem discovery translated into a reusable internal tool.

## Repository contents

- `index.html` — reporting and reconciliation interface.

## Responsible use

Input file formats must match those expected by the tool. Validate the output against its source systems before using it for decisions. Use **synthetic or explicitly authorized anonymized data** for public demos; do not commit real customer information, private reports, credentials, or other confidential information.
