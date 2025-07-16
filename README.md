# Emotional Granularity
This repository contains code and data from, and involves a replication of the analyses conducted in, Hoemann et al., 2023

Hoemann, K., Lee, Y., Kuppens, P., Gendron, M., & Boyd, R. L. (2023). Emotional granularity is associated with daily experiential diversity. Affective Science, 4(2), 291-306. https://doi.org/10.1007/s42761-023-00185-2

## Environment
The environment is a R 4.4.1 environment that makes use of [Tidyverse](https://www.tidyverse.org/packages/).

## Data
Data were obtained from the associated [GitHub repository](https://github.com/katie-hoemann/granularityDiversity) and analyses were carried out according to steps describes on the associated [OSF repository](https://osf.io/gn8ca/)

## Repository organization
 * [Data](./Data) # raw data input to script
 * [original_study](./original_study)
 * [replication](./replication)
 * [README.md](./README.md)
 * [.Rproj](./emotionality_granularity_replication.Rproj)

### Project structure (TEMPLATE BORROWED FROM OTHER REPO)
```{text}
granularityDiveristy
  ├── scripts/
  │   ├── matlab_batch.m
  │   ├── freesurfer_preproc_clinical.m # a wrapper for recon-all-clinical
  │   │   ├── 
  │   ├── firstlevel_subject.m
  │   ├── project_spmT_to_surface.sh   <== your new bash script
  │   └── visualize_overlay.sh         <== optional screenshot tool
  ├── data/
  │   ├── func/<subj>/spmT_0001.nii
  │   └── anat/<subj>/T1.nii.gz
  ├── fs_output/  # Freesurfer recon-all output (SUBJECTS_DIR)
  └── surface_output/<subj>/lh.spmT.mgh, screenshot.png, etc.
```

## Analyzing data and generating plots
pending

 README.md templated from [Greta Tuckute](https://github.com/gretatuckute/drive_suppress_brains/blob/main/README.md) and [Guillaume Noblet](https://github.com/gnoblet/TidyTuesday/blob/main/README.md)