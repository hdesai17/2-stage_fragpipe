# 2-stage FDR searches with FragPipe 
This repository provides code for command line MSFragger 2-stage searches (GUI is highly recommended).

### Table of Contents: 
- [MSFragger command line pipelines for 2-stage searches](https://github.com/hdesai17/chemoproteogenomics#msfragger-command-line-2-stage-search)

The [FragPipe GUI](https://github.com/Nesvilab/FragPipe) is now compatible with 2-stage searches. \
Instructions on running 2-stage searches with the GUI are located in bioXiv manuscript: [Multi-omic stratification of the missense variant cysteinome](https://doi.org/10.1101/2023.08.12.553095) in supplementary information.

>[!IMPORTANT]
>:exclamation:
>_The updated GUI is recommended over command-line scripts provided here._ 

## MSFragger command-line 2-stage search
>[!NOTE]
>_The updated GUI is recommended over command-line scripts._ 

Process .raw MS files with an MSFragger pipeline using Philospher and Peptide Prophet for post-processing with optional IonQuant quantitation. 

#### Before Running

1. Download or clone the repo

  `git clone https://github.com/hdesai17/chemoproteogenomics.git`

2. 2-stage_cmd-line folder contains run script and helper scripts.
  
>[!IMPORTANT]
>Several files require path updates (see notes 'pipeline' and 'run' scripts)

#### Running
   
`./2-stage-run.sh` or `sh 2-stage-run.sh`
 


