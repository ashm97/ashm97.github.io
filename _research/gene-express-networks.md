---
title: "Classifying bacterial and viral infections"
layout: single-portfolio
excerpt: "<img src='/images/research/Gene_network.png' alt=''>"
collection: research
order_number: 85
---

Multivariate feature selection can often be a black box. This is especially the case in gene expression data, where thousands of features are considered in combination. Using only model statistics, one has little insight into the process driving predictive capability of feature sets. To provide direct insight, I investigated how underlying networks guide the process of feature selection in gene expression data. In the biological context, this can be extremely useful in finding the key groups of genes driving a given disease state. In the modelling perspective, this provides a visually interpretable means to explore feature selection of high dimensional data.

## Article

<b>Myall, A.C.</b>, Perkins, S., Rushton, D., Jonathan, D., Spencer, P., Jones, A.R. and Antczak, P., 2020. <i>Identifying robust biomarkers of infection through an omics-based meta-analysis.</i> medRxiv.

A fundamental problem for disease treatment is that while antibiotics are a powerful counter to bacteria, they are ineffective against viruses. Often, bacterial and viral infections are confused due to their similar symptoms and lack of rapid diagnostics. With many clinicians relying primarily on symptoms for diagnosis, overuse and misuse of modern antibiotics are rife, contributing to the growing pool of antibiotic resistance.  To ensure a given individual receives optimal treatment given their disease state and to reduce over-prescription of antibiotics leading to antimicrobial resistance, the host response can be measured quickly to distinguish between the two states. To establish a predictive biomarker panel of disease state (viral/bacterial/no-infection) we conducted a meta-analysis of human blood infection studies using Machine Learning (ML). We focused on publicly available gene expression data from two widely used platforms, Affymetrix and Illumina microarrays as they represented a significant proportion of the available data. We were able to develop multi-class models with high accuracies with our best model predicting 93% of bacterial and 89% viral samples correctly. To compare the selected features in each of the different technologies, we reverse engineered the underlying molecular regulatory network and explored the neighbourhood of the selected features. This highlighted that although on the gene-level the models differed, they did contain genes from the same areas of the network. Specifically, this convergence was to pathways including the Type I interferon Signalling Pathway, Chemotaxis, Apoptotic Processes, and Inflammatory / Innate Response. 

<p align="center">
  <img src='/images/research/biomarkers_gene_sel.png'  />
</p>

<i>Genes which were highly selected amongst optimal models</i>

[Article](https://academic.oup.com/cid/advance-article/doi/10.1093/cid/ciaa892/5868508){: .btn--research} 

[GitHub Repo](https://github.com/ashm97/Developing-an-infection-state-predictive-model){: .btn--research}



