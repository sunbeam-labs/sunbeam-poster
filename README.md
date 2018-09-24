# sunbeam-poster
Poster for the 2018 ASM Conference on Rapid Applied Microbial Next-Generation Sequencing and Bioinformatic Pipelines (ASM NGS).

## Abstract:

**Background:** Shotgun metagenomic sequencing experiments provide functional and compositional insight into complex microbial communities. To analyze such data, a number of preprocessing and analytical steps must be performed. Many of these steps, such as quality control, adapter trimming, and phylogenetic classification, are common to many sequencing experiments. Other analyses are specific to each study.

**Methods:** Here we introduce Sunbeam, a modular and user-extensible pipeline designed to process metagenomic sequencing data in a consistent and reproducible fashion. Sunbeam performs multiple processing steps common to many metagenomic sequencing experiments including quality control, adapter trimming, host read removal, low-complexity filtering, metagenomic classification, read assembly, and reference genome alignments. Sunbeam also includes a powerful extension framework that enables users to incorporate new analysis or processing steps easily. 

**Results:** Sunbeam installs in a single step, has no dependencies other than Linux, doesn't require administrative access, and works on most cluster computing frameworks. Sunbeam is inherently modular and will restart where it left off in case of error. To quickly and accurately filter problematic low-complexity reads in metagenomic data, we also introduce Komplexity, a rapid sequence complexity analysis tool, which identifies low complexity sequences to allow removal. The Sunbeam pipeline is well-documented, regularly updated and in routine use. We also provide a number of pre-built extensions (github.com/sunbeam-labs/).

**Conclusions:** Sunbeam provides an easy-to-use, extensible framework for in-depth analysis of metagenomic sequencing experiments. Sunbeam ensures reproducible and consistent analyses by standardizing post-processing, analytical, and custom steps, and robust removal of problematic, low-complexity reads. Sunbeam is written in Python using the Snakemake workflow management software and is freely available at github.com/sunbeam-labs/sunbeam under the GPLv3.

