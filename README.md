# How to Extract Data from the Amygdala Using MarsBaR
- Protocol Developed by Kristen Stauffer
- Webpage Developed by Andie Bulbin

## Step 1: Open and Set Up MATLAB
1. Open MATLAB
1. Type the following in the command line:
- $ addpath(genpath(‘PATH TO SPM12’))
- $ cd /PATH FOR NO SCALP IMAGING DATA DIRECTORY
- $ spm fmri
- NOTE: chane the file paths based on what version of SPM you are using and where you are getting the Level 2

## Step 2: Open MarsBaR
1. Click on Toolox menu and select marsbar
(insert image)

## Step 3: Define the Design to Extract Data From
1. Click on "Design" from the MarsBaR menu
1. Select "Set design from file"
1. Go to Level_2_Analyses Folder
1. Click on the analysis folder that you want to extract the data from (e.g. ART_102417)
1. Click on the con_XXXX folder that you want to extract data from
1. Select the SPM.mat file

## Step 4: Define the Parameter to Extract the Data
1. Click on the "Data" from the MarsBaR menu
1. Select "Extract ROI Data" (full options)
1. Define the ROI(s) that you are going to extract from
- Scroll to the template folder
- Select the ROIs that you want to use: in this example, LAmy_aal_roi.mat, RAmy_aal_roi.mat, and BiAmy_AAL_roi.mat
1. When it asks "Use SPM design?" select "Yes"
1. When it asks "Images from:" select "SPM design"
