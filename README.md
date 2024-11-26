# CS683-Project
Aim of this project is to reduce the Address transaltion bottleneck by integrating the use of L2/LLC cache block entries to store the TLB entries and the use a Dead Page predictor.

we are integrating  the ideas taken from 

Victimia:-https://dl.acm.org/doi/10.1145/3613424.3614276

HPCA’ 21 Dead Page and Dead Block Predictors:-https://www.csa.iisc.ac.in/~arkapravab/papers/hpca21_DOA.pdf 

Simulator:-Sniper is the simulator used to do the experiments.

The Zip files dp.zip, combined_Victima_dp.zip contains the implementation of dead_page predictor , Victima+dead_page predictor respectively.
