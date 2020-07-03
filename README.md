# PhiLR
# Language: R
# Input: TXT
# Output: CSV
# Tested with: PluMA 1.1, R 4.0.0
# Dependencies: phyloseq_1.3.20, ape_5.4, philr_1.14.0

PluMA plugin to run PhiLR (Silverman et al, 2017)

The plugin takes as input a TXT file of keyword-value pairs, whitespace-delimited:

otufile: File that holds OTU abundances (TXT)
mapping: Mapping file for samples (TXT)
tree: Taxonomic tree (TRE)

The plugin will output correlations as a CSV file, holding a matrix where entry (i, j) represents the correlation between node i and node j.
