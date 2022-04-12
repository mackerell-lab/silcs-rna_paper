# Supplementary Data for SILCS-RNA paper
---

## FragMaps 

The directory contains the SILCS FragMaps for all 7 RNAs studied in the paper along with an SDF file with all the respective ligands.

To visualize the FragMaps 
1. Download the repository

```git clone https://github.com/mackerell-lab/silcs-rna_paper.git```
OR
[[Click Here](https://github.com/mackerell-lab/silcs-rna_paper/archive/refs/heads/main.zip)]

2. Enter the directory for an RNA 

```cd FragMaps/fmn/```

3. Unzip the compressed fragmaps

```tar -xzf silcs_fragmaps_5kx9.tgz```

4. Enter the directory

```cd silcs_fragmaps_5kx9```

5. Use VMD or PyMOL to visualize

```vmd -e view_maps.vmd```
OR 
```pymol view_maps.pml```

---

## GCMC - Grand Canonical Monte Carlo (GCMC) Code

The directory contains the executable for GCMC code used in the SILCS-RNA paper: gcmc_v1.4.10

- Should run in Unix/Linux environments.

#### Usage : gcmc_v1.4.10 <input_file> <output_file> {optional: -nt <number_of_threads> }

An example is provided with all inputs and outputs in the example.tgz file.
