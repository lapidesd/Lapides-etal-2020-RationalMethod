# Supporting code and data for : CONSTRAINTS ON THE VALIDITY OF THE RATIONAL METHOD FOR IDENTIFYING PEAK DISCHARGE ON HETEROGENEOUS HILLSLOPES UNDER IDEALIZED RUNOFF GENERATION CONDITIONS

Dana Lapides [1], Anneliese Sytsma [2], Octavia Crompton [3], and Sally Thompson [3,4]

[1] Department of Earth and Planetary Science, University of California, Berkeley

[2] Department of Environmental Design, University of California, Berkeley

[3] Department of Civil and Environmental Engineering, University of California, Berkeley

[4] Department of Environmental Engineering, University of Western Australia

This repository includes: 

  - Curved_Hillslope_Rational_Method_Optimization.ipynb:
a python program that takes a user-defined IFD curve of the form ![equation](https://latex.codecogs.com/gif.latex?%5Cinline%20I%20%3D%20k_1/%28D%5Eb_1&plus;k_2%29%5E%7Bb_2%7D) (Koutsoyiannis et al., 1998) and runs an optimization for peak flow for hillslopes of different curvatures. Hillslope width functions are given by ![equation](https://latex.codecogs.com/gif.latex?%5Cinline%20w%3Dce%5E%7Bax%7D), following Lapides et al., 2020a. A full description of the solutions used to calculate time of concentration and contributing area is found in Lapides et al. (2020a) and a program for calculating hydrographs on curved hillslopes is available at https://github.com/lapidesd/Hillslope_Storage_Kinematic_Wave. Full description of the optimization process is included in Lapides et al. (2020b).

  - Patchy_Data:
folder containing data were collected by running numerical rainfall-runoff simulations as described in Crompton et al., 2019. Two different patchy landscapes are included, one with patchiness more skewed toward downslope than the other. A grid of intensity-duration values were used for different storms, and each storm was run on subsections of the patchy landscapes in order to identify travel times from different points in the landscape. These data could then be used to construct area-duration curves. In this folder is Patchy_Optimization.ipynb:
a python program that visualizes data from patchy hillslope numerical simulations. Included in this program is a block, which runs an optimization for peak flow from a user-defined IFD curve. A full description of the optimization is available in Lapides et al. (2020b).

For beginners to Python and jupyter notebook:

In each of the two jupyter notebook simulations, the code is broken down into blocks. The first block includes module dependencies, which you must install before running the notebook in addition to jupyter notebook. To run the code, run each block sequentially. If you make changes, you need to rerun only the block where you made changes and some subsequent blocks. Prior blocks should be unaffected.

REFERENCES:

Crompton, O., Sytsma, A., and Thompson, S. (2019). “Emulation of the Saint Venant Equations Enables Rapid and Accurate Predictions of Infiltration and Overland Flow Velocity on Spatially Heterogeneous Surfaces.” Water Resources Research.

Koutsoyiannis, D., Kozonis, D., and Manetas, A. (1998). “A mathematical framework for studying rainfall intensity-duration-frequency relationships.”Journal of Hydrology, 206, 118–135.

Lapides, D., Sytsma, A., and Thompson, S. (2020a). “Analytical solutions for overland flow on topographically convergent or divergent slopes.” Journal of Hydraulic Engineering, in preparation.

Lapides, D., Sytsma, A., Crompton, O. and Thompson, S. (2020b). “Constraints on the validity of the rational method for identifying peak discharge on heterogenous hillslopes under idealized runoff generation conditions." Journal of Hydraulic Engineering, in preparation.
