# Dimensionality-Reduction-and-Clustering-Methods-for-Single-cell-and-Spatial-Transcriptomics-Data
Dimensionality Reduction and Clustering Methods for Single-cell and Spatial Transcriptomics Data

## Citation

## Contents

- [Citation](#citation)
- [Contents](#contents)
- [Dimensionality Reduction Methods](#tools)
  - [Single Cell Transcriptomics](#deconvolution)
    - [PCA](#spotlight)
    - [NMF](#spotlight)
    - [scvis](#spotlight)
    - [UMAP](#spotlight)
    - [tGPLVM](#spotlight)
    - [DR-A](#spotlight)
    - [SCDRHA](#spotlight)
    - [MulitiMAP](#spotlight)
    - [DREAM](#spotlight)
  - [Spatial Transcriptomics](#deconvolution)
    - [Seurat](#spotlight)
    - [SCANPY](#spotlight)
    - [SpatialPCA](#spotlight)
- [Clustering Methods](#tools)
  - [Single Cell Transcriptomics](#deconvolution)
    - [CellBIC](#spotlight)
    - [HMRF](#spotlight)
    - [SAME-clustering](#spotlight)
    - [SPRESSO](#spotlight)
    - [Metacell](#spotlight)
    - [Leiden](#spotlight)
    - [stLearn](#spotlight)
    - [jSRC](#spotlight)
    - [Metacell2](#spotlight)
    - [scHFC](#spotlight)
    - [eSPRESSO](#spotlight)
  - [Spatial Transcriptomics](#deconvolution)
    - [spatialDE](#spotlight)
    - [spaGCN](#spotlight)
    - [BayesSpace](#spotlight)
    - [Banksy](#spotlight)
    - [STAGATE](#spotlight)
    - [Stardust](#spotlight)
    - [DR-SC](#spotlight)
    - [GraphST](#spotlight)
    - [ADEPT](#spotlight)
   
## Dimensionality Reduction Methods

### Single Cell Transcriptomics

- [PCA](https://github.com/erdogant/pca) - Simplified with significant dimensionality reduction effects
- [NMF](https://github.com/renozao/NMF) - Utilizing non-negative decomposition is more applicable to biological data
- [scvis](https://github.com/erdogant/pca) - Simplified with significant dimensionality reduction effects
- [UMAP](https://github.com/erdogant/pca) - Simplified with significant dimensionality reduction effects
- [tGPLVM](https://github.com/architverma1/tGPLVM) - Can be used for raw, unfiltered data
- [DR-A](https://github.com/eugenelin1/DRA) - Utilizing deep learning models to enhance dimensionality reduction performance
- [SCDRHA](https://github.com/WHY-17/SCDRHA) - The composite structure is capable of simultaneously avoiding dropout events and preserving cellular topological structure
- [MulitiMAP](https://github.com/Teichlab/MultiMAP) - Able to integrate and analyze data of different quantities and dimensions
- [DREAM](https://github.com/Crystal-JJ/DREAM) - Strong stability in dimensionality reduction and suitable for pseudo-temporal analysis

### Spatial Transcriptomics

- [Seurat](https://github.com/satijalab/seurat) - Applicable to different types of single-cell transcriptomic data
- [SCANPY](https://github.com/scverse/scanpy) - Suitable for handling large-scale single-cell data
- [SpatialPCA](https://github.com/shangll123/SpatialPCA) - Able to preserve crucial biological signals and spatial structures while reducing dimensionality

## Clustering Methods

### Single Cell Transcriptomics

- [CellBIC](https://github.com/neocaleb/CellBIC) - Top-down hierarchical
- [HMRF](https://bitbucket.org/qzhudfci/smfishhmrf-py) - Identifies varied spatial domain patterns
- [SAME-clustering](https://github.com/yycunc/SAMEclustering) - Proficient in estimating the number of clusters
- [SPRESSO](https://github.com/tmorikuicr/spresso) - Based on gene expression data (may lack spatial information)
- [Metacell](https://tanaylab.github.io/metacell/) - Can enhance the reliability of data by improving the signal-to-noise ratio
- [Leiden](https://github.com/vtraag/leidenalg) - Suitable for larger-scale single-cell data
- [stLearn](https://stlearn.readthedocs.io/) - Can collaboratively integrate gene expression, spatial distance, and tissue morphology data
- [jSRC](https://github.com/xkmaxidian/jSRC) - Integrated dimensionality reduction and clustering
- [Metacell2](https://github.com/tanaylab/metacells) - Achieves higher accuracy in identifying rare cell types
- [scHFC](https://github.com/WJ319/scHFC) - High clustering stability
- [eSPRESSO](https://github.com/tmorikuicr/espresso) - Three-dimensional reconstruction

### Spatial Transcriptomics

- [spatialDE](https://github.com/PMBio/SpatialDE) - A tool specialized in delineating tissue regions in spatial transcriptomics data
- [spaGCN](https://github.com/jianhuupenn/SpaGCN) - Heightened sensitivity in the detection of genes exhibiting enriched spatial expression patterns
- [BayesSpace](https://github.com/edward130603/BayesSpace) - Capable of improving estimation accuracy without sacrificing clustering performance
- [Banksy](https://github.com/prabhakarlab/Banksy_py) - Eliminates the assumption that cells of the same type or subtype must be physically close to each other
- [STAGATE](https://github.com/zhanglabtools/STAGATE) - Adding an attention mechanism to the graph autoencoder enables adaptive learning
- [Stardust](https://github.com/InfOmics/stardust/) - More user-friendly
- [DR-SC](https://github.com/feiyoung/DR-SC.Analysis) - Can perform clustering on data lacking spatial information
- [GraphST](https://github.com/JinmiaoChenLab/GraphST) - Able to preserve local spatial information through graph self-supervised contrastive learning
- [ADEPT](https://github.com/maiziezhoulab/ADEPT) - Well-connected with downstream analyses
