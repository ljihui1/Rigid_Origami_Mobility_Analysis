GENERAL INFORMATION

1. These MATLAB codes are released as supplementary materials for the Reference: 
	Jihui Li, Jinye Zhu, Shaoxing Qu,
	"A general mobility analysis framework to reveal non-intuitive kinematic characteristics of rigid origami",
	Proceedings of the National Academy of Sciences,DOI: 10.1073/pnas.2602778123.
	If you use any part of this code in your work, you MUST cite this paper.

3. Author Information
	A.Corresponding author: 
		Shaoxing Qu
		Zhejiang University, Hangzhou, China
		Email:  squ@zju.edu.cn
	B. Alternate Contact Information
		Jihui Li
		Zhejiang University, Hangzhou, China
		Email:  jihuili@mail.nwpu.edu.cn

DATA & FILE OVERVIEW

The enclosed 51 folders correspond to the 51 origami structures analyzed in the paper. Each folder 
contains two main functions and several subfunctions.

1. main_*name*_mobilityAnalysis.m: This is the main code for calculating the kinematic compatibility equations.
The presented results given in SI Appendix, Table S5 can be reproduced by running this function.

2. main_*name*_motionSimulation.m: This is the main code for simulating the motion paths of rigid-foldable origami. Running this function generates motion animations corresponding to the snapshots shown in the paper. For bifurcated origami, different motion branches can be simulated by manually selecting different sets of combination coefficients, which is indicated by the prompt "Manually  chose one of the solutions of coefficients!".
