# GSE164772_single-cell-mining-data
Here i aim to isolate the microglia clusters of interest from GSE164772 count data and to evaluate cluster specific comparison across Adult and Juvenile datasets

For the first markdown document, I used seurat to for preprocessing of the count data, generating PCs
and then UMAP clusters. we then find cluster specific markers across all clusters. we then filter only microglia population using subset(). and this would be saved as an input for trajectory analysis using monocle at the second markdown document.




Background of this datasest.
GSE164772 Dataset:
Mpeg+ and CD45+ cells were sorted and sequenced from 28 dpf (Adult) and 6 dpf (Juvenile) zebrafish. Zebrafishes are pooled for each sample, 
but 2 sequencing lanes are used for J
uvenile while 1 lane is used for adult zebrafish group.



