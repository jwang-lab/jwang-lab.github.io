---
title: "Wang Lab - Research"
layout: textlay
excerpt: "Wang Lab -- Research"
sitemap: false
permalink: /research/
---

# Research Highlights

---

![]({{ site.url }}{{ site.baseurl }}/images/respic/TrimNN.png){: style="width: 300px; float: left;margin-right: 30px; border: 10px"}

## Cellular community motifs in spatial omics
<div style="text-align: justify">
The spatial organization of cells plays a pivotal role in shaping tissue functions and phenotypes in various biological systems and diseased microenvironments. However, the topological principles governing interactions among cell types within spatial patterns remain poorly understood. Here, we present the triangulation cellular community motif neural network (TrimNN), a graph-based deep learning framework designed to identify conserved spatial cell organization patterns, termed cellular community (CC) motifs, from spatial transcriptomics and proteomics data. TrimNN employs a semi–divide-and-conquer approach to efficiently detect overrepresented topological motifs of varying sizes in a triangulated space. By uncovering CC motifs, TrimNN reveals key associations between spatially distributed cell-type patterns and diverse phenotypes. These insights provide a foundation for understanding biological and disease mechanisms and offer potential biomarkers for diagnosis and therapeutic interventions.
  
<p><br>Citation: Yu, Y., Wang, S., Li, J. et al. TrimNN: characterizing cellular community motifs for studying multicellular topological organization in complex tissues. Nat Commun 16, 7737 (2025). https://doi.org/10.1038/s41467-025-63141-7</p>
</div>
---- 

---

![]({{ site.url }}{{ site.baseurl }}/images/respic/BSP.png){: style="width: 300px; float: left;margin-right: 30px; border: 10px"}

## Spatially variable features identification in spatial omics
<div style="text-align: justify">
Identifying spatially variable genes (SVGs) is critical in linking molecular cell functions with tissue phenotypes. Spatially resolved transcriptomics captures cellular-level gene expression with corresponding spatial coordinates in two or three dimensions and can be used to infer SVGs effectively. However, current computational methods may not achieve reliable results and often cannot handle three-dimensional spatial transcriptomic data. Here we introduce BSP (big-small patch), a non-parametric model by comparing gene expression pattens at two spatial granularities to identify SVGs from two or three-dimensional spatial transcriptomics data in a fast and robust manner. This method has been extensively tested in simulations, demonstrating superior accuracy, robustness, and high efficiency. BSP is further validated by substantiated biological discoveries in cancer, neural science, rheumatoid arthritis, and kidney studies with various types of spatial transcriptomics technologies.
  
<p><br>Citation: <b>Wang, J.*</b>, Li, J., Kramer, S.T. et al. Dimension-agnostic and granularity-based spatially variable gene identification using BSP. Nat Commun 14, 7367 (2023). https://doi.org/10.1038/s41467-023-43256-5</p>
</div>
---- 


---

![]({{ site.url }}{{ site.baseurl }}/images/respic/scGNN.png){: style="width: 300px; float: left;margin-right: 30px; border: 10px"}

## Graph deep learning approaches modeling single-cell RNA-seq data
<div style="text-align: justify">
Single-cell RNA-sequencing (scRNA-Seq) is widely used to reveal the heterogeneity and dynamics of tissues, organisms, and complex diseases, but its analyses still suffer from multiple grand challenges, including the sequencing sparsity and complex differential patterns in gene expression. We introduce the scGNN (single-cell graph neural network) to provide a hypothesis-free deep learning framework for scRNA-Seq analyses ([Wang et al. Nature Communications](https://www.nature.com/articles/s41467-021-22197-x)). This framework formulates and aggregates cell–cell relationships with graph neural networks and models heterogeneous gene expression patterns using a left-truncated mixture Gaussian model. scGNN integrates three iterative multi-modal autoencoders and outperforms existing tools for gene imputation and cell clustering on four benchmark scRNA-Seq datasets. In an Alzheimer’s disease study with 13,214 single nuclei from postmortem brain tissues, scGNN successfully illustrated disease-related neural development and the differential mechanism. scGNN provides an effective representation of gene expression and cell–cell relationships. It is also a powerful framework that can be applied to general scRNA-Seq analyses. Then we extend the framework to single cell multiomics and spatial transcriptomics.
<p><br>Citation: <b>Wang, J.*</b>, Ma, A., Chang, Y. et al. scGNN is a novel graph neural network framework for single-cell RNA-Seq analyses. Nat Commun 12, 1882 (2021). https://doi.org/10.1038/s41467-021-22197-x</p>
</div>
---- 


![]({{ site.url }}{{ site.baseurl }}/images/respic/NRI.png){: style="width: 300px; float: left;margin-right: 30px; border: 10px"}

## Machine learning approaches and applications in molecular dynamics
<div style="text-align: justify">
Protein allostery is a biological process facilitated by spatially long-range intra-protein communication, whereby ligand binding or amino acid change at a distant site affects the active site remotely. Molecular dynamics (MD) simulation provides a powerful computational approach to probe the allosteric effect. However, current MD simulations cannot reach the time scales of whole allosteric processes. The advent of deep learning made it possible to evaluate both spatially short and long-range communications for understanding allostery. For this purpose, we applied a neural relational inference model based on a graph neural network, which adopts an encoder-decoder architecture to simultaneously infer latent interactions for probing protein allosteric processes as dynamic networks of interacting residues ([Zhu et al. Nature Communications](https://www.nature.com/articles/s41467-022-29331-3)). From the MD trajectories, this model successfully learned the long-range interactions and pathways that can mediate the allosteric communications between distant sites in the Pin1, SOD1, and MEK1 systems. Furthermore, the model can discover allostery-related interactions earlier in the MD simulation trajectories and predict relative free energy changes upon mutations more accurately than other methods.
<p><br>Citation: Zhu, J., <b>Wang, J.*</b>, Han, W. et al. Neural relational inference to learn long-range allosteric interactions in proteins from molecular dynamics simulations. Nat Commun 13, 1661 (2022). https://doi.org/10.1038/s41467-022-29331-3</p>
</div>


---


