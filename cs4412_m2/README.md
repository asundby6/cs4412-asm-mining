# Alec Sundby - Kennesaw State University

# CS 4412 — Unsupervised Detection of Attack Surface Drift

## Project Description
Applying unsupervised data mining to Attack Surface Management using the LANL Cyber Security Dataset. The pipeline uses PCA for dimensionality reduction, DBSCAN for behavioral clustering, and Isolation Forest for anomaly scoring.

## Dataset
LANL Comprehensive Multi-Source Cyber-Security Events
Available at: https://csr.lanl.gov/data/cyber1/
Due to file size constraints, auth.txt.gz is not included in this repository.
The notebook uses a representative sample constructed to mirror the behavioral structure of the authentication logs.

## Repository Structure
- docs / project proposal and milestone reports
- notebooks / Jupyter notebooks
- data / data directory (large files excluded for now)

## Milestones
- M1: Project proposal
- M2: Initial implementation — EDA, preprocessing, PCA + DBSCAN clustering
- M3: Anomaly scoring — Isolation Forest, concept drift analysis (upcoming)
