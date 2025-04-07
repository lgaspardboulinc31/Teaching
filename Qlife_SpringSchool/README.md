# Qlife Spring School - "Cell Dynamics in Developmental Systems"

Recent technological developments in sequencing, imaging and image analysis have granted access to unprecedented temporal and spatial resolution of gene expression, cell dynamics and morphological features.
The Qlife program in Quantitative Biology of the PSL University organizes a spring school that will cover these emerging approaches through a series of lectures and digital workshops, using datasets from Drosophila, ascidians and mammals. Dynamic, quantitative analysis of tissue development will be performed through the combination of image analysis (deep learning-based segmentation, cell tracking, registration) with multiscale analysis of forces and modeling. These data will be integrated with the output of single cell and spatial transcriptomic analyses to provide an unprecedented combined view of cell location, morphology, interactions, migration, expression pattern and fate.

## Workshop

### Objectives of the Workshop

During the Spring School, we provided a workshop untitled "Spatial transcriptomics data analysis for cancer research" with Emma Molière and Florence Cavalli. 
Spatial transcriptomics is a fast-evolving field in both technological and methodological development. It has been widely adopted over the past 2-3 years and is a powerful tool to decipher in situ transcriptome. Cancer is renowned to be anaplastic/dysplastic with uncontrolled cell proliferation, however recent studies showed that some tumors may display spatial architecture like immune cell infiltrates, fibroblasts etc. coherent with the body of work from pathology. Leveraging spatial transcriptomics to better describe spatial heterogeneities is an important topic this workshop will focus on. We will perform the analysis of a 10X Visium brain tumor glioblastoma slide. We will cover first the data generation, annotation and quality control parts. We will then perform clustering, deconvolution with the use of a single-cell reference dataset and predict cell-cell interactions. This will allow the user to become familiar with the data analysis and have the opportunity to question the key steps of the analysis.

The compiled version of the notebook can be retrieved here: [http://xfer.curie.fr/get/Vlqygvkyu0V/Qlife_ST_for_cancer.html](http://xfer.curie.fr/get/Vlqygvkyu0V/Qlife_ST_for_cancer.html)

### Dataset

We rely on public datasets that can be retrieved from: 

- 10X Genomics Visium data for GBM: [Glioblastoma Whole Transcriptome](https://www.10xgenomics.com/datasets/human-glioblastoma-whole-transcriptome-analysis-1-standard-1-2-0.)
- Atlas of GBM from GBmap : [Web explorer](https://cellxgene.cziscience.com/collections/999f2a15-3d7e-440b-96ae-2c806799c08c), [Ruiz-Moreno, C. et al, bioRxiv, 2022](https://www.biorxiv.org/content/10.1101/2022.08.27.505439v1).
- Metaprograms of GBM from spatial data:  [Greenwald et al. (2024)](https://www.cell.com/cell/fulltext/S0092-8674(24)00320-9?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS0092867424003209%3Fshowall%3Dtrue)

### Environment

The workshop was tested on R version 4.4.2 "Pile of Leaves" with an R environment built using renv package. We provide in the folder the `renv.lock` file to build it again and run the workshop. 
The notebook takes about 40min to compile on MacBook Pro Apple M1 with 32Gb memory. 
