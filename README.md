[![DOI](https://zenodo.org/badge/369344312.svg)](https://zenodo.org/badge/latestdoi/369344312)
# gemberling-et-al-NMETH-A42509C

This is repository is intented to serve as a record of all the data processing steps and analyses performed in the manuscript NMETH-A42509C by Gemberling et al. Please contact the authors if there are sections in any particular notebook that are unclear or that could use more color. A brief defintion of the contents of each notebook is provided below: 

### RNA-seq related notebooks:
- [Heaton_6594_201110A5.ipynb](Heaton_6594_201110A5.ipynb): Processing pipeline of 2 libraries that needed to be re-done.
- [Siklenka_6563_201007A5.ipynb](Siklenka_6563_201007A5.ipynb): Processing pipeline of Cre+ and Cre- mouse libraries with a non-targeting control (NTC) and targeting FoxP3 (g5) guide RNAs. 
- [genewiz_rnaseq.ipynb](genewiz_rnaseq.ipynb): Processing pipeline for liver samples of dCas9-KRAB and dCas9-p300core mouse with a non-targeting control (NTC) and targeting Pdx1 and guides, in addition to PBS treated cells. 
- [rnaseq.cre_neg_g5.demultiplex_miseq.ipynb](rnaseq.cre_neg_g5.demultiplex_miseq.ipynb): demultiplex samples from validation run.
- [rnaseq.differential_gene_expression.ipynb](rnaseq.differential_gene_expression.ipynb): Differential gene expression analyses.
- [rnaseq.novogene_pcks9.ipynb](rnaseq.novogene_pcks9.ipynb): Differential gene expression analyses of Pcsk9 transmice data.
### ChIP-seq related notebooks:
- [Siklenka_6621_201109A5.ipynb](Siklenka_6621_201109A5.ipynb): Processing pipeline of H3K27ac histone mark data for Cre+ and Cre- mouse libraries with a non-targeting control (NTC) and targeting FoxP3 (g5) guide RNAs. 
- [chipseq.differential_binding.ipynb](chipseq.differential_binding.ipynb): Differential binding analysis for H3K27me3 and H3K27ac deposition in transgenic mouse samples targeting dCas9-KRAB to Pcsk9 and dCas9-p300core to Pdx1 promoters respectively.
- [chipseq.qc.ipynb](chipseq.qc.ipynb): Spearman correlation heatmap used for QC purposes.
- [chipseq.quantify_reads_in_peaks.KRAB.ipynb](chipseq.quantify_reads_in_peaks.KRAB.ipynb): Quantification of ChIP-seq signal for dCas9-KRAB samples.
- [chipseq.quantify_reads_in_peaks.p300.ipynb](chipseq.quantify_reads_in_peaks.p300.ipynb: Quantification of ChIP-seq signal for dCas9-p300core samples.
- [remove_reads_from_another_fastq.ipynb](remove_reads_from_another_fastq.ipynb): Clean up a demultiplexing issue with some other libraries sequenced together.

### RNA- and ChIP-seq related notebooks
- [integrative.p300.proximity_analysis.ipynb](integrative.p300.proximity_analysis.ipynb): Integrative analysis for ChIP-seq differential binding and differential expression of closest gene, for Cre+ and Cre- mouse libraries with a non-targeting control (NTC) and targeting FoxP3 (g5) guide RNAs. 
- [integrative.p300_pdx1_pcsk9.proximity_analysis.ipynb](integrative.p300_pdx1_pcsk9.proximity_analysis.ipynb): Integrative analysis for ChIP-seq differential binding and differential expression of closest gene, for liver samples of dCas9-KRAB and dCas9-p300core mouse with a non-targeting control (NTC) and targeting Pdx1 and guides, in addition to PBS treated cells.
- [trackhub.ipynb](trackhub.ipynb): Creation of UCSC Genome Browser trackhub to access the data.
