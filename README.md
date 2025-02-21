# Multimodal Foundation Transformer Models for Multiscale Genomics

![Alt text](schematic.png)


This repository supplements the manuscript **Multimodal Foundation Transformer Models for Multiscale Genomics**. It is designed to introduce the application of Transformer models across different genomic data modalities including DNA, single-cell RNA, and spatial transcriptomics. 

### Purpose
- **Adaptation of Transformer Models:**  
  Originally developed for natural language processing, Transformer models have been repurposed here to analyze complex genomic datasets.
- **Key Applications:**  
  - **Predicting RNA Expression:** Inferring RNA expression levels from DNA sequences.
  - **Classifying Promoter Regions:** Distinguishing promoter regions in DNA.
  - **Annotating Cell Types:** Leveraging single-cell RNA sequencing (scRNA-seq) and spatial transcriptomics data for accurate cell type annotation.

### Scope
- **DNA Analysis:**  
  Focus on classifying promoter regions and predicting gene expression from DNA sequences.
- **Single-Cell RNA Sequencing (scRNA-seq):**  
  Capturing intricate gene expression patterns for precise cell type annotation.
- **Spatial Transcriptomics:**  
  Integrating gene expression profiles with spatial coordinates to enhance cell type classification.

## Background & Learning Objectives

### Background
Transformer models have revolutionized natural language processing by effectively managing sequential data. Their success has inspired adaptations in genomics, where they help uncover patterns and dependencies in high-dimensional biological data.

### Learning Objectives
- **Understanding Transformers:**  
  Learn how Transformer architectures can be applied to sequential and high-dimensional genomic data.
- **Application in Genomics:**  
  Gain insights into predicting gene expression, classifying promoter regions, and annotating cell types using Transformer models.
- **Data Modalities:**  
  Explore methods for integrating DNA sequences, scRNA-seq, and spatial transcriptomics data.

## Prerequisites
- **Technical Background:**
  - Basic understanding of single-cell technologies.
  - Python programming skills.
  - Familiarity with tools such as [Scanpy](https://scanpy.readthedocs.io/en/stable/) and [Anndata](https://anndata.readthedocs.io/en/latest/).

## Installation Guide
Before diving into the  tutorials, ensure that the necessary packages are installed. We will need `Scanpy` and `Squidpy` for RNA-seq and Spatial Transcriptomics analysis and `Transformers` from Hugging Face for our Transformer models. Use the following commands to install these packages:

### Required Packages
- **Scanpy & Squidpy:**  
  Used for RNA-seq and spatial transcriptomics analysis.
  ```bash
  pip install scanpy
  pip install squidpy


- To install **Transformers**, use this command in a notebook cell:
  ```python
  pip install transformers


## Data
All necessary data files and detailed instructions are provided within the notebook to ensure you can easily follow along and apply the concepts demonstrated in the tutorials.

## Tutorials
Explore practical applications of Transformers through these hands-on tutorials available via Google Colab:

- **Transformers for MultiOmics – Predicting RNA Expression from DNA Sequences:**  
  Demonstrates how to predict RNA expression levels from DNA sequences.  
  [A Primer on Transformers in Multi-Omics – Predict gene expression from DNA sequences](https://colab.research.google.com/drive/16VxwUb3TQXulSGDdBW8gHG4elp8Rs92s)

- **Transformers for DNA – Classifying Promoter Regions:**  
  Focuses on classifying promoter regions in DNA sequences using a Transformer model.  
  [A Primer on Transformers for Predicting Whether a DNA Sequence is a Gene Promoter](https://colab.research.google.com/drive/1YX_uO73lr8uENXLLj57cMHn796PtAoVd)

- **Transformers for Single-Cell Genomics (scRNA-Seq) – Classifying Cell Types:**  
  Illustrates the use of Transformer model for cell type annotation from scRNA-seq data.  
  [A Primer on Transformers in Single-Cell RNA Sequencing (scRNA-seq)](https://colab.research.google.com/drive/1yDKEFXLIr884JeBDQMHWYthpa-u8k3q9)

- **Transformers in Spatial Transcriptomics – Annotating Cell Types:**  
  Shows how to integrate spatial coordinates with gene expression data for improved cell type classification with a Transformer model.  
  [A Primer on Transformers in Spatial Transcriptomics](https://colab.research.google.com/drive/13kax9iVi4uI6sh3ciXL9HxLl_RNtBcmy)


## System Requirements

These tutorials and associated tools are designed to be platform-independent and can be run on a variety of systems. Below are the specifics regarding system compatibility and access to all the notebooks:

- **Google Colab**:  
  For a hassle-free setup with no local system requirements, you can run the notebooks directly in Google Colab. Google Colab automatically handles all dependencies and provides GPU support. You can access all the tutorials through the following links:
  - [A Primer on Transformers in Multi-Omics – Predict gene expression from DNA sequences](https://colab.research.google.com/drive/16VxwUb3TQXulSGDdBW8gHG4elp8Rs92s)
  - [A Primer on Transformers for Predicting Whether a DNA Sequence is a Gene Promoter](https://colab.research.google.com/drive/1YX_uO73lr8uENXLLj57cMHn796PtAoVd)
  - [A Primer on Transformers in Single-Cell RNA Sequencing (scRNA-seq)](https://colab.research.google.com/drive/1yDKEFXLIr884JeBDQMHWYthpa-u8k3q9)
  - [A Primer on Transformers in Spatial Transcriptomics](https://colab.research.google.com/drive/13kax9iVi4uI6sh3ciXL9HxLl_RNtBcmy)


- **Local Environments**:
  - **Linux**: Tested on  Ubuntu 20.04 . Ensure you have Python installed, along with pip for package management.
  - **macOS**: Tested on macOS Sonoma (14.6) with similar requirements as Linux.
 

Feel free to explore the notebooks, experiment with the code, and dive deeper into applying Transformer models in genomics!



