# Committed dataset

**Source dataset:** UCI Online Retail

**Selection:** Complete workbook observations from all sheets, preserving sheet/source order and split into CSV files below GitHub's file-size limit.

**Data license:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). This applies to the data, independently of the project code.

## Sources

- https://archive.ics.uci.edu/dataset/352/online+retail

## CSV files

| File | Rows | Bytes |
|---|---:|---:|
| [retail_sheet1_001.csv](raw/retail_sheet1_001.csv) | 100,000 | 8,672,626 |
| [retail_sheet1_002.csv](raw/retail_sheet1_002.csv) | 100,000 | 8,698,948 |
| [retail_sheet1_003.csv](raw/retail_sheet1_003.csv) | 100,000 | 8,671,075 |
| [retail_sheet1_004.csv](raw/retail_sheet1_004.csv) | 100,000 | 8,742,785 |
| [retail_sheet1_005.csv](raw/retail_sheet1_005.csv) | 100,000 | 8,775,544 |
| [retail_sheet1_006.csv](raw/retail_sheet1_006.csv) | 41,909 | 3,656,494 |

Attribution: Daqing Chen / UCI Machine Learning Repository. XLSX converted to CSV with source column names and values; datetimes use an ISO-like textual representation and empty cells remain empty. Cancellation/return records and missing customer identifiers are retained for the future data audit. These are recorded sales, not observations of unconstrained demand.

The CSV files contain published observations or their documented format conversion; no training records were invented. Source formats and raw CSV exports are distinguished by the manifest. File checksums and schemas are recorded in [csv-manifest.json](csv-manifest.json).
