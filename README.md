# MAF-Compiler
Compile and filter MAFs for import into cBioPortal

This script first compiles then strips large genes with high false positives and olfactory receptors among other non-importable variants from VEP vcf2maf MAF files.
From the compiled file it strips and retains genes of interest and adds additional formatin suitable for import into cBioPortal. 
Note - if used on MAFs from clinical gene panels, dataframes 1 and 3 shouold be eliminated or highly modified. 
