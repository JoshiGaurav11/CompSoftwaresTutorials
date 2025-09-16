---
title: "ADF"
layout: page
---
In the IPC cluster (troglodyte), AMS-2021 is already installed and running. We will use the AMS-GUI utility AMSINPUT for the generation of input files (.run, .ams) and AMSVIEW for visualisation of output file (.rkf).

Let us understand the software with an example of fragment analysis of osmocene with the following steps:
1. Software Initiation:
2. Importing xyz file:
    1. Create an xyz file with coordinates of your choice of molecule. Example: [osmocene.xyz](ADF-files/osmocene.xyz)
    2. Go to File &rarr; Import Coordinates &rarr; in dialogue box go to the folder where xyz file is and click open
       ![Importing coordinates from xyz](ADF-files/adf1.png)
3. Symmetrize, if possible, and generate fragments:
    1. After importing all the atoms are selected, click on empty white place to remove selection. Click on the star icon at bottom  to symmetrise the molecule to nearby symmetry.
       ![Symmetrize]()
    2.  Select the atoms for fragment 1, for instance Cp2 in case of osmocene.
       ![Fragment-1 selection]()
