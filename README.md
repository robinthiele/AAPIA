# Mastcell-Avoidance-Prevents-Immune-Activation
RNA-Seq Analysis - Antigen avoidance prevents Mastcell derived immune activation and inflammation

To replicate the entire analysis, raw countmatrices must be downloaded from the Gene Expresseion Omnibus (SuperSeries ID: GSE225054). Metadata are included in this repository.


Analysis is split into two scripts. 

"Tissue_specific_RNA-Seq_Analysis.Rmd" facilitates general DESeq2 differential gene expression analysis starting from raw counts. Further Gene set enrichment analysis via ClusterProfiler is computed and visualized. The script euqally works for the small intestine and stomach dataset (both part of the SuperSeries).

"Tissue_data_integration.Rmd" integrates both individual datasets by comparing log2FoldChanges of certain genes.
