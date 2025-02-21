# Multimodal Foundation Transformer Models for Multiscale Genomics

![Alt text](schematic.png)


This repository supplements the manuscript **Multimodal Foundation Transformer Models for Multiscale Genomics**. It is designed to introduce the application of Transformer models across different genomic data modalities including DNA, single-cell RNA, and spatial transcriptomics. 


## Background
Transformers, originally developed for tasks in natural language processing (NLP), have shown remarkable adaptability and success in analyzing complex patterns in high-dimensional biological datasets, such as single-cell RNA sequencing (scRNA-seq). By leveraging Transformers, researchers can effectively manage the sequential and intricate nature of biological data, which is pivotal for capturing essential dependencies and patterns crucial for precise cell type annotation.

## Learning Objectives
This primer provides:
- A comprehensive introduction to using Transformer across different genomic data modalities.
- Insights into how Transformers handle the complex data structure of DNA, single-cell RNA, and spatial transcriptomics.
- Guidance on applying these models for predicting gene expression from DNA sequences, promoter prediction and annotate cell types accurately.

## Prerequisites
Readers should have a basic understanding of:
- Single-cell technology principles.
- Python programming.
- Functionality of [Scanpy](https://scanpy.readthedocs.io/en/stable/) and [Anndata](https://anndata.readthedocs.io/en/latest/) packages.

## Installation Guide

Before diving into the  tutorials, ensure that the necessary packages are installed. We will need `Scanpy` and `Squidpy` for RNA-seq and Spatial Transcriptomics analyisis and `Transformers` from Hugging Face for our Transformer models. Use the following commands to install these packages:

- To install **Scanpy**, and **Squidpy** use this command in a notebook cell:
  ```python
  !pip install scanpy
  !pip install squidpy

- To install **Transformers**, use this command in a notebook cell:
  ```python
  !pip install transformers


## Data
All necessary data files and detailed instructions are provided within the notebook to ensure you can easily follow along and apply the concepts demonstrated in the tutorials.

## Tutorials
For a practical application of these concepts, refer to the tutorials available as:

- Transformers in MultiOmics - Predicting RNA Expression from DNA Sequences
This primer illustrates how to use Transformer models to predict RNA expression levels from DNA sequences, demonstrating the model's capability to understand the interactions between nucleotides in promoter regions.
- [A Primer on Transformers in   - Predict gene expression (RNA) levels from corresponding DNA sequences](https://colab.research.google.com/drive/16VxwUb3TQXulSGDdBW8gHG4elp8Rs92s)


[MultiOmics Primer Notebook ; A Primer on Transformers in MultiOmics - Predict gene expression (RNA) levels from corresponding DNA sequences](https://colab.research.google.com/drive/1YX_uO73lr8uENXLLj57cMHn796PtAoVd)

- Transformers in DNA Primer - Classifying Promoter Regions
This primer discusses using Transformer models to classify promoter regions in DNA sequences. It includes discussions on integrating synthetic and real data to capture essential sequence patterns and positional dependencies.
[DNA Primer Notebook:A Primer on Transformers for Predicting Whether a DNA Sequence is a Promoter](https://colab.research.google.com/drive/1YX_uO73lr8uENXLLj57cMHn796PtAoVd)

- Transformers in Single-Cell Genomics (scRNA-Seq) Primer - Classifying Cell Types in scRNA-seq Data
This primer discusses the application of Transformer models in identifying different cell types from single-cell RNA sequencing data, emphasizing complex gene expression patterns.
[scRNA Primer Notebook: A Primer on Transformers in Single-Cell RNA Sequencing(scRNA-seq](https://colab.research.google.com/drive/1yDKEFXLIr884JeBDQMHWYthpa-u8k3q9)

- Transformers in Spatial   Primer - Classifying Cell Types in Spatial Transcriptomics Data
This primer shows how Transformer model can be used to annotate cell types in spatial transcriptomics data, integrating gene expression profiles with spatial coordinates for enhanced analysis.
[Spatial Transcriptomics Primer Notebook: A Primer on Transformers in Spatial Transcriptomics](https://colab.research.google.com/drive/13kax9iVi4uI6sh3ciXL9HxLl_RNtBcmy)

- [A Primer on Transformers in   - Predict gene expression (RNA) levels from corresponding DNA sequences](https://colab.research.google.com/drive/16VxwUb3TQXulSGDdBW8gHG4elp8Rs92s)
- [A Primer on Transformers for Predicting Whether a DNA Sequence is a Gene Promoter](https://colab.research.google.com/drive/1YX_uO73lr8uENXLLj57cMHn796PtAoVd)
- [A Primer on Transformers in Single-Cell RNA Sequencing (scRNA-seq)](https://colab.research.google.com/drive/1yDKEFXLIr884JeBDQMHWYthpa-u8k3q9)
- [A Primer on Transformers in Spatial Transcriptomics](https://colab.research.google.com/drive/13kax9iVi4uI6sh3ciXL9HxLl_RNtBcmy)


## System Requirements

These tutorials and the associated tools are designed to be platform-independent and can be run on a variety of systems. Below are the specifics regarding system compatibility:

- **Google Colab**: For a hassle-free setup and no local system requirements, you can run the notebook directly in [Google Colab](https://colab.research.google.com/github/sumeer1/A-Primer-on-Transformers-in-Single-Cell-Genomics/blob/main/A%20Primer%20on%20Transformers%20for%20Cell%20Type%20Annotation.ipynb). This platform automatically handles all dependencies and provides a robust environment with GPU support.

- **Local Environments**:
  - **Linux**: Tested on macOS Sonoma (14.5). Ensure you have Python installed, along with pip for package management.
  - **macOS**: Tested on Ubuntu 20.04 with similar requirements as Linux.
 
    

Feel free to explore the notebook, experiment with the code, and dive deeper into the application of Transformers in genomics!
