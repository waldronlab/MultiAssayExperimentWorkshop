# Multi-omics data representation and analysis with MultiAssayExperiment

Nov 16, 2017
Weill Cornell Medical College Applied Bioinformatics Core d:bug

Marcel Ramos and Levi Waldron

The MultiAssayExperiment software package provides for the coordinated representation of, storage of, and operation on multiple diverse genomics data. It integrates an open-ended set of single-assay data classes, while abstracting the complexity of back-end data objects through a sufficient set of data manipulation, extraction, and re-shaping methods to interface with most R/Bioconductor data analysis and visualization tools. This workshop will introduce the data class and essential operations on it, then will lead users through a complete workflow including construction and several statistical analyses of a multi-omics dataset.

To install the workshop dependencies on your own RStudio desktop (may not actually install dependencies):

    > BiocInstaller::biocLite("waldronlab/MultiAssayExperimentWorkshop",dependencies=TRUE, build_vignettes=TRUE)

Customized MultiAssayExperiment objects built for The Cancer Genome Atlas:

    > library(curatedTCGAData)

Here are associated [slides](https://github.com/waldronlab/MultiAssayExperimentWorkshop/blob/master/MultiAssayExperimentWorkshop_slides.pptx?raw=true) presented at the start of this workshop.
