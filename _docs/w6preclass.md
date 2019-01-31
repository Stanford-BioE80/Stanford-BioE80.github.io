---
title: "Wee6 5 Preclass- Abstraction"
permalink: /docs/w6preclass/
---

# Week 6 Preclass

Please read and consider the below before start of class on Monday.
The questions given are only study questions not homework to be graded.
Talk about it all with your classmates, friends, or TAs, as you like.

_______________________________________________________________________

## Preclass for Monday

## Introduction: Abstraction as a tool for managing complexity in bioengineering.

Welcome to the pre-class material for Abstraction as a tool for managing complexity in bioengineering. 

**Goal-1:** After Week 6 you will able to describe the role of abstraction as a tool for helping 
to managecomplexity in biological systems - with an emphasis on the design step of the engineering cycle.

**Goal-2:** You will also be able to apply abstraction (in the form of black box diagrams) to decompose 
or synthesize the designs systems that could then be implemented in living matter for example viaengineered 
(i.e., designer) DNA.

## Example-1:  Bacterial Flash Mob

**Write down the DNA sequence** encoding a dynamic bacterial flash mob (see animation below in Figure.1 )

**Q.1. What is the first base of your DNA program?  A, T, C, or G?  
(Note: Do not spend more than 100 seconds pondering and answering this question.  Time’s up!).**  

**ADD GIF here**
*Figure 1.  Dynamic bacterial flash mob.* 
A collection of engineered bacteria (black dots)move randomly in two dimensions.One cell activates randomly, turns red, and secretes a diffusing attractant molecule (green circle).All other cells sense and move towards the source of the attractant.After a period of time all cells return to their original stateuntil the process repeats over and again.

**Q.2. Why is Q1 a difficult question to answer?**   
(Hint: Consider the difference between what you do and what must physically occur to use a smartphone to take a photograph and send an image to your best friend via text message.  Are you ever typing 0s and 1s into your phone?  What’s happening instead?)


One simple-but-powerful and general-purpose approach for organizing engineered systems is shown on the next slide.  Forexample, a computer has a keyboard that receives input via keys (sensors), performs logical operations (computation), andcan output via a display, printer or other device (actuation).  As a second example, a pilot can control a Boeing 787 airplaneby moving the yoke, whose inputs are combined with other inputs collected by additional sensors (e.g., air pressure), andthen a flight computer determines what the actuated flight surfaces on the wings and tail physically do, as controlled by a“fly-by-wire” system.


Note that our thinking about such systems can quickly become complicated by the details of any one example, but thateach example follows a similar pattern; inputs are received by one or more sensors; so-received information is computedupon as needed via an intermediate process; and finally some action is taken.  Please also note that in more complicatedsystems the output of a system can itself be an input, creating a “loop” or feedback to realize more sophisticated dynamics(e.g., repeating or other dynamically controlled behaviors, such as in the case of the looping bacterial flash mob).


**ADD Fig-2 here**
*Figure 2.  Generic system architecture.*  
A sensor measures environmentalproperties or inputs  (for example: a keyboard) and transfers this information to a computer (logic unit) to be processed. The results are then transferred to an actuator (e.g., a printer or a display) that can output these results.


This same framework can be applied to help manage the engineering of biological systems.Stated differently, the desired behavior of a complicated biological process can be represented at an intermediate level ofabstraction via a simpler-to-understand  “black box” diagram.


**Q.3. Revisit to the bacterial flash mob and develop a device-level block diagram that would result in the so-shownbehavior.  Label simple sensors, logic blocks, and actuators, as needed.  Connect outputs to inputs (i.e., connectboxes together via ines) where and as required.**  
(Hint: Only give simple device names (e.g., “coin flip,” “turn red,” etc.);do not describe any biology in any molecular detail).


**Key Concept:** What we are practicing via this generic system architecture is called **abstraction**. 
Abstraction is a tool that allows engineers (and others) to modularize and manage the complexity of a system. Abstraction establishes a level of simplicity at which a person interacts with the system, temporarily hiding more complex details for later consideration, only if and as such details must be considered.  


**ADD Fig-3 here**
From a different perspective, note how George Boole observed ways in which human language results in a type of abstraction that can be used to organize and link our experiences to actions.  For example: if it is raining AND snowing then bundle up OR if it is warm ANDsunny then go the beach.


But, returning to the Bacterial Flash Mob example.

**Q.4. When we go to actually implement any sensor, computer, or actuator, what exactly is inside the boxes?  Are there actually black boxes inside a cell?  What “wires” connect one box to another?**

These are challenging questions that we will resolve starting Monday!

*Useful Additional Resource:* 
Check out this free comic bolok that starts out simple but quickly begins to develop answers to **Question-4**
[Adventures in Synthetic Biology](https://openwetware.org/wiki/Adventures)


