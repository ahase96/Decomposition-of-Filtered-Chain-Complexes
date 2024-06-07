ripser.cpp is adapted from https://github.com/Ripser/ripser and any changes made to it are explicitely mentioned.

Makefile is taken from https://github.com/Ripser/ripser without any changes made to it.

sphere_3_192 and rp2_600 are taken from https://github.com/Ripser/ripser without any changes made to them.

The remaining files in examples are adapted from https://github.com/OpenAppliedTopology/Umatch_paper and modified slightly in the sense of formatting.

In order to get, make and run my adaption of Ripser:

'''sh
git clone https://github.com/ahase96/Decomposition-of-Filtered-Chain-Complexes
cd ripser
make
.\ripser examples/test.lower_distance_matrix (or .\ripser examples/cyclo_1000.lower_distance_matrix.csv)
'''
