---
title: "Week 4 Problem Set"
permalink: /docs/w4ps/
last_modified_at: 
2018: Week 9
---
**PSET #4**

ASSIGNED: Friday 01 May 2020

DUE: 5:00p Pacific 01 May 2020

**NOTES:**

- Given the unique circumstance of Spring 2020, we ask you to do your best to maximize your learning. Each problem set is an opportunity to assess your learning, identify gaps, reflect on what you have learned, and determine what you wish to learn next.
- Problem sets must be completed individually unless stated otherwise.
- Please turn in your completed problem sets as an electronic copy via Gradescope. Please make sure to clearly indicate the starting and ending boundaries of your answers to each question on Gradescope.
- Please do not go over any word limits and where appropriate show your work (e.g., calculations with appropriate units).
- Please **type** your answers when possible.  
- Please **label** and provide descriptions for the figures. 


GOAL: Reflect on the role of **Abstraction** as a tool for helping to manage complexity in biological systems.  

## (Q1) Generic System Architecture (15 pts)

In class you encountered the **Generic System Architecture** composed of: 

  - Sensors (to measure properties or inputs), 
  - Logic Unit (to process information measured via sensors), and 
  - Actuator (that can act or output the desired result). 

We can apply this same architecture to abstract a diversity of systems.
For example, imagine yourself riding your bicycle on University Avenue and encountering a stop sign. 

In one scenario you can describe yourself as the system.  In this case, your eyes are the sensor, your brain is the computation unit, and your hands are the actuator (i.e., pressing the levers to stop your bike).  

In another scenario, you can describe your bike as the system.  In this case, the levers are the sensors. There is no computation unit, and the signal is directly transferred via a cable to the brakes (i.e., actuators on the wheels).  

**Q.1.a.** Look around the world from the perspective of an integrated systems engineer. Find an example of an integrated system, either natural or engineered. Submit a photo of the system you found and provide a one line description of the system itself. 

**Q.1.b.** Draw the generic system architecture with appropriate units for your system. Label the input(s) and output(s) to the system. 

**Q.1.c.** Revisit [Acoustic reporter genes for noninvasive imaging of microorganisms in mammalian hosts](https://www.nature.com/articles/nature25021) paper.  Draw a generic system architecture that describes the cells with an acoustic reporter.

Note: If you want to learn more  about abstraction, sensors, and actuators in living matter check out **BIOE 44: Fundamentals for Engineering Biology Lab** 

## (Q2) CHOMP Circuits (20 pts)

Referring back to class, recall the hierarchy based on the Part (bioparts), Devices, and Systems approach to abstraction. 
If you need a refresher, please use the following [link](https://parts.igem.org/Abstraction_Hierarchy).

**Q.2.a.**  In your own words provide brief definitions for Parts, Devices, and Systems. (1 sentence each)

Briefly read the abstract from the paper titled: [Programmable protein circuits in living cells](https://science.sciencemag.org/content/361/6408/1252.long). 

**Q.2.b.** n your own words, summarize the abstract in 2-3 sentences. What is the main claim of this paper? (1-2 sentences)

**Q.2.c.** What are the primary evidence in support of the claim?(1-2 sentences)

**Q.2.d.** Take a look at Figure-1 below  (reporduced from the paper). Briefly describe what are the inputs and the output to this logic device? (Bullet points)

**Q.2.d.** Does the presented logic device (Figure-1) use a *Common Signal Carrier*? Why or Why not? (1-2 sentences)

<figure>
<a href="/assets/images/Pset3-LogicGate .png"><img src="/assets/images/Pset3-LogicGate .png"></a>
<figcaption><b>Figure 1</b>. Logic Device diagram of CHOMP circuits.</figcaption>
</figure>

## (Q3) Unknown genetic circuit (10 pts)

Take a look at the following, genetic circuit.  

**Q.3.a.** What are the circuit input(s) and output(s)?

**Q.3.b.** Complete the following time trace diagram. What happens to the GFP signal after  $\sigma70$ is added to the circuit? 

<figure>
<a href="/assets/images/PSET4-2020-FIG1.png"><img src="/assets/images/PSET4-2020-FIG1.png"></a>
<figcaption><b>Figure 2</b>. Unknown genetic circuit.</figcaption>
</figure>

**Q.3.c.** Describe the behavior of this circuit via a name (e.g., AND gate, NAND gate, Toggle switch)?

## (Q4) Toggle switch (X pts)

The toggle switch is a common network motif that can be implemented as a genetic circuit. Two inputs are used to switch the system between two stable states. A diagram of the gene-regulatory network is shown below.

A transcriptionally represses B, while B transcriptionally represses A. B also represses the reporter molecule C. SM1 is a small molecule that allosterically inhibits repression of B by A, while SM2 is a small molecule that allosterically inhibits repression of A by B.

**Q.4.a**  Describe the overall behavior of the system. What are the inputs? What are the two states? How does the system state respond to the given inputs?

**Q.4.b** Given the following toolkit, label the gene-regulatory network diagram with the corresponding part names. You should choose parts that can work together to achieve the overall system behavior you described in Q.4.a
- What part did you assign to A?
- What part did you assign to B?
- What part did you assign to C?
- What part did you assign to SM1?
- What part did you assign to SM2?

<table>
  <tr>
    <td> **Part name** </td>
    <td> **Description** </td>
  </tr>
  <tr>
    <td>tetR</td>
    <td>Repressor from the tet operon</td>
  </tr>
  <tr>
    <td>tetO</td>
    <td>Operator from the tet operon</td>
  </tr>
  <tr>
    <td>doxycycline (dox)</td>
    <td>Small molecule that binds to tetR</td>
  </tr>
  <tr>
    <td>lacI</td>
    <td>Repressor from the *lac* operon</td>
  </tr>
  <tr>
    <td>lacO</td>
    <td>Operator from the *lac* operon</td>
  </tr>
  <tr>
    <td>IPTG</td>
    <td>Small molecule that binds to lacI</td>
  </tr>
  <tr>
    <td>GFP</td>
    <td>Green fluorescent protein</td>
  </tr>
</table>

**Q.4.c** Use the toolkit and the DNA templates below to implement the toggle switch according to your labeled gene-regulatory network from Q.4.b.

## Extra resources, learning, and Practice Questions

The following suggested reading and questions are 100% optional additional. They are meant to help you engage with various aspects of the topics that we have covered in each segment based on your interest and level. They are not required as part of your problem sets. But we hope that they enable you to enhance your learning based on your interest.

### Q.EX1.Navigating the Abstraction Hierarchy (0 pts)

Recall from the class that we can use abstraction to help and manage complexity in engineering biological systems. 

**Q.EX1.a.**  Imagine an engineered living system with a function of your choice.  What does this system do?
 Example engineered bacteria (*E.coli* for example) to detect lead or arsenic and produce a color pigment (red for lead, purple for arsenic) (1-2 sentences)

**Q.EX1.b.**  Sketch a black box “device-level” systems diagram that would implement your system.  

**Hint:** Your boxes should have simple names, such as “change color,” “detect lead,” “OR,” or whatever human-defined functions are needed and appropriate.  Make sure also to connect each black box device to the others as needed.    

Next, going down the abstraction hierarchy, you need parts.  Where to get parts?  How about a student-produced collection of thousands of DNA parts.  Sure! Go to the [iGEM Parts Registry](http://parts.igem.org/Catalog).  

**Q.EX1.c.** Find parts that could be used to implement your device.  Share the name of those parts as part of PSET-3.  
If you can’t find what you need, make a note and move on.

**Q.EX1.d.**   Sketch how your parts should be organized as DNA elements in relation to one another so that they would implement the function as you desire.  Draw a black box around your parts.  Add inputs and output arrows to the box as appropriate. Are your input and output signals generic or specific to your device?

### Q.EX2.  Buggy Bacterial Flash Mob? (0 pts)
 
 Students at MIT are claiming that they have designed a genetic program to realize 
 arepeating bacterial flash mob.  See their work yet again via:
 
[Polkadorks, iGEM-2006](https://2006.igem.org/wiki/index.php/IAP2004:Polkadorks)
 
In an epic East Coast versus West Coast technology “battle,” some of your colleagues
are now claiming that the genetic program designed at MIT won’t actually produce the
so-desired behavior.  Looking only at their proposed “device-level system diagram”...

**Q.EX2.a.** What do you think?  Will their program work or not?   

YES or NO (circle one)

**Q.EX2.b.**  Why or why not? (bullet points) 

### Q.EX3. Inverters and Ring Oscillator (0 pts)

Imagine that you are a system level **Bioengineer** designing genetic inverters and ring oscillators.

**Q.EX3.a.** Draw a box diagram of a genetic inverter at the *parts & device levels*. Describe the behavior of the genetic inverter. 

**Q.EX3.b.** Imagine that you are building a 3-inverter genetic ring oscillator at the *systems level*. Describe the role of *Common Signal Carriers* in constructing such a system (2-3 sentences and use diagrams and drawings if helpful).  





