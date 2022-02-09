Tumor-infiltrating NK cell subsets associated with the magnitude of T cell response in human lung cancer
------------

This repository contains the scripts used to analyze our samples from human lung cancer focused on NK cells.
The data contains RNA-seq samples from bulk and single-cell.

REQUIREMENTS
------------

This project requires the following modules/programs:

* TopHat (v1.4.1)
* HTSeq (v0.7.1)
* Cutadapt (v1.3)
* [DESeq2](https://bioconductor.org/packages/release/bioc/html/DESeq2.html) (v.1.14.1)
* fastcluster (v.1.1.25)
* dendextend (v.1.7.0)
* [Cell Ranger](https://support.10xgenomics.com/single-cell-gene-expression/software/pipelines/latest/what-is-cell-ranger) (v2.0.2)
* [Seurat](https://satijalab.org/seurat) (v2.1)
* [MAST](https://www.bioconductor.org/packages/release/bioc/html/MAST.html)

INSTALLATION
------------

* You can follow the instructions for [our mapping pipeline](https://github.com/vijaybioinfo/cellranger_wrappeR) using Cell Ranger.
* For the single-cell quality control just pull [our in-house script](https://github.com/vijaybioinfo/quality_control).
* Clustering of single-cell data with [our pipeline](https://github.com/vijaybioinfo/clustering) using Seurat.

Global description
------------

*Demultiplexing libraries*: Cell Ranger was used to demultiplex the 10x libraries. And our in-house
mapping [pipeline](https://github.com/ndu-UCSD/LJI_RNA_SEQ_PIPELINE_V2) was used for the bulk data.

*Quality control*: An in-house [script](https://github.com/vijaybioinfo/quality_control)
was used to explore the quality of the data and select the thresholds.

*Clustering*: Seurat was used to cluster the data.

For more specific information about the data generation and processing, please check the methods.

MAINTAINERS
-----------

Current maintainers:
* Ciro Ramírez-Suástegui (ksuasteguic@gmail.com, ciro@lji.org)

Contact
-----------
Please email Ciro Ramírez-Suástegui (ciro@lji.org) and Vijayanand Pandurangan (vijay@lji.org).
