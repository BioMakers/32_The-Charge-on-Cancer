# 32_The-Charge-on-Cancer
Using Induced Dipole Moment to Electrostatically Separate Healthy and Cancer Cell-Metal Nanoparticle Complex

## Panel Figure
![](/Images/Banner.png?raw=true)

## Synopsis
Current nanotechnology based strategies have introduced a number of nanoparticles of variable chemistry and architecture for cancer diagnosis and treatment. Although these nanoparticles are designed to safely reach their target and specifically release their cargo at the site of the disease they are not effective because their cargoes are usually chemical drugs whose mechanism of action are unknown. Here by using special ferromagnetic nanoparticles we propose a method based on a physical technique that we have developed to separate and kill cancer cells without causing damage to normal cells. The physical technique is the ability to induce magentic dipole moment using electric fields and separate the magnetised nanoparticles that would be bound to the cancer cells.  

## Team

<img src="Images/Prabakaran-338_Final1.jpg" alt="alt text" width="50%" height="50%">

![Dr. Sudhakaran Prabakaran](Images/Prabakaran-338_Final1.jpg "Dr. Sudhakaran Prabakaran")
![Dr. Sanjiv Sambandan](Images/Sanjiv-Sambandan.jpg "Dr. Sanjiv Sambandan")

## Workflow
The proposal explores the use of electric fields to segregate cancer cells using conductive nanoparticles. The technology being explored consists of two parts: 

1. Binding of cancer cells with nanoparticles
2. The technique to move the cancer cell-nanoparticle complex

## Background

## Electrostatic Alignment of Metallic Particles:
If a dispersion of conductive metallic particles in an insulating fluid is contained in an environment bathed in an external electric field, the field polarizes the conductive particles allowing some of them to move and chain up due to dipole-dipole attractive forces. This phenomena is described in the figure below and has been used for engineering applications such as self healing circuits. 
Therefore, electric fields can be used to move and cluster metallic particles.
References: http://dx.doi.org/10.1063/1.4958729; http://dx.doi.org/10.1063/1.4916513; 10.1109/TED.2012.2191557

![](/Images/Clustering-of-cells.png?raw=true)

## Forming Metallic Nanoparticle- Cancer Cell Complex:
We will use ferromagnetic nanoparticles coated with antibodies that will detect cancer cells specifically, for example antibodies that recognize newly formed blood vessel that aid in cancer development or antibodies that detect cancer stem cells. These nanoparticles will attach themselves to the cancer stem cells forming a metallic nanoparticle – cancer cell complex.

## Software
No specific software. If scripts are eventually needed we will use MATLAB and they will be made available in this Github account. 

## Hardware
There are no hardware components needed for this project - although some heavy duty engineering equipments will be used.
1. To fabricate the electrodes we have used a DC sputtering system. The fine gaps between the electrodes (10um to 100um with +-1um accuracy) were created using photolithography that requires the use of a Mask Aligner and UV exposure.
2. To measure we will use a probe station with a semiconductor parameter analyzer.
The electrodes are ready and we have access to the measurement setup.

## Biological Materials

1. Jurkat T Cells
2. Ferromagnetic nanoparticles coated with avidin
3. Biotin labeling kit
4. Antibody targetting specific antigen expressed by Jurkat T cells

(The details of these materials are given in the subfolder)

## The Methodology is as follows: 
Step 1: Fabricate Electrodes (spacing about 1000 micron) on a printed circuit board. A voltage will be applied across these electrodes to establish an electric field in the gap.

Step 2: Grow normal and cancer cells in co-cultures and drop cast these cells on the substrate to create an in vitro cell culture (Panel Figure, Left).  

Step 3: Bind metal nanoparticles with antibodies (using avidin-biotin reaction) and drop cast them onto the substrate. The metallic nanoparticles would then target the cancer cells specifically based on specific antigen expressed by Jurkat T cells. 

Step 4: Apply the electric field. Due to the mechanism described in Panel Figure, the metal nanoparticles will cluster thereby pulling the cancer cells with them. Thus cancer cells will be separated from healthy cells. 

## Benefits and outcomes 
1. Existing methods to deliver drugs using nanoparticles to kill cancer cells do not kill cancer cells completely because the mechanism of cancer initiation and spread is not completely understood. 

2. Our proposed method uses electric fields acting on metallic nanoparticles attached specifically to cancer cells to separate and cluster cancer cells. These cells can now be destroyed without having a significant impact on the healthy cells.

## Potential Risks and Mitigation: 
Without the use of fine feature fabrication, access to a fully controllable waveform – the electric field will be too low (gap between the electrodes too large) and the segregation may not be possible. Nevertheless, we will attempt to use fully insulating dispersion media to enhance electrostatic forces. 

## License
None yet!
Copyright 2017 Sanjiv Sambandan and Sudhakaran Prabakaran


