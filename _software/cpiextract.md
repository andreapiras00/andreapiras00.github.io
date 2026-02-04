---
title: "CPIExtract"
excerpt: "A software package to collect and harmonize small molecule and protein interactions"
collection: software
---

The binding interactions between small molecules and proteins are the basis of cellular functions. Yet, experimental data available regarding compound-protein interaction (CPI) is not harmonized into a single entity but rather scattered across multiple institutions, each maintaining databases with different formats. Extracting information from these multiple sources remains challenging due to data heterogeneity.

CPIExtract interactively extracts, filters and harmonizes CPI data from 9 databases, providing the output in tabular format (csv).
The package provides two separate pipelines:
- Comp2Prot: Extract protein target interactions for compounds provided as input
- Prot2Comp: Extract compound interactions for proteins provided as input