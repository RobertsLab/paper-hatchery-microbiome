gannet/Atumefaciens/20200618_metagenomics_megan_tables

# P.generosa metagenomic data extraction using MEGAN6

# All files are tab-delimited.

# All files were generated using the "summarized" option when exporting, meaning
that the all the reads at and below the terminal taxonomic class were summed to generate the counts.

# File are named in the following manners:

PREFIXES:

- abs-reads_abs-comparison_: Files were imported using absolute read counts and comparison was run using absolute read counts.

- abs-reads-ind-samples_: Files were imported using absolute read counts and individual samples were analyzed.

ROOTS:

- _day_: Data is grouped by day.

- _pH_: Data is grouped by pH.

SUFFIXES:

- interpro2go: Gene ontology assignments.

- reads: Read counts.

- PathToCount: Shows full "path" (either GO terms or taxonomy) leading to,
and including, the terminal term and corresponding summarized counts (i.e.
sum of all reads at terminal term and all below that term) of reads assigned
to the terminal term.

- PathToPercent: Shows full "path" (either GO terms or taxonomy) leading to,
and including, the terminal term and corresponding percentage of summarized counts (i.e.
sum of all reads at terminal term and all below that term) of reads assigned
to the terminal term. This is percentage of all reads assigned within the designated group/sample.
It is NOT a percentage of all reads in the entire experiment!!


FILES
---

abs-reads_abs-comparison_day_interpro2goPathToCount.txt: See above.

abs-reads_abs-comparison_day_interpro2goPathToPercent.txt: See above.

abs-reads_abs-comparison_Day.megan: MEGAN6 comparison file, compared by "Day".

abs-reads_abs-comparison_day_readsTaxonPathToCount.txt: See above.

abs-reads_abs-comparison_day_readsTaxonPathToPercent.txt: See above.

abs-reads_abs-comparison_pH_interpro2goPathToCount.txt: See above.

abs-reads_abs-comparison_pH_interpro2goPathToPercent.txt: See above.

abs-reads_abs-comparison_pH.megan: MEGAN6 comparison file, compared by "pH".

abs-reads_abs-comparison_pH_readsTaxonPathToCount.txt: See above.

abs-reads_abs-comparison_pH_readsTaxonPathToPercent.txt: See above.


megan_log.txt: MEGAN6 log file that documents data import/export/selection process.
