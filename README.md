# Robust ICP initialization

Authors: Sasha Kolpakov (UniNe, Switzerland) & Michael Werman (HUJI, Israel)

The paper is available as icp_init.pdf

Some tests and examples of ICP initialization:

under ideal conditions (icp_init_main_algorithm); with multiplicative noise (icp_init_mult_noise); with additive noise (icp_init_add_noise); with occlusions points added (icp_init_occluded_images).

Using:

Caerbannog point clouds from https://data.nrel.gov/submissions/153 (unoccluded teapot, bunny, cow).

Required:

SageMath (https://www.sagemath.org) installed to run the worksheets.

Also:

generating interactive pictures illustrating the algorithm (icp_init_generate_pics); pictures saved in /pics/ folder (add_noise_pic, mul_noise_pic, occluded_pic files, all timestamped, for each Caerbannog point cloud); all pictures are in scripted html format and have to be downloaded to be viewed.

comparing ICP performance without initialization, and with initialization under ideal conditions, no noise, no occlusion (icp_init_comparison); interactive pictures saved in /pics/ folder (comparison_no_init, comparison_init files, all timestamped, for each Caerbannog point cloud).
