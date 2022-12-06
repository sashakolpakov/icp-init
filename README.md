# E-Init :: עינית :: Robust ICP initialization

Authors: Sasha Kolpakov (UniNe, Switzerland) & Michael Werman (HUJI, Israel)

The paper is available as icp_init.pdf

Some tests and examples of ICP initialization:

under ideal conditions (icp_init_main_algorithm); with multiplicative noise (icp_init_mult_noise); with additive noise (icp_init_add_noise); with occlusions points added (icp_init_occluded_images); with occlusion and noise superimposed (icp_init_superposition); registering two scans of the same object (icp_init_partial_scan). 

Using:

Caerbannog point clouds from https://data.nrel.gov/submissions/153 (unoccluded teapot, bunny, cow);
Three D Scans from https://threedscans.com/ ("Enfant au Chien", "Pan and Bacchus", "Hermanubis" statues before and after restoration). 

Required:

SageMath (https://www.sagemath.org) installed to run the worksheets;
Open3D (http://www.open3d.org), available via pip. 

Also:

generating interactive pictures illustrating the algorithm (icp_init_generate_pics); pictures saved in /pics/ folder (add_noise_pic, mul_noise_pic, occluded_pic files, all timestamped, for each Caerbannog point cloud); all pictures are in scripted html format and have to be downloaded to be viewed;

comparing ICP performance without initialization, and with initialization under ideal conditions, no noise, no occlusion (icp_init_comparison); interactive pictures saved in /pics/ folder (comparison_no_init, comparison_init files, all timestamped, for each Caerbannog point cloud);

comparing our initialization of local ICP to global optimization ICP version GO-ICP (https://github.com/yangjiaolong/Go-ICP), test statistic available in (go_icp_comparison). 
