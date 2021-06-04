# XBeach wave model for BanzaiPipeline
The files in this repository contain the XBeach model setup for the wave of Banzai Pipeline, Hawaii. The model is very simple, and is here shared with NO WARRANTY WATSOEVER, and above all should not be used for navigation or planning purposes.

To use the model, follow these steps.
1. Download XBeach from the Deltares page: https://oss.deltares.nl/web/xbeach/source-code-and-exe (This model has been tested with "XBeach rev. 5834 x64 (with netcdf support)")
2. Unzip the XBeach model in the "model" folder.
3. To change wave conditions, edit the "jonswap" file. 
4. To change tides, edit the "tide" file.
5. Run XBeach
6. Optionally, open the jupyter notebook file and export each timestep of the model in a separate folder. These images can be turned into a video.

The bathymetry has been interpolated into the model grid from the SOEST HAWAII datasets: http://www.soest.hawaii.edu/hmrg/multibeam/bathymetry.php
