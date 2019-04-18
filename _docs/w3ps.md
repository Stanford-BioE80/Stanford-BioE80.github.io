---
title: "Week 3 Problem setslass"
permalink: /docs/w3ps/
last_modified_at: Feb.20.2019
2018: Week 6 
toc: true
---
**DUE:** Next Friday (April.26), beginning of class via Gradescope.

**NOTES:** 
  - All BIOE.80 problem sets must be completed individually unless plainly noted opetherwise.
  - Please turn in your completed problem sets as an electronic copy via **Gradescope**. 
  - Please make sure to not go over the word limits, provide figure captions, and when appropriate show your work (e.g., 
  calculations). 
  
GOAL: Reflect on the role of **Abstraction** as a tool for helping to manage complexity in biological systems.

## (Q1) Generic System Architecture (30 pts)

In class you encountered the Generic System Architecture composed of: 

Sensors (to measure properties or inputs), Logic Unit (to process information measured via sensors), and Actuator (that can act or output the desired result). 

We can apply the architecture to abstract diversity of systems.
For example, imagine yourself riding your bicycle on University Avenue and encountering a stop sign on the road. 

In one scenario you can describe yourself as the system.  In this case, your eyes are the sensor, your brain is the computation unit, and your hands are the actuator (pressing the levers to stop your bike).  

In another scenario, you can describe your bike as the system.  In this case, the levers are the sensors. There is no computation unit, and the signal is directly transferred via a cable to the actuators breaks on the wheels.  

**Q.1.a** Pick a scenario of your own choice (include a photo if applicable). Define the system in this scenario. 

**Q.1.b** Draw a generic system architecture with appropriate units.   

## (Q2) GOOP Tube (50 pts)

On Friday you were given two GOOP tubes, one tube of DNA (instructions to express GFP), and one tube of water.

**Q.2.a.** Did you show up on Friday and participate in the activity? (Yes / No) 

**Q.2.b.** When and where did you add the water and DNA-expression to your GOOP tubes? 

**Q.2.c.** Did the GOOP with expression instructions turn green (produce GFP)? How long did it take? 

(Your grade does not depend on the expression of GFP). Include photos of both tubes at the start, mid-way (about 6 hours), and after 12 hours. (Time points don't have to be exact. Simply report when you took the photos.) 

Make sure to provide figure legends. 

**_Please give us feedback. Did you run into any problems?_**

**Q.2.d.** Why might certain designs work in GOOP, but not in a cell?  Why might certain designs work in a cell, but not in GOOP? (2-3 sentences) 

**Q.4.e. Revisiting Design Tools (PyMol).**

Add a screenshot of your GFP structure in PyMol with the chromophore highlighted in red (see week-3 in class instructions). Why do you think the structure (barrel structure) might be necessary around the chromophore? (bullet points) 



## Extra learning (100% optional):

If you want to explore more: a different type of DNA logic mentioned briefly in class, please check out this video from Prof. Endy on how to to engineer Boolean integrase Logic (BIL) gates based on DNA flipping... 
[Transcriptors & Boolean Integrase Logic (BIL) gates, explained](https://www.youtube.com/watch?v=ahYZBeP_r5U).


## (Q6) Patterns with Logic (0 pts)
 
Your goal is to engineer patterns in tissues using proteins delivered by the platform shown in Figure-1 (below). The platform itself consists of two channels (purple and
green) through which proteins (inputs) are supplied continuously. In between the two channels sits a chamber containing
engineered tissue (pink). Proteins from each 
channel can slowly move laterally throughout the developing tissue. When the protein inputs are sensed by cells
within the tissue the cells respond according to whatever genetic logic is operating in each cell.

The concentration gradient of each protein A and B is given on the right in Figure-1 for a cross-section of the device. Values of A or B above the dotted line can be considered ‘1’ or ‘ON’, and values below can be considered ‘0’ or ‘OFF’. 



<figure>
<href="/assets/images/PSET-3.fig1.png"><img src="/assets/images/PSET-3.fig1.png">
<figure >
  
**Figure-1** Platform to engineer patterns in tissues via protein inputs.
  
Consider two different genetic logic devices (AND, XOR) that are responsive to proteins A and B as inputs and that produce an output C. For each, use 1-2 sentences to describe the logic being implemented in words. Then sketch the signal (in this case, concentration) for the expected output (C) for each device as a function of input concentrations (Draw on the figures below or sketch your own chart of concentration vs. position in the device). 

**Hint** For each logic gate, "truth tables" or input/output relationships are given. Use the corresponding truth table for the AND and XOR devices. 


<figure>
<href="/assets/images/PSET3.fig2.png"><img src="/assets/images/PSET3.fig2.png">
<figure >

**Figure-2** Cells with genetic logic devices-1: AND Gate.


<figure>
<href="/assets/images/PSET3.fig3.png"><img src="/assets/images/PSET3.fig3.png">
<figure >

**Figure-3** Cells with genetic logic devices-2: XOR Gate.
 

***(Q5)  Buggy Bacterial Flash Mob? (0 pts)***
 
 Students at MIT are claiming that they have designed a genetic program to realize 
 arepeating bacterial flash mob.  See their work yet again via:
 
[Polkadorks, iGEM-2006](https://2006.igem.org/wiki/index.php/IAP2004:Polkadorks)
 
In an epic East Coast versus West Coast technology “battle,” some of your colleagues
are now claiming that the genetic program designed at MIT won’t actually produce the
so-desired behavior.  Looking only at their proposed “device-level system diagram”...


**5.a**. What do you think?  Will their program work or not?   


YES or NO (circle one)


**5.b.** Why or why not? (bullet points) 

## (Q3) Inverters and Ring Oscillator (0 pts)

Imagine that you are a system level **Bioengineer** designing genetic inverters and ring oscillators.

**Q.3.a.** Draw a box diagram of a genetic inverter at the *parts & device levels*. Describe the behavior of the genetic inverter. 
(2-3 sentences and use diagrams and drawings if helpful). 

**Q.3.b.** Imagine that you are building a 3-inverter genetic ring oscillator at the *systems level*. Describe the role of *Common Signal Carriers* in constructing such a system (2-3 sentences and use diagrams and drawings if helpful).  
