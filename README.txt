%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
Boundary Region Analysis Notebook for Coronal Holes (BRANCH)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

Creator: Isaac AshLind
Contact: ia378@nau.edu


BRANCH/
|
|-- AIA/ ----------- FITS files from the Atmospheric Imaging Assembly on SDO
|
|-- BRANCH.ipynb --- main notebook: analyze contours, boundaries, scale, and extent
|
|-- BRANCH.txt ----- create a conda environment with the required dependencies
|
|-- README.txt ----- file you are reading right now, contact me with any questions
|
|-- CHContours/ ---- binary images for east, west, north, south, and full contours
|
|-- CHBRegions/ ---- grayscale boundary regions with RBG background for same as above
|
|-- DataFrames/ ---- .pkl files are Pandas DataFrames storing scale and extent data

NOTE: pipeline is optimized for 193 angstroms, needs adjustment for other wavelengths


Created during NASA Goddard internship, Summer 2021