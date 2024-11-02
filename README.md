# aviangenomics

Overview

This repository contains data and scripts related to the genome assembly, annotation, and analysis of finch species (family Fringillidae). The project aims to study genome structure, evolutionary patterns, and immune gene functions across different bird genomes.

Project Contents

    HoFi_hifiasm_assembly/: Contains genome assembly files for Haemorhous mexicanus (House Finch) produced using HiFi sequencing data and assembled with the Hifiasm tool.
    Scripts/: (If applicable) Contains scripts used for quality assessment, data processing, and analysis.
    Results/: (Optional) Contains summary tables, BUSCO results, or any other processed output files (excluding raw data files).
    Documentation/: (Optional) Provides further documentation on methods and protocols used in this project.

Data

Due to storage limitations , raw .fasta, .fastq, .fna, .fa, and .sra files are not stored here. The accesion numbers for the raw reads used can be found in the automation scripts.

Setup Instructions

To run the analysis, clone this repository and set up the necessary dependencies.
Cloning the Repository

bash

git clone https://github.com/vertebrategenomics/aviangenomics.git
cd aviangenomics

Dependencies

The following tools are required to run analyses in this project:

    BUSCO
    QUAST
    Hifiasm
    Python 3.8+ and required libraries
