---
title: "New algorithms for unsupervised cell clustering from scRNA-seq data"
collection: publications
category: under_review
permalink: /publication/scRNA
excerpt: Novel k-MST graph-based clustering methods tailored for unsupervised identification of cell types from single-cell RNA-seq datasets.
date: 2025-02-17
venue: 'Under Review'
paperurl: 'https://www.biorxiv.org/content/10.1101/2024.11.22.624768v1.full.pdf'
bibtexurl: 
citation: 'Robles, M., Díaz-Riaño, J., <strong>Forigua, C.</strong>, Ojeda, S., Guio, L., Siaucho, P., ... & Duitama, J. (2024). New algorithms for unsupervised cell clustering from scRNA-seq data. bioRxiv, 2024-11.'
---
Abstract
====
The identification of cell types is a basic step of the pipeline for Single-Cell RNA sequencing data analysis. However, unsupervised clustering of cells from scRNA-seq data has multiple challenges: the high dimensional nature of the data, the sparse nature of the gene expression matrix, and the presence of technical noise that can introduce false zero entries. In this study, we introduce new algorithms for clustering scRNA-seq data. The first algorithm builds a k-MST graph from distances obtained directly from the input data without dimensionality reduction. The computation follows an iterative procedure of k steps in which each step calculates and stores the edges of minimum spanning trees over different subgraphs obtained removing edges selected in previous iterations. The Louvain algorithm is executed on the k-MST graph for cell clustering. We also explored alternatives based on neural networks in which an autoencoder is used to learn the parameters of a Gaussian mixture model, aiming to improve the handling of clusters with different shapes and sizes. Benchmark experiments with simulated data and public datasets show that the algorithms proposed in this work have competitive accuracy, compared to previous solutions, but also that sequencing depth, number of cells and tissue types have important effects on the performance of the algorithms. Moreover, we performed further experiments with scRNA-data taken from a patient with refractory epilepsy. The AE-GMM model achieved the best accuracy for this dataset, and the k-MST ranked first among methods that do not require previous information on the expected number of clusters.