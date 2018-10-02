# BatchColoc: Imaris batch for fluorescent signal colocalization
A custom MATLAB script for proliferated cancer cell fluorescent signal 
colocalization. 

This script works independently from Imaris as an Imaris extention. It 
requires the user to have a good level of familiarity with Imaris.
The general workflow can be summaried as follows:
  - Preprocessing: background subtration
  - Create surfaces for fluorescent signals from each channel
  - Create masks from Surfaces created above
  - Create surfaces for colocalized signals (both double and triple coloc)
  - Export statistics 

## Parameters:
  - Users need to modify parameters in section "Create surfaces for each
    channel" and "Create colocalization surfaces" accordingly.

## Preconditions:
  - ImarisLib.jar (which normally locates in the XTensions folder in the
    Imaris installation directory) needs to be put in the same folder.
  - Imaris needs to be running when executing the following code. 

**(C) Copyright 2018, All rights reserved**          

**Waitt Advanced Biophotonics Core, Salk Institute for Biological Studies, 10010 N Torrey Pines Rd., San Diego, CA 92037, The United States**

**Linjing Fang, May 2018**
