# Heatmap-Code
Code for making a heatmap with RNA seq data

Code taken with slight edits from: https://github.com/mousepixels/sanbomics_scripts/blob/main/PyDeseq2_DE_tutorial.ipynb

1. Droppednamesthreshrawcounts.csv is a file of Genes and their RNA counts taken from this paper: https://journals.asm.org/doi/10.1128/iai.00814-20.
2. Titles represent whether a mouse sample was either a control or an infected sample, with the 3 or 14 representing the days post-experiment start for the mice.
3. This file was generated from the original files that the researchers created; each sample was separate in those files.
4. This file was also run through data cleaning, code for that is in CreatingCleanRNADataset.ipynb.
5. Original files, for those who want to start at the beginning and create these heatmaps, are all in the RawSeqCounts folder.
