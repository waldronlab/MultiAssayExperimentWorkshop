# Archived

This workshop is now moved to www.github.com/waldronlab/MultiAssayWorkshop

# Multi-omics data representation and analysis with MultiAssayExperiment

July 20, 2018
BiocNYC R/Bioconductor meet-up

Marcel Ramos and Levi Waldron

The MultiAssayExperiment software package provides for the coordinated representation of, storage of, and operation on multiple diverse genomics data. It integrates an open-ended set of single-assay data classes, while abstracting the complexity of back-end data objects through a sufficient set of data manipulation, extraction, and re-shaping methods to interface with most R/Bioconductor data analysis and visualization tools. This workshop will introduce the data class and essential operations on it, then will lead users through a complete workflow including construction and several statistical analyses of a multi-omics dataset.

To install the workshop dependencies on your own RStudio desktop (the first line installs experimental data packages not installed automatically by biocLite):

```
BiocManager::install(c("curatedTCGAData", "mirbase.db", "EnsDb.Hsapiens.v86"))
BiocManager::install("waldronlab/MultiAssayExperimentWorkshop")
```
