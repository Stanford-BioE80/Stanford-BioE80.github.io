---
title: "Week 3 Problem setslass"
permalink: /docs/w3ps/
last_modified_at: Feb.20.2019
2018: Week 6 
toc: true
---
**DUE:** Next Friday(April.26), beginning of class via Gradescope.

**NOTES:** 

All BIOE.80 problem sets must be completed individually unless plainly noted opetherwise.

Please turn in your completed problem sets as an electronic copy via Gradescope.

Please make sure to not go over the word limits and when appropriate show your work (e.g., calculations).

GOAL: Reflect on the role of **abstraction** as a tool for helping to managecomplexity in biological systems.

  ## (Q1) Patterns with Logic
 
Your goal is to engineer patterns in tissues using proteins delivered by the hardware
platform shown in Figure-1 (below). The platform itself consists of two channels (purple and
green) through which proteins (ligands) are supplied continuously. A chamber in which
engineered tissues develop (pink) sits between the two channels. Proteins from each channel
can slowly move (diffuse) throughout the developing tissue. When the protein ligands are sensed by cells
within the tissue the cells respond according to whatever genetic logic is operating in each cell.

The concentration gradient of each protein ligand A and B is given in Figure-1. Note that values of A or B above the dotted line can be considered ‘1’ or ‘ON’, and values below can be considered ‘0’ or ‘OFF’. 

**Figure-1** 
<figure>
<href="/assets/images/PSET-3.fig1.png"><img src="/assets/images/PSET-3.fig1.png">
<figure >
	
Consider two different genetic logic devices (AND, XOR) that are responsive to proteins A and B as inputs (“truth tables” or input/output relationship are given for each gate). Sketch the expected output (C) for each device as a function of the A and B inputs (draw on the figure below if useful). 

**Hint-1** For each logic gate use the corresponding truth table.

**Hint-2** Each logic gate takes in two inputs, ligands A and B, then computes some output C to realize a spatially defined pattern across the population of cells (pink). 

**Figure-2** Cells with genetic logic devices-1: AND Gate.
<figure>
<href="/assets/images/PSET3.fig2.png"><img src="/assets/images/PSET3.fig2.png">
<figure >

**Figure-3** Cells with genetic logic devices-1: XOR Gate.
<figure>
<href="/assets/images/PSET3.fig3.png"><img src="/assets/images/PSET3.fig3.png">
<figure >
  
## (Q2) GOOP Tube (35 pts)

On Friday you were given two GOOP tubes, one tube of DNA (instruction to express GFP), and one tube of water.

**Q.2.a.** Did you show up on Fridayt? (Yes / No)

**Q.2.b.** When and where did you add the water and DNA-expression to your GOOP tubes. 

**Q.2.c.** Did the GOOP with expression instructions turn green (produce GFP)? How long did it take? (Your grade does not depend on the expression of GFP). Include photos of both tubes at the start, mid-way (about 6 hours), and after 12 hours. (Time points don't have to be exact. Simply report when you took the photos) Make sure to provide a figure legend. 

**Q.2.d.** Why might certain designs work in GOOP, but not in a cell?  Why might certain designs work in a cell, but not in GOOP? (2-3 sentences) 

**Q.4.e. Revisiting Design Tools (PyMol).**

Add a screenshot of your GFP structure in PyMol with the chromophore highlighted in red (see week-3 in class instructions). Why do you think the structure (barrel structure) might be necessary around the chromophore? (bullet points) 

**_Please give us feedback. Did you run into any problems?_**


## (Q3) Ring Oscillator (0 pts)

Draw a device system level diagram of a 3-inverter Ring oscillator. Think back to the class on Wednesday, imagine that you are a system's level **Bioengineer** designing an oscillator...

5.a. What is an ideal inverter from a systems level perspective? (bullet points and a simple diagram to describe inputs and outputs for the inverters) (5 points)

5.b. Provide an example of a bad design choice, from system's level view, for these inverters? (Ring oscillator should still work) (5 points)

## (Q4) Approximate and rapid numerical estimates (40 pts)

Approximations based on simple physical principles are known as Fermi problems. These problems will help you build quantitative intuition for working with biology. Most of these estimates are rough: they are designed to give you a broad, order of magnitude intuition for the biology, so keep in mind that that the exactly correct number could be different. Give your answers to two significant figures and provide units where appropriate. You should only need simple math and arithmetic; a couple of lines of work at most. 

Additional resources: bionumbers is an excellent source for biological numbers [link](http://bionumbers.hms.harvard.edu/) . "_Cell Biology by the Numbers_" is a great book on estimation problems in biology. You can get a free copy of the draft version [here](http://book.bionumbers.org/).

_Escherichia coli_ (**Figure 1**) is well-studied bacteria considered to be representative of how bacterial systems work generally (i.e., a 'model' organism). _E. coli_ is also easy to grow in the lab and divides rapidly (about 20 mins). As a result, _E. coli_ is frequently used in bioengineering either as a model organism (to be studied or engineered directly) or as a host to generate large copies of user defined DNA. You will see (and setup your own in BIOE44) cultures tubes of _E. coli_ (with medium - food for bacteria) often growing overnight on shaking incubators (set to 37C) (**Figure 2**).

<figure>
<a href="/assets/images/w2pc_ecoli.png"><img src="/assets/images/w2pc_ecoli.png"></a>
<figcaption><b>Figure 1</b>.
<i>E. coli</i> is shaped like a rod, which we can approximate as a spherocylinder: a cylinder with hemispherical caps. Of note, MG1655 is a strain derived from a lineage of <i>E. coli</i> variants that was originally isolated from a diphtheria patient at the Palo Alto hospital in 1922.
<a href="https://??????????">Source TBD</a>
</figcaption>
</figure>

<figure>
<a href="/assets/images/w2pc_ecoligrowth.png"><img src="/assets/images/w2pc_ecoligrowth.png"></a>
<figcaption><b>Figure 2</b>.
<i>E. coli</i> grown to saturation (after 8-12 hours). <i>E. coli</i> divides about every 20 mins. 
<a href="http://book.bionumbers.org/">Source: Cell Biology by the Numbers</a>
</figcaption>
</figure>

**Q.4.a.** Based on a spherocylinder model, calculate the volume of an _E. coli_ cell. 

**Q.4.b.** If an _E. coli_ cell were the size of a building, how big would a water molecule be?

**Q.4.c.** The mean diameter of a protein is roughly 4 nm. What is the upper bound on how many proteins could fit inside an *E. coli* cell?

**Q.4.d.** How would you go about estimating the total number of carbon atoms in an *E.coli* cell? You don't have to calculate this just define variables and describe your approach step by step. 


**Extra learning** (100% optional):

If you want to explore more re: a different type of DNA logic mentioned briefly in class, pleasecheck out this video from Prof. Endy on how to to engineer Boolean integrase Logic (BIL) gatesbased on DNA flipping... 
[Transcriptors & Boolean Integrase Logic (BIL) gates, explained](https://www.youtube.com/watch?v=ahYZBeP_r5U)

## (Q5) Bacterial edge detection (0 pts)

Building on work first published in 2005, Jeff Tabor and colleagues eventually demonstrated a 
bacterial edge detection system.  In their system a bacterial lawn (i.e., a uniform layer of identically engineered 
bacteria growing on a plate) detect a light-encoded image.  The bacteria are initially all the same but, 
depending on whether they are exposed to light or not, send or receive small molecule-encoded signals that diffuse 
across the light/dark boundary.  Only cells positioned at the boundary between light and dark express an enzyme that 
results in formation of a dark pigment (HINT: see Figure and also the primary 

<figure>
<href="/assets/images/PSET-3.fig1.png"><img src="/assets/images/PSET-3.fig1.png">
<figure >
[source](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2775486/))


5.a. **Develop a device-level block diagram** that would result in the so-shown behavior. Label simple sensors, logic blocks, and actuators, as needed.  Connect outputs to inputsif and as required. (Hint:  Only give simple device names (e.g., “Dark sensor,” “pigment actuator” etc.); do not describe any biology in any molecular detail).  

 ## (Q6)  Buggy Bacterial Flash Mob? (0 pts)
 
 Students at MIT are claiming that they have designed a genetic program to realize 
 arepeating bacterial flash mob.  See their work yet again via:
 
[Polkadorks, iGEM-2006](https://2006.igem.org/wiki/index.php/IAP2004:Polkadorks)
 
In an epic East Coast versus West Coast technology “battle,” some of your colleagues
are now claiming that the genetic program designed at MIT won’t actually produce the
so-desired behavior.  Looking only at their proposed “device-level system diagram”...


1.a. What do you think?  Will their program work or not?   (10 points)


YES or NO (circle one)


1.b. Why or why not? (bullet points) (10 points)


