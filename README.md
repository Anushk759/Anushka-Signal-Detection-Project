 Post-Marketing Drug Safety Signal Detection Using FAERS Data

 Overview

This independent portfolio project demonstrates a post-marketing pharmacovigilance signal detection workflow using publicly available data from the FDA Adverse Event Reporting System (FAERS).

The project evaluates the reporting pattern between CRESTOR (rosuvastatin) and pneumonia using disproportionality analysis and explores the relationship between clinical data management and pharmacovigilance workflows.

This is an independent educational/portfolio project and not an official regulatory safety assessment.**

 Objectives

- Analyze publicly available post-marketing adverse event data
- Assess FAERS data quality and reporting patterns
- Perform disproportionality analysis using PRR and ROR
- Interpret the results in a pharmacovigilance context
- Apply clinical data management concepts to safety data
- Demonstrate Python-based analysis of pharmacovigilance data

 Data Source

FDA Adverse Event Reporting System (FAERS)

The analysis uses the publicly available FAERS 2026 Q1 data extract.

Workflow

1. Data loading and preparation
2. Data quality assessment
3. Identification of the drug and adverse event of interest
4. Construction of a 2×2 contingency table
5. Proportional Reporting Ratio (PRR) calculation
6. Reporting Odds Ratio (ROR) calculation
7. Interpretation of the observed reporting pattern
8. Clinical and pharmacovigilance assessment

 Key Results

- PRR: 2.09
- ROR: 2.18

The observed association was treated as hypothesis-generating rather than a validated safety signal, because the number of co-reported cases did not meet the predefined minimum threshold used in the project.

 Clinical Data Management Component

The project also demonstrates the connection between clinical data management and pharmacovigilance through:

- Data quality assessment
- Structured safety-data handling
- CDISC SDTM conceptual mapping
- Data-flow considerations from clinical data management to pharmacovigilance
- Preparation of data for downstream safety analysis

 Tools & Skills

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Data Analysis
- Pharmacovigilance
- FAERS
- Disproportionality Analysis
- PRR
- ROR
- Clinical Data Management
- CDISC SDTM Concepts

Repository Contents

- Anushka_signal_detection.ipynb` — Python/Jupyter Notebook containing the analysis
- `Project_Report.pdf` — Detailed project report.

Disclaimer

This project is an independent educational/portfolio analysis based on publicly available pharmacovigilance data. The findings should not be interpreted as an official regulatory safety assessment, medical advice, or a confirmed pharmacovigilance signal.

 Author

Anushka Pal

MSc Biotechnology | Bioinformatics & Genomics | Clinical Data Management | Pharmacovigilance
