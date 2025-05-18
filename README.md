# benchmark_BatchCorrection
This is the repositories of the code and visualization for my benchmark of the batch correction tools in the scRNA-seq field. Harmony, Seurat V5 integration and BBKNN is used in this study. 
You can find all the code from the "final_pipeline" and the visualization from the "Figure"

<br>
239T_Jurkat dataset of the first task:
<br>
support.10xgenomics.com/single-cell-gene-expression/datasets/1.1.0/jurkat
<br>
support.10xgenomics.com/single-cell-gene-expression/datasets/1.1.0/293t
<br>
support.10xgenomics.com/single-cell-gene-expression/datasets/1.1.0/jurkat:293t_50:50
<br>
<br>
Panc8 dataset of the second task:
<br>
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE81076
<br>
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE85241
<br>
<br>
Cross-species dataset:
<br>
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE84133

<br><br>
Due to the limited space in the main paper, the original picture in the papers have to be put here.
***
### The result of each tool on 239T_Jurkat dataset

<div align="center">
  <img src="Figure/UMAP_5050_raw_label.png" width="80%"><br>
  <em>Raw data UMAP result of 239T_Jurkat</em><br><br>

  <img src="Figure/UMAP_5050_Harmony_label.png" width="80%"><br>
  <em>Harmony UMAP result of 239T_Jurkat</em><br><br>

  <img src="Figure/UMAP_5050_Seurat_label.png" width="80%"><br>
  <em>Seurat UMAP result of 239T_Jurkat</em><br><br>

  <img src="Figure/UMAP_5050_BBKNN_label.png" width="80%"><br>
  <em>BBKNN UMAP result of 239T_Jurkat</em>
</div>

<br><br>

***

### The result of each tool on panc8 dataset

<div align="center">
  <img src="Figure/UMAP_panc8_raw.png" width="80%"><br>
  <em>Raw data UMAP result of panc8</em><br><br>

  <img src="Figure/UMAP_panc8_Harmony_label.png" width="80%"><br>
  <em>Harmony UMAP result of panc8</em><br><br>

  <img src="Figure/UMAP_panc8_Seurat.png" width="80%"><br>
  <em>Seurat UMAP result of panc8</em><br><br>

  <img src="Figure/UMAP_panc8_BBKNN_label.png" width="80%"><br>
  <em>BBKNN UMAP result of panc8</em>
</div>

<br><br>

***

### The result of each tool on cross-species dataset

<div align="center">
  <img src="Figure/UMAP_Cross_species_raw.png" width="80%"><br>
  <em>Raw data UMAP result of cross-species dataset</em><br><br>

  <img src="Figure/UMAP_Cross_species_Harmony.png" width="80%"><br>
  <em>Harmony UMAP result of cross-species dataset</em><br><br>

  <img src="Figure/UMAP_Cross_species_Seurat.png" width="80%"><br>
  <em>Seurat CCA UMAP result of cross-species dataset</em><br><br>

  <img src="Figure/UMAP_Cross_species_Seurat_RPCA.png" width="80%"><br>
  <em>Seurat RPCA UMAP result of cross-species dataset</em>
</div>



