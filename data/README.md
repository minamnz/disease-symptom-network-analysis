# Input dataset: `rawData.csv`

The source dataset supplied with this university project is stored at **`../rawData.csv`** (repository root) so the original notebook can read it using `pd.read_csv("rawData.csv")`, provided the notebook is run from that working directory.

## Inspected schema

- **Rows:** 4,920 (including repeated rows)
- **Columns:** 18: `Disease`, `Symptom_1` through `Symptom_17`
- **Distinct diseases:** 41
- **Distinct non-placeholder symptoms:** 131
- **Distinct complete rows:** 304; repeated rows: 4,616
- Empty symptom slots are represented by the literal string `0` in the data. The notebook's preprocessing handles these placeholder values.

The dataset appears to be an educational disease/symptom table. The original source, license, and clinical representativeness have **not been independently verified**. Before publishing publicly, confirm that redistribution is permitted. The inspected columns do not contain direct patient identifiers, but the rows should not be interpreted as independent clinical encounters.

The source CSV is preserved exactly as supplied; the project's Python code is unchanged.
