# Single-Cell RNA+ATACseq Analysis of B-Cell Lymphoma with SEACells

#### Motivation
B-cell lymphomas are largely determined by the interplay between gene expression and chromatin accessibility. We seek to find regulatory elements tumor B-cells and healthy B-cells in our dataset by integrating rna and atac-seq data using the metacell method SEACells to deal with the sparsity of single cell data


#### Dependencies
* SEACells (requires Python3.8 or above)
* Scanpy
* ArchR
* seaborn
* numpy
* pandas
* matplotlib

#### Notebook Descriptions
* ArchR.Rmd
  - Preprocess scATAC-seq data and export peak counts matrix and metadata for analysis in Python
* Unfiltered_RNA_to_Joint.ipynb
  - Subset scRNA-seq dataset, basic preprocessing and exploratory data analysis, differential gene expression analysis, and cell type annotations.
* ATACMetacellsAnalysis.ipynb
  - Compute metacells for the ATAC data using SEACells
* Final_SEACell_ATAC_RNA_Integration.ipynb
  - Compute gene-peak correlations, find highly regulated genes, compute gene scores, calculate open peaks in metacells, and calculate gene accessibility

(Please see our notebooks for our output and results)

#### Data
* Links to any data files required to run our notebooks (including data files we created) can be found in the notebooks
* The dataset studied in this project is the Fresh Frozen Lymph Node with B-cell Lymphoma dataset from 10x Genomics (link: https://www.10xgenomics.com/resources/datasets/fresh-frozen-lymph-node-with-b-cell-lymphoma-14-k-sorted-nuclei-1-standard-2-0-0)
  - RNA dataset download name: Raw feature barcode matrix (HDF5)
  - ATAC dataset download name: ATAC Per fragment information file (TSV.GZ)
