# GSE41586 Transcriptomics Analysis
## Project Description
This repository contains a Differential Gene Expression (DGE) analysis report using Python and PyDESeq2. The analysis was performed on the GSE41586 dataset to understand cellular responses during infection.
## Dataset
- **Dataset ID:** [GSE41586](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE41586)
- **Platform:** GPL570 [HG-U133_Plus_2] Affymetrix Human Genome U133 Plus 2.0 Array.
- **Samples:** Human host cells (HT29/Macrophages) responding to bacterial stress.
## Methods
The analysis was conducted using a computational approach integrated within the Google Colab environment, utilizing the Python programming language. The methodology is divided into the following steps:
1. Data Acquisition, the gene expression profile was retrieved from the NCBI Gene Expression Omnibus (GEO) database under the accession number GSE41586. The raw or processed data files were loaded into the environment for downstream analysis.
2. Data Preprocessing using Python libraries such as Pandas and NumPy, the dataset was cleaned and structured. This involved handling missing values, normalizing the expression levels (if required), and mapping probe IDs to their respective gene symbols.
3. Differential Expression Analysis to identify genes significantly affected by the experimental conditions, statistical filtering was applied. We calculated the log2 fold change (Log2FC) and p-values to distinguish between up-regulated and down-regulated genes.
4. Data Visualization performed using Matplotlib and Seaborn libraries. Key visualizations include:
   - Volcano Plots to illustrate the statistical significance and magnitude of gene expression changes.
   - Heatmaps to show the expression clusters across different samples or time points.
5. Environment: All scripts were executed in a cloud-based Jupyter notebook (Google Colab), ensuring reproducibility and efficient handling of the genomic data.
## Analysis Results
### Volcano Plot of Differential Gene Expression
<p align="center">
  <img src="volcano-plot" width="800">
  <br>
  <b>Figure 1:</b> Volcano Plot of Differential Gene Expression.
</p>
