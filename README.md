# gutmicrobiome_pharmacology
Supplementary data, figures, and code for a computational microbiome pharmacology study identifying gut microbiome metabolites with regorafenib-like transcriptional signatures in colorectal cancer.

# Supplementary material for:
A Systems Biology Framework Links Gut Microbiome Metabolites to Regorafenib-Associated Transcriptional Programs in Colorectal Cancer

This repository contains supplementary tables, supplementary figures, derived data, and code associated with the manuscript.

## Code availability
Analysis scripts are provided in the `code/` directory. Public datasets used in this study are available from IBDMDB and LINCS as described in the manuscript.

## Supplementary tables
- Table S1a: Top regorafenib-concordant metabolites
- Table S1b: Top regorafenib-opposing metabolites
- Table S2a: KEGG pathway enrichment results for regorafenib-concordant metabolites
- Table S2b: KEGG pathway enrichment results for regorafenib-opposing metabolites
- Table S3: β-glucuronidase annotation of regorafenib-associated taxa
- Table S4: Overlap of top-ranked regorafenib-concordant metabolites between baseline and longitudinal metabolite profiles
- Table S5: Longitudinal sensitivity results for experimentally tested metabolites
- Table S6a: Survival analysis results for genes associated with regorafenib-concordant metabolites
- Table S6b: Survival analysis results for genes associated with regorafenib-opposing metabolites
- Table S7: Concentration-dependent viability effects of framework-prioritised metabolites in CRC cells

See the README within the `supplementary_tables/` directory for file-level descriptions.

## Supplementary figures
- Figure S1a: Baseline versus longitudinal consensus regorafenib mimic scores
- Figure S1b: Regorafenib mimic scores for experimentally tested metabolites
- Figure S2: Kaplan-Meier survival analysis for HIST1H2AC

## Derived data

Machine-readable derived datasets underlying the reported analyses are provided in the `derived_data/` directory, including:

- regorafenib_metabolite_concordance_scores.csv
- prioritised_metabolites.csv
- pathway_enrichment_results_regorafenib-concordant.csv
- pathway_enrichment_results_regorafenib-opposing.csv
- longitudinal_sensitivity_scores.csv
- survival_analysis_results.csv
- cell_viability_results.xlsx

These files contain analysis outputs derived from the publicly available source datasets and are provided to facilitate reproducibility and reuse.

Large intermediate gene-metabolite correlation matrices are not included in the repository because of file size. These matrices can be regenerated from the publicly available source data using the analysis code provided in this repository.
