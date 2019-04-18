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
  - Please make sure to not go over the word limits, when appropriate provide figure captions, and show your work (e.g., 
  calculations). 
  
GOAL: Reflect on the role of **Abstraction** as a tool for helping to manage complexity in biological systems.  

## (Q1) Generic System Architecture (10 pts)

In class you encountered the **Generic System Architecture** composed of: 

  - Sensors (to measure properties or inputs), 
  - Logic Unit (to process information measured via sensors), and 
  - Actuator (that can act or output the desired result). 

We can apply the architecture to abstract diversity of systems.
For example, imagine yourself riding your bicycle on University Avenue and encountering a stop sign. 

In one scenario you can describe yourself as the system.  In this case, your eyes are the sensor, your brain is the computation unit, and your hands are the actuator (i.e., pressing the levers to stop your bike).  

In another scenario, you can describe your bike as the system.  In this case, the levers are the sensors. There is no computation unit, and the signal is directly transferred via a cable to the breaks (i.e., actuators on the wheels).  

**Q.1.a.** Pick a scenario of your own choice (include a photo if applicable). Define the system in this scenario. 

**Q.1.b.** Draw a generic system architecture with appropriate units. Label the input(s) and output(s) to the system. 

## (Q2) GOOP Tube (40 pts)

On Friday you were given two GOOP tubes, one tube of DNA (instructions to express GFP), and one tube of water.

**Q.2.a.** Did you show up on Friday and participate in the activity? (Yes / No) 

**Q.2.b.** When and where did you add the water and DNA-expression to your GOOP tubes? 

**Q.2.c.** Did the GOOP with expression instructions turn green (produce GFP)? How long did it take? 

(Your grade does not depend on the expression of GFP). Include photos of both tubes at the start, mid-way (about 6 hours), and after 12 hours. (Time points don't have to be exact. Simply report when you took the photos.) 

Make sure to provide figure legends. 

**_Please give us feedback. Did you run into any problems?_**

**Q.2.d.** Why might certain designs work in GOOP, but not in a cell?  Why might certain designs work in a cell, but not in GOOP? (2-3 sentences) 

**Q.2.e. Revisiting Design Tools (PyMol).**

Add a screenshot of your GFP structure in PyMol with the chromophore highlighted in red (see week-3 in class instructions). Why do you think the structure (barrel structure) might be necessary around the chromophore? (bullet points) 

## (Q3) CHOMP Circuits (15 pts)

Briefly read the abstract from the paper titled: [Programmable protein circuits in living cells](https://science.sciencemag.org/content/361/6408/1252.long).

**Q.3.a.** In your own words, what is the primary *claim* of the paper? (1-2 sentences)

**Q.3.b.** Take a look at Figure-1 below  (reporduced from the paper). Briefly describe what are the inputs and the output to this logic device? (Bullet points)

**Q.3.c.** Does the presented logic device (Figure 1) use a *Common Signal Carrier*? Why or Why not? (1-2 sentences)

<figure>
<a href="/assets/images/Pset3-LogicGate .png"><img src="/assets/images/Pset3-LogicGate .png"></a>
<figcaption><b>Figure 1</b>. Logic Device diagram of CHOMP circuits.</figcaption>
</figure>

## (Q4) Navigating the Abstraction Hierarchy (35 pts)

Thinking back to the class recall the hierarchy based on the Part (bioparts), Devices, and Systems approach to abstraction. 
If you need a refresher, please use the following [link](https://parts.igem.org/Abstraction_Hierarchy).

**Q.4.a.**  In your own words provide brief definitions for Parts, Devices, and Systems. (1 sentence each)

Recall from the class that we can use abstraction to help and manage complexity in engineering biological systems. 

**Q.4.b.**  Imagine an engineered living system with a function of your choice.  What does this system do?
(1-sentence. Example engineered bacteria (*E.coli* for example) to detect lead or arsenic and produce a color pigment (red for lead, purple for arsenic).

**Q.4.c.**  Sketch a black box “device-level” systems diagram that would implement your system.  

**Hint:** Your boxes should have simple names, such as “change color,” “detect lead,” “OR,” or whatever human-defined functions are needed and appropriate.  Make sure also to connect each black box device to the others as needed.    

Next, going down the abstraction hierarchy, you need parts.  Where to get parts?  How about a student-produced collection of thousands of DNA parts.  Sure! Go to the [iGEM Parts Registry](http://parts.igem.org/Catalog).  

**Q.4.d.** Find parts that could be used to implement your device?  Share the name of those parts as part of PSET-3.  
If you can’t find what you need, make a note and move on.

**Q.4.e.**  Sketch how your parts should be organized as DNA elements in relation to one another so that they would implement the function as you desire.  Draw a black box around your parts.  Add inputs and output arrows to the box as appropriate. Are your input and output signals generic or specific to your device?

Note: If you want to learn more about abstraction or practice design, build, and test sensors,  and actuators in living matter  check out **BIOE 44: Fundamentals for Engineering Biology Lab** 

## Extra learning (100% optional):

If you want to explore more: a different type of DNA logic mentioned in class, please check out this video from Prof. Endy on how to to engineer Boolean integrase Logic (BIL) gates based on DNA flipping... 
[Transcriptors & Boolean Integrase Logic (BIL) gates, explained](https://www.youtube.com/watch?v=ahYZBeP_r5U).

You can learn more about genetic parts to program bacteria from the paper [here](  https://www.sciencedirect.com/science/article/pii/S0958166906001273?via%3Dihub).

### (Q5)  Buggy Bacterial Flash Mob? (0 pts)
 
 Students at MIT are claiming that they have designed a genetic program to realize 
 arepeating bacterial flash mob.  See their work yet again via:
 
[Polkadorks, iGEM-2006](https://2006.igem.org/wiki/index.php/IAP2004:Polkadorks)
 
In an epic East Coast versus West Coast technology “battle,” some of your colleagues
are now claiming that the genetic program designed at MIT won’t actually produce the
so-desired behavior.  Looking only at their proposed “device-level system diagram”...

**5.a**. What do you think?  Will their program work or not?   

YES or NO (circle one)

**5.b.** Why or why not? (bullet points) 

###  (Q6) Inverters and Ring Oscillator (0 pts)

Imagine that you are a system level **Bioengineer** designing genetic inverters and ring oscillators.

**Q.6.a.** Draw a box diagram of a genetic inverter at the *parts & device levels*. Describe the behavior of the genetic inverter. 
(2-3 sentences and use diagrams and drawings if helpful). 

**Q.6.b.** Imagine that you are building a 3-inverter genetic ring oscillator at the *systems level*. Describe the role of *Common Signal Carriers* in constructing such a system (2-3 sentences and use diagrams and drawings if helpful).  
