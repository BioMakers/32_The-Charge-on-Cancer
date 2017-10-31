# 32_The-Charge-on-Cancer
Using Induced Dipole Moment to Electrostatically Separate Healthy and Cancer Cell-Metal Nanoparticle Complex
![](/Images/Banner.png?raw=true)

## Synopsis

The current nanotechnology based strategies have introduced a number of nanoparticles of variable chemistry and architecture for cancer diagnosis and treatment. Most nanoparticles are designed to safely reach their target and specifically release their cargo at the site of the disease. But these cargos are usually coated with chemical drugs and most anticancer drugs do not kill cancer cells completely because the mechanism of cancer initiation and spread is not completely understood. Our proposed method based on physical techniques – particularly the use of electric field to induce dipole moments - have a better chance at segregating, separating and killing cancer cells without causing damage to normal cells. 

![Dr. Sudhakaran Prabakaran](Images/Prabakaran-338_Final1.jpg "Dr. Sudhakaran Prabakaran")
![Dr. Sanjiv Sambandan](Images/Prabakaran-338_Final1.jpg "Dr. Sanjiv Sambandan")


## Software
Software will be needed to control the arduino uno unit that is controlling the potentiostat circuit and the feedback circuit to control the pump. Several supporting software such as a desktop GUI to display data from the potentiostat and simulations will also be written




## Proposal
The proposal explores the use of electric fields to segregate cancer cells using conductive nanoparticles. The technology being explored consists of two parts: (i) The technique of embedding the nanoparticle with the cancer cells, and (ii) the technique to move the cancer call-nanoparticle complex.


## Hardware
Electrostatic Alignment of Metallic Particles:
If a dispersion of conductive metallic particles in an insulating fluid is contained in an environment bathed in an external electric field, the field polarizes the conductive particles allowing some of them to move and chain up due to dipole-dipole attractive forces. This phenomena is described in Fig. 1 and has been used for engineering applications such as self healing circuits. 
Therefore, electric fields can be used to move and cluster metallic particles.
References: http://dx.doi.org/10.1063/1.4958729; http://dx.doi.org/10.1063/1.4916513; 10.1109/TED.2012.2191557

Forming Metallic Nanoparticle- Cancer Cell Complex:
We will use ferromagnetic nanoparticles coated with antibodies that will detect cancer cells specifically, for example antibodies that recognize newly formed blood vessel that aid in cancer development or antibodies that detect cancer stem cells. These nanoparticles will not attach themselves to the cancer cells forming a metallic nanoparticle – cancer cell complex.
Therefore, the cancer cells are attached to metallic particles while healthy cells are not.


![](/Images/Clustering-of-cells.png?raw=true)

## The Methodology is as follows: 
Step 1: Fabricate Electrodes (spacing about 1000 micron) on a printed circuit board. A voltage will be applied across these electrodes to establish an electric field in the gap.
Step 2: Grow normal and cancer cells in co-cultures and drop cast these cells on the substrate to create an in vitro cell culture (Fig. 2, Left).  
Step 3: Coat metal nanoparticles with antibodies and drop cast them onto the substrate. The metallic nanoparticles would then target the cancer the cells specifically.
Step 4: Apply the electric field by turning on the power supply. Due to the mechanism described in Fig. 1, the metal nanoparticles should cluster and thereby pull the cancer cells with them, thereby achieving segregation and separation from healthy cells.


### Electronics

## License

Copyright 2017 Sanjiv Sambandan and Sudhakaran Prabakaran

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
