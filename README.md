# Single-Cell RNA+ATACseq Analysis of B-Cell Lymphoma with SEACells

#### Motivation
B cell lymphomas are largely determined by the interplay between gene expression and chromatin accessibility. We seek to use SEACells in our BCL dataset to find regulatory elements in tumor B-cells

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
  - Description of file
* Unfiltered_RNA_to_Joint.ipynb
  - Description of file
* ATACMetacellsAnalysis.ipynb
  - Compute metacells for the ATAC data using SEACells
* Final_SEACell_ATAC_RNA_Integration.ipynb
  - Compute gene-peak correlations, find highly regulated genes, compute gene scores, calculate open peaks in metacells, and calculate gene accessibility

(Please see our notebooks for our output and results)

#### Data
* Links to any data files required to run our notebooks (including data files we created) can be found in the notebooks
* The dataset studied in this project is the Fresh Frozen Lymph Node with B-cell Lymphoma dataset from 10x Genomics
  - Name of file: link to file
