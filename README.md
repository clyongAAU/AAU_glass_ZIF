# Deep learning force field for ZIF crystal/glass solid electrolyte

# Supplementary Data
This repository includes the data and analysis code used in the paper listed above.

Folders:
```
Lammps_input (lithium trajectory simulation lammps file)
MSD_NGP (All MSD and NGP data calculated from lithium trajectory)
van_Hove_function (All van Hove correlation function results for crystalline and glassy ZIF-4 and ZIF-62)
ZIF_structure_file (Lammps data file of crystalline and glassy ZIF-4 and ZIF-62)
```

# USE POTENTIAL
To use the potential in LAMMPS use the following commands:

```
pair_style deepmd ../../ZIFsol.pb
pair_coeff      * * C H N Zn Li
```




