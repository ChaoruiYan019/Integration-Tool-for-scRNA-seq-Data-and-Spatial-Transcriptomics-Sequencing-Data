# Integration-Tool-for-scRNA-seq-Data-and-Spatial-Transcriptomics-Sequencing-Data
Integration Tool for scRNA-seq Data and Spatial Transcriptomics Sequencing Data

## Citation

## Contents

- [Citation](#citation)
- [Contents](#contents)
- [Tools](#tools)
  - [Deconvolution](#deconvolution)
      - [SPOTLight](#spotlight)
      - [Cell2location](#cell2location)
      - [SD2](#sd2)
      - [SpatialDWLS](#spatialdwls)
      - [Stereoscope](#stereoscope)
      - [RCTD](#rctd)
      - [STRIDE](#stride)
      - [DSTG](#dstg)
      - [CellDART](#celldart)   
  - [Mapping](#mapping)
      - [MIA](#mia)
      - [AddModuleScore](#addmodulescore)
      - [Tangram](#tangram)
      - [Harmony](#harmony)
      - [pciSeq](#pciseq)
      - [LIGER](#liger)
      - [SpaGE](#spage)
      - [gimVI](#gimvi)
      - [stPlus](#stplus)
      - [CeLEry](#celery)

## Tools

### Deconvolution

- [SPOTLight](https://github.com/MarcElosua/SPOTlight_deconvolution_analysis) - Performs well even with small cell datasets
- [Cell2location](https://github.com/BayraktarLab/cell2location) - Allows joint analysis of multiple single-cell and spatial transcriptomic data with high accuracy, regardless of cell abundance
- [SD2](https://github.com/leihouyeung/SD2) - Including dropout data as valid input data can provide more convincing biological information
- [SpatialDWLS](https://github.com/RubD/Giotto) - Possesses high computing efficiency
- [Stereoscope](https://github.com/almaan/stereoscope) - Using similar organizations of scRNA-seq data and spatial transcriptomic sequencing data is possible, without requiring the pairing of these two types of data
- [RCTD](https://github.com/dmcable/spacexr) - Considering platform effects, cross-platform learning can be achieved
- [STRIDE](https://github.com/wanglabtongji/STRIDE) - Can be used for integrating serial sectioned tissues and reconstructing the three-dimensional structure of tissues
- [DSTG](https://github.com/Su-informatics-lab/DSTG) - Due to inherent algorithmic differences, spatial transcriptomics sequencing data and scRNA-seq data may not be compatible
- [CellDART](https://github.com/mexchy1000/CellDART) - Better than most existing integration methods in terms of spatial localization of multiple subtypes of excitatory neurons

### Mapping

- [MIA](https://github.com/reubenmoncada/Multimodal-intersection-analysis-MIA-) - Good performance in the localization of cell types in cross-tissue regions
- [AddModuleScore](https://github.com/WalterMuskovic/AddModuleScore) - Focusing on scoring selected genes
- [Tangram](https://github.com/broadinstitute/Tangram) - Detect conserved cell type patterns across species
- [Harmony](https://github.com/WalterMuskovic/AddModuleScore) - Requires less computing resources
- [pciSeq](https://github.com/acycliq/pciSeq) - Requires only low-magnification imaging
- [LIGER](https://github.com/welch-lab/liger) - Suitable for large-scale datasets, with consideration of platform effects
- [SpaGE](https://github.com/tabdelaal/SpaGE) - Adapts to large-scale datasets, considering platform effects. It has interpretability, high predictive accuracy for HVGs, and does not require high computer resources
- [gimVI](https://github.com/scverse/scvi-tools) - Efficient gene expression data imputation and integration capability
- [stPlus](https://github.com/xy-chen16/stPlus) - Can be applied to large-scale datasets
- [CeLEry](https://github.com/QihuangZhang/CeLEry) - Consider the sample size challenge inherent in spatial transcriptomics datasets and provide a dedicated method for generating test set samples to enhance performance
