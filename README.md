# CottonSat
An open-access super-resolution and fusion satellite imagery dataset for cotton


You must unzip the file. The files are organised into the S-1 (Sentinel-1), the “Super-resolution” and “Data fusion” folders.
The “Super-resolution” folder contains the S-2 folder, which includes the original Sentinel-2 images and those cropped to areas of interest. The super-resolved images by band (red, green, blue, and near-infrared) are also included in the folder.
The “Data fusion” folder contains the original images and the images cropped according to areas of interest for the Sentinel-2 (S-2) and Landsat 8/9 (L8-9) satellites. It also contains the registration (REGISTRATION_L8-9_S2 and REGISTRATION_L8-9_SR) and resampling (RESAMPLED_L8-9_S2 and RESAMPLED_L8-9_SR) folders, respectively, for the fusion of Landsat 8/9 and Sentinel-2 satellite data, as well as for the fusion of Landsat 8/9 and Sentinel-2 super-resolution data. The fusion results are in the  FUSION_SR and FUSION_SIMPLE folders, with and without super-resolution, respectively.
All images are organised by observation number.

The PlanetScope data have been used for comparition purposes and have not been included in the dataset due to copyright restrictions.
