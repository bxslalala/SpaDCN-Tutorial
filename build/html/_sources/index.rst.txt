SpaDCN
=============================================================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   Installation
   run_dlpfc

.. image:: ./SpaDCN_overview.png
   :width: 600

Introduction
========
Spatially resolved transcriptomics (SRT) has emerged as a transformative technology for investigating cellular organization and tissue architecture. However, the challenge of identifying pathology-relevant spatial functional landscapes within the tissue microenvironment persists due to the omission of cell-cell communication dynamics. To address this issue, we propose SpaDCN, a Spatially Dynamic graph Convolutional Network architecture, which aligns cell-cell communications and gene expression within spatial context to reveal the spatial functional regions with coherent cellular organization. To effectively transfer the influence of cell-cell communications on expression variation, SpaDCN respectively generates node layer and edge layer of spatial graph representation from expression data and the ligand–receptor complex contributions, and then employs a dynamic graph convolution to switch the propagation of node graph and edge graph. We demonstrate that SpaDCN outperforms existing methods in identifying spatial domains and denoising expression across diverse platforms and species. Notably, SpaDCN excels in identifying marker genes with significant prognostic potential in cancer tissues. In conclusion, SpaDCN offers a powerful and precise tool for spatial domain detection in spatial transcriptomics, with broad applicability across various tissue types and research disciplines.