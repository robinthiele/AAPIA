# Antigen-Avoidance-Prevents-Immune-Activation

RNA-Seq Analysis - Custom Code - Antigen avoidance prevents Mastcell-mediated immune activation and inflammation

This Repository is a Code availability-Supplement to "Plum, T. et al. Mast cells link immune sensing to antigen avoidance behavior. Nature xxx, xxx-xxx (2023)."

To replicate the the downstream RNA-Seq data analysis, raw countmatrices must be downloaded from the Gene Expresseion Omnibus (SuperSeries ID: GSE225054). Metadata are included in this repository.


Analysis is split into two RMarkdown scripts. 

"Tissue_specific_RNA-Seq_Analysis.Rmd" facilitates general DESeq2 differential gene expression analysis starting from raw counts. Further Gene set enrichment analysis via ClusterProfiler is computed and visualized. The script euqally works for the small intestine and stomach dataset (both part of the GSE225054 SuperSeries).

"Tissue_data_integration.Rmd" integrates both individual datasets by comparing log2FoldChanges of certain genes.
