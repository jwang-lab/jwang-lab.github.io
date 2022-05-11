---
title: "Wang Lab - Research"
layout: textlay
excerpt: "Wang Lab -- Research"
sitemap: false
permalink: /research/
---

# Research Highlights

---

![]({{ site.url }}{{ site.baseurl }}/images/respic/genediscovery.png){: style="width: 300px; float: left;margin-right: 30px; border: 10px"}

## Deep learning approaches in modeling single-cell and spatial transcriptomics
<div style="text-align: justify">
Single-cell RNA-sequencing (scRNA-Seq) is widely used to reveal the heterogeneity and dynamics of tissues, organisms, and complex diseases, but its analyses still suffer from multiple grand challenges, including the sequencing sparsity and complex differential patterns in gene expression. We introduce the scGNN (single-cell graph neural network) to provide a hypothesis-free deep learning framework for scRNA-Seq analyses ([Wang et al. Nature Communications](https://www.nature.com/articles/s41467-021-22197-x)). This framework formulates and aggregates cell–cell relationships with graph neural networks and models heterogeneous gene expression patterns using a left-truncated mixture Gaussian model. scGNN integrates three iterative multi-modal autoencoders and outperforms existing tools for gene imputation and cell clustering on four benchmark scRNA-Seq datasets. In an Alzheimer’s disease study with 13,214 single nuclei from postmortem brain tissues, scGNN successfully illustrated disease-related neural development and the differential mechanism. scGNN provides an effective representation of gene expression and cell–cell relationships. It is also a powerful framework that can be applied to general scRNA-Seq analyses. Then we extend the framework to single cell multiomics and spatial transcriptomics.
</div>
---- 


![]({{ site.url }}{{ site.baseurl }}/images/respic/scn2aMut.png){: style="width: 300px; float: left;margin-right: 30px; border: 10px"}

## Machine learning approaches and applications in molecular dynamics
<div style="text-align: justify">
Protein allostery is a biological process facilitated by spatially long-range intra-protein communication, whereby ligand binding or amino acid change at a distant site affects the active site remotely. Molecular dynamics (MD) simulation provides a powerful computational approach to probe the allosteric effect. However, current MD simulations cannot reach the time scales of whole allosteric processes. The advent of deep learning made it possible to evaluate both spatially short and long-range communications for understanding allostery. For this purpose, we applied a neural relational inference model based on a graph neural network, which adopts an encoder-decoder architecture to simultaneously infer latent interactions for probing protein allosteric processes as dynamic networks of interacting residues ([Zhu et al. Nature Communications](https://www.nature.com/articles/s41467-022-29331-3)). From the MD trajectories, this model successfully learned the long-range interactions and pathways that can mediate the allosteric communications between distant sites in the Pin1, SOD1, and MEK1 systems. Furthermore, the model can discover allostery-related interactions earlier in the MD simulation trajectories and predict relative free energy changes upon mutations more accurately than other methods.

</div>


---


