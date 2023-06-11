# MOMs-PI_microdiversity_2023

Code and input data used to replicate data analyses in the manuscruipt Microdiversity of the Vaginal Microbiome is Associated with Preterm Birth.

### Code

`MOMS-PI_analysis.ipynb`: code used to analyze CTF, ALTAS, InStrain, gRodon, and PathoFact outputs and metadata and generate plots in Fig. 1-4 and Supplementary Fig. 1-9.
- `Fig. 1a`: use ALTAS outputs
- `Fig. 1b-e`: use CTF outputs
- `Fig. 2a-f` and `Fig. 2j`: use InStrain outputs based on data from the MOMs-PI study
- `Fig. 2h-i`: use InStrain outputs based on data from the Relman study (Gotsman et al.)
- `Fig. 3a`: use ALTAS outputs and InStrain outputs based on data from the MOMs-PI study
- `Fig. 3b`: use gRoden outputs
- `Fig. 3d-f`: use InStrain outputs based on data from the MOMs-PI study
- `Fig. 4: use PathoFact outputs
- `Supplementary Fig. 2`: use ALTAS outputs
- `Supplementary Fig. 3 and 4`: use InStrain outputs based on data from the MOMs-PI study
- `Supplementary Fig. 5a-d`: use ALTAS outputs
- `Supplementary Fig. 5e`: use ALTAS outputs and InStrain outputs based on data from the MOMs-PI study
- `Supplementary Fig. 6f-i`: use InStrain outputs based on subsampled data (10^5 reads) from the MOMs-PI study
- `Supplementary Fig. 6j`: use InStrain outputs based on subsampled data (5,000 Gardnerella reads) from the MOMs-PI study
- `Supplementary Fig. 6`: use ALTAS outputs and InStrain outputs based on data from the MOMs-PI study
- `Supplementary Fig. 7`: use InStrain outputs based on data from the MOMs-PI study
- `Supplementary Fig. 8`: use PathoFact outputs
- `Supplementary Fig. 9`: use metadata

### Input data
- `CTF`: outputs from compositional tensor factorization analysis
- `InStrain`: microdiversity profiles using InStrain
  - `MOMs-PI`: use data from the MOMs-PI study
  - `Relman`: use data from the Relman study (Gotsman et al.)
  - `subsample_10to5reads`: use subsampled data (10^5 reads) from the MOMs-PI study
  - `subsample_Gardnerella_reads`: use subsampled data (5,000 Gardnerella reads) from the MOMs-PI study
- `ALTAS`: outputs from ALTAS pipeline for assembly, binning, and annotation
-  `PathoFact`: antimicrobial resistance (AMR) profiles using PathoFact
-  metadata can be requested through the RAMS Registry (https://ramsregistry.vcu.edu)

