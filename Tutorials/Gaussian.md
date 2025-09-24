---
title: "Gaussian"
layout: page
---

## Input Generation using Avogadro

- Install Avogadro
    - Visit the Avogadro site and go to Download
    - Once downloaded, run the setup file to install the software

Note: There are different tools needed for utilising software, for instance Draw, Navigation, Manipulation, and selection Tool. These tools will appear in the toolbar, If not there, go to Settings &rarr; Toolbars and check the Tools option. A detailed description of tools is given in [Avogadro website](https://avogadro.cc/docs/tools/draw-tool/). 

- We will generate input for osmocene as an example in **Avogadro:1.2.0**
    - In Avogadro, go to Build &rarr; Insert &rarr; fragemnt
    - Search the fragment cyclopentadienyl and click on inset; it will appear in the GUI
    
      Figure1
    
    - Go to Edit &rarr; Copy or press Ctrl-C; It will copy the selected fragment
    - Paste the copied fragment using Edit &rarr; Paste or Ctrl-V
    - The pasted fragment will be on top of already kept Cp fragment but it will be in selected mode.
    - For a sandwich structure, we have to translate one Cp ring by ~3.0 angstrom in Z-direction. We can do the translation using the translate option under Manipulate Settings.
 
      Figure 2
      
    - The manipulate settings box will also appear automatically after pasting on left side, If not then we can get it by going to Settings &rarr; Toolbars &rarr; Manipulate Settings.
    - Once the rings are apart we need metal in the middle; remove the fragment selection by going to select &rarr; select none or Ctrl-Shift-A.
    - Rotate the rings such that they cover each other fully (eclipse); now click on the Draw tool and change element to osmium from the draw setting on left select any one of the atom in the middle of the ring.
 
      Figure 3
 
    - Select Manipulation tool, i.e., in shape of a hand and then rotate the molecule such that both rings are visible from side angle.
 
      Figure 4
 
    - Select Selection tool, i.e., in shape of an arrow, and select the other dummy atom and then press delete.
    - Select the osmium atom now, and then using manipulation tool move it along z axis such that it appears in the middle.
 
      Figure 5
 
    - Go to selection tool and right click on empty place to remove the selection (or press Ctrl-Shift-A); then using manipulation tool rotate the molecule to visualize the metallocene from your choice of angle.
 
      Figure 6
 
    - To generate input file; go to Extensions....
      
- A detailed manual is given at https://avogadro.cc/docs/

