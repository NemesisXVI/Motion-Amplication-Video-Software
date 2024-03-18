The code includes the following combination of spatial and temporal
filter, which we used to generate results:

	Spatial					Temporal
=========================================================================
	Laplacian pyramid		Butterworth bandpass
        Laplacian pyramid		Second-order IIR bandpass

Dependencies :  MATLAB's Image Processing Toolbox , and MATLAB's CPP COMPILER


To run in your local system 

1) Download the folder, given along the report and extract it .
2) Start up MATLAB and change directory to the location of this code.
3) Run "dependency.m" to build pyramid toolbox libraries .
4) Run "install.m".
5) Run "reproduce.m" to reproduce the results .



