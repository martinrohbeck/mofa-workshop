# MultiOmicsCourse

## Description

This notebook provides an examination of patients diagnosed with blood cancer, specifically focusing on chronic lymphocytic leukemia (CLL). It features a dataset covering four omics: DNA methylation, RNA sequencing, somatic mutations, and drug response data collected from the blood of 200 patients suffering from CLL. Through the integration of these four types of data, we demonstrate how MOFA (Multi-Omics Factor Analysis) enables us to (i) understand key genomic markers of the disease and (ii) recommend personalized treatment options by understanding the latent variables unique to each patient.

The code is heavily inspired by previous projects from [Ricard Argelaguet](https://github.com/rargelaguet), [Britta Velten](https://github.com/bv2) and [Junyan Lu](https://github.com/lujunyan1118).

## Installation

We recommend to create a conda environment for the project from the `env.yaml` file:

```
conda env create --name moc --file=env.yaml
```
