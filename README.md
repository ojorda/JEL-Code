This README file describes the STATA replication files for the paper Jordà and Taylor, “Local projections” as published in Journal of Economic Literature.
Notes:    The replication files are located in the main folder LP_JEL_Replication, which in turn contains a number of subfolders, one for each of the main examples, organized as follows:
Folder name:	Output figures shown in the paper
Example1_LongDifferences:	Figure1a.pdf, Figure1b.pdf
Example2_Multipliers:	Figure2a.pdf, Figure2b.pdf, Figure9a.pdf, Figure9b.pdf
Example3_Smoothing:	Figure3.pdf
Example4_LagAugmentation:	Figure4.pdf
Example5_SignificanceBands:	Figure5a.pdf, Figure5b.pdf
Example6_JointInference: Figure6a.pdf, Figure6b.pdf
Example7_MinimumDistance:	Figure7a.pdf, Figure7b.pdf, Figure7c.pdf, Figure7d.pdf
Example8_Counterfactuals:	Figure8a.pdf, Figure8b.pdf
Example9_StateDependence:	Figure10a.pdf, Figure10b.pdf

The STATA programs rely on various packages which need to be installed for the code to run. If an error message occurs, search for and install the required package. In addition, correct output of the figures requires the fonts Palatino and cmsy10 to be installed. Most do files can be run individually, but some folders also include an all.do file which will run all programs in that folder. Each do file sets the current directory and users will need to amend those lines to point to their own directory path.

