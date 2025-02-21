
The HSC Result compiler is a rather simple MATLAB app made for the purpose of simplifying the 
process of importing solar cell IV-measurement data. 

It is only known to function with files from two specific sources:
1. 	.mat-files containing IV-sweeps and figures of merit obtained using a Keithley 2450 SMU 
	and a custom MATLAB measurement script shared on the following website https://zenodo.org/records/6510119
2.	.json-files exported from the Litos Lite Parallel JV and Stability Measurement Platform (FLUXiM AG).

Note for naming your measurements:
An underscore-separated naming scheme is used for categorizing measurements:
type_samplespecification_other
for example:
"SpiroOMeTAD_sample1electrode1_remeasure"
If you have either "_d_" or "_D_" in your measurement name, it will be recognized as a dark measurement,
and thus it's figures of merit will not be listed.

This is NOT a standalone app, thus requiring MATLAB in order to run (tested with 2023b). It is installed into MATLAB using the installer file.

Apologies for the messy state and lacking documentation of this project, it was uploaded in a rush. There are most certainly flaws in this app which may be fixed in time. Additionally, users are free to make their own modifications.
