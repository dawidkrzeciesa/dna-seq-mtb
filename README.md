# Snakemake workflow: dna-seq-mtb

[![Snakemake](https://img.shields.io/badge/snakemake-≥6.3.0-brightgreen.svg)](https://snakemake.github.io)
[![GitHub actions status](https://github.com/snakemake-workflows/dna-seq-mtb/workflows/Tests/badge.svg?branch=main)](https://github.com/snakemake-workflows/dna-seq-mtb/actions?query=branch%3Amain+workflow%3ATests)


A Snakemake workflow for calling somatic variants in tumor/normal samples.
This workflow is under heavy development. 
A tumor-only mode will be added soon, as well as options for handling FFPE samples.

## Background

This workflow uses the [dna-seq-varlociraptor workflow](https://github.com/snakemake-workflows/dna-seq-varlociraptor) as a [module](https://github.com/snakemake-workflows/dna-seq-mtb/blob/main/workflow/Snakefile#L4), and configures it with reasonable defaults for running analysis in molecular tumor boards.


## Usage

The usage of this workflow is described in the [Snakemake Workflow Catalog](https://snakemake.github.io/snakemake-workflow-catalog/?usage=snakemake-workflows%2Fdna-seq-mtb).

If you use this workflow in a paper, don't forget to give credits to the authors by citing https://github.com/snakemake-workflows/dna-seq-mtb.
