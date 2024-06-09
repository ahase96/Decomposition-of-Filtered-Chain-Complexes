This is the repository corresponding to the bachelor's thesis 'Computational Decomposition of Filtered Chain Complexes' by Axel Hasenkamp. The thesis was handed it at the Technical University of Munich on 15 June 2024.

The files in the repository are taken or adapted from the following sources:

- ripser.cpp is adapted from https://github.com/Ripser/ripser and any changes made are explicitely mentioned is said file.
- Makefile is taken from https://github.com/Ripser/ripser and no changes were made.
- sphere_3_192 and rp2_600, in the folder examples, are taken from https://github.com/Ripser/ripser and no changes were made.
- The remaining files in the folder examples are adapted from https://github.com/OpenAppliedTopology/Umatch_paper and modified in the sense of formatting only.

Computational Decomposition of Filtered Chain Complexes_final contains LaTeX code of the bachelor's thesis.

In order to obtain, make and run this adaption of Ripser:

```sh
git clone https://github.com/ahase96/Decomposition-of-Filtered-Chain-Complexes
cd ripser
make
.\ripser examples/test.lower_distance_matrix
```

or alternatively

```sh
git clone https://github.com/ahase96/Decomposition-of-Filtered-Chain-Complexes
cd ripser
make
.\ripser examples/cyclo_1000.lower_distance_matrix.csv
```
