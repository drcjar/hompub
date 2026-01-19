# hompub

PubMed-based analysis of publications with Homerton University Hospital affiliations.

## Purpose
To quantify and visualise academic output for internal R&I reporting.

## Methods
- PubMed queried via NCBI Entrez API
- Affiliation-based filtering using `Homerton[AD]`
- Deduplication by PMID
- Year extracted from PubMed DP field

## Outputs
- Publications per year
- Top journals
- Aggregated counts only (no raw records committed)

## Governance
This repository contains **code only**. Raw data are generated locally and excluded from version control.
