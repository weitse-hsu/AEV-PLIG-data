# AEV-PLIG-data
This repository provides the exact train/validation/test splits used in the manuscript *"Can AI-predicted complexes teach machine learning to compute drug binding affinity?"*

These files are provided to support reproducibility for the benchmarking of AEV-PLIG models trained on public datasets, including HiQBind, BindingNet v1, and BindingNet v2.

## Contents

- `processed_hiqbind.csv` and `processed_bindingnet_v1_v2.csv`: CSV files containing spltis for the processed HiQBind and BindingNet v1 and v2 datasets, respectively. These datasets are used in experiments associated with Figure 1A. 
- The folder `progressive_augmentation`: A folder containing CSV files for the progressive augmentation experiments presented in Figure 1C, which contains subfolders `high_conf`, `med_conf`, and `low_conf`. Each subfolder contains 5 subfolders (`50K`, `75K`, `100K`, `125K`, and `150K`), each of which contains a CSV file with the respective splits.
- The folder `filtered_datasets`: A folder containing filtered HiQBind datasets used in experiments associated with Figure 2C, which includes subfolders `all_entries`, `high_confidence` and `high_quality`, each containing a CSV file with the respective splits. Note that the Boltz-1x-reproduced dataset has the same splits as the original HiQBind dataset.

---

## Authors
Wei-Tse Hsu, University of Oxford (wei-tse.hsu@bioch.ox.ac.uk)
