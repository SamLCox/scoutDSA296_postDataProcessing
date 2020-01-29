# scoutDSA296_postDataProcessing

MATLAB codes/scripts for post-processing recevied transmissions from wildlife computer SCOUT-DSA-296 tags.  See below for specific notes regarding the use of MATLAB scripts.  The functions script contains functions used within scripts written by myself.  Codes/scripts are to be run in numercial order (i.e. 1, 2a, 2b, 3, 4...).

This code accompanies the paper: Cox et al (2018) Processing of acceleration and dive data on‐board satellite relay tags to investigate diving and foraging behaviour in free‐ranging marine predators. Methods in Ecology and Evolution. 9(1) 64-77.
https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.12845

Please note that these codes/scripts are availble as a guide to the sort of post-processing required with these data - the codes/scripts have not been generalised and de-bugged to work with other datasets than that used in the paper cited above.

Please do not hesitate to contact me with any questions.

---------------------------------------------------------------------------------------------------------------------
SPECIFIC NOTES FOR MATLAB SCRIPTS:

These were written useing MATLAB version R2011b.  The license was base software with the statistics and signal processing tool box.  However a number of functions used across the scripts were taken from the matlab file exchange and will need to be sourced for the codes/scripts to work.  Please let me know if I have missed any of these.

export_fig - https://fr.mathworks.com/matlabcentral/fileexchange/23629-export-fig

subtightplot - https://fr.mathworks.com/matlabcentral/fileexchange/39664-subtightplot

m_map - https://www.eoas.ubc.ca/~rich/map.html

cell2csv - http://fr.mathworks.com/matlabcentral/fileexchange/47055-cell-array-to-csv-file--improved-cell2csv-m-

scripps toolbox (The Matlab Toolbox of Ch. Begler) - http://mooring.ucsd.edu/software/matlab/doc/toolbox/index.html
