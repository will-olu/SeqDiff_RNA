# Pipeline for differential gene expression analysis of RNA-Seq data. 
Based on experimental results from the Cavanaugh Lab at Loyola University Chicago.
Cavanaugh Lab Website: https://cavanaughlab.weebly.com

## FastQC for Quality Control
Download FastQC from https://www.bioinformatics.babraham.ac.uk/projects/download.html#fastqc
Drag and Drop files into FastQC to determine quality of data
If per base sequence content is uneven at the beginning this is due to primers and is okay.  You can cut this area out of the sequence, for this analysis we removed the first 10 bases.
If per sequence GC content is uneven, this is okay because the _Drosophila melanogaster_ genome has a GC bias
The sequence duplication levels may be high.  This is because RNA-Seq libraries contain transcripts of exons that occur at various frequencies. 
