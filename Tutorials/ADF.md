---
title: "ADF"
layout: page
---
In the IPC cluster (troglodyte), AMS-2021 is already installed and running. We will use the AMS-GUI utility AMSINPUT for the generation of input files (.run, .ams) and AMSVIEW for visualisation of output file (.rkf).

Let us understand the software with an example of fragment analysis of osmocene with the following steps:
1. Software Initiation:
    1. 
3. Importing xyz file:
    1. Create an xyz file with coordinates of your choice of molecule. Example: [osmocene.xyz](ADF-files/osmocene.xyz)
    2. Go to File &rarr; Import Coordinates &rarr; in dialogue box go to the folder where xyz file is and click open
       ![Importing coordinates from xyz](ADF-files/adf1.png)
4. Symmetrize, if possible, and generate fragments:
    1. After importing all the atoms are selected, click on empty white place to remove selection. Click on the star icon at bottom to symmetrise the molecule to nearby symmetry.
       ![Symmetrize]()
    2. Click on the atoms for fragment 1, for instance Os in case of osmocene, for its selection. If there is a need of selecting more than one atom for the fragment, then the selection can be done either manually or by selecting one atom and then ctrl-D to select atom connected to it in order to expand the selection. Check the total number of atoms that are selected at bottom right in graphics to double check the selection.
    3. Click on Model &rarr; Regions and then click on + symbol, left to Regions, to create a region; you will see all the selected atoms are now in Region_1 with some color in the graphics. For instance, Os is in red in our case.
       ![Region_1]()
    4. To select the atoms for fragment 2, we can go to Select &rarr; Invert selection and then click on + symbol, left to Regions, to create Region_2. Both the fragments are now defined.
       ![Region_1-and-Region_2 selected]()
    5. Go to Main &rarr; Task &rarr; Single Point and then click on arrow at the end of Task line. It will take us to the fragment page, we can also reach here by going to MultiLevel &rarr; Fragments. Check the box yes for Use Fragments. In this example both fragments are even numbered and neutral, we can try other possiblity too by changing charge and spin for Region_1 and Region_2.
       ![Fragments electronic-state]()
    6. The fragments can be of higher electronic state, in that case one fragment has to have alpha spin and other one has to have beta to cancel out and maintain singlet state for the whole molecule. For instance, in osmocene with fragments in triplet.
       ![Fragments_triplet]()
       Remember in this case, the overall calculation will be in unrestricted mode, check the unrestricted box in Main. 
    8. Another possiblity is to have fragments with odd electrons. In osmocene with
  
5. /home/edjcomm/gaurav/CpOsB6H11/CpOsCp
