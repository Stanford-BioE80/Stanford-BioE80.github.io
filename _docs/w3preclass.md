---
title: "Week 3 Preclass- Abstraction"
permalink: /docs/w3preclass/
last_modified_at: Feb.20.2019
2018: "Week 6"
---

# Week 3 Preclass
## Abstraction as a tool for managing complexity in bioengineering

Please read and consider the below before start of each class.
The questions given are only study questions not homework to be graded.
Talk about it all with your classmates, friends, or TAs, as you like.

_______________________________________________________________________

## Preclass for Monday

## Introduction: Abstraction as a tool for managing complexity in bioengineering.

Welcome to the pre-class material for Abstraction as a tool for managing complexity in bioengineering. 

**Goal-1:** After Week 3 you will able to describe the role of abstraction as a tool for helping 
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
Check out this free comic bolok that starts out simple but quickly begins to develop answers to **Question-4**: 
[Adventures in Synthetic Biology](https://openwetware.org/wiki/Adventures)


_______________________________________________________________________

## Preclass for Wedensday 

There is no preclass for Wedensday Week-3. 

## Preclass for Friday 

Reader note: The following was shared as the In class instruction for Friday. It might be better to share this as a pre-class. 

## Inclass / Preclass for Friday 


**Part 1:** Reconsider the hypothetical bacterial *“flash mob”* that you encountered in the pre-classmaterial for Monday of this week.  See the animation or text below:

**ADD GIF here**

Or, in natural language, “We start with a collection of engineered e-coli moving randomly inmedia. The bacteria are represented by black dots in the animation. Under control of astochastic element, a few bacteria begin excreting an attractant. These bacteria we will call thesender cells. In the animation we have one sender cell represented by the red dot; the greencircle represents the attractant diffusing away from the sender cell.  Through chemotaxis, aprocess by which a cell along a chemical gradient swims toward or away from the stimulus (anattractant in this case), nearby bacteria start swimming towards the sender cells. These bacteriawe will call the receiver cells. This way, groups begin forming around the original sender cells onthe plate.  Additionally, all bacteria have been engineered with a quorum sensing mechanismwhich effectively senses local cell density. In the groups that have formed, the local cell density eventually reaches a certain threshold. The quorum sensing mechanism of the cells then stopssecretion of any attractant. The existing attractant then diffuses away. Since there is no moreattractant being secreted, the cells will diffuse away and eventually be spread out across theplate once again. Then by the stochastic element a few cells will begin excreting the attractantand the whole process is repeated.  Basically polkadots will form, diffuse, and form again inrandom areas on the plate. Our system should thus form time-varying patterns based on localrandom time-varying symmetry breaking.”


**Q.1.** Working with one partner, on a separate sheet of paper, quickly sketch a black box“device-level” systems diagram that would implement what is shown and described above.  Yourboxes should have very simple names, such as “change color,” “swim,” “secrete attractor,” “AND,” or whatever human-defined functions are needed and appropriate.  I.e., recall thatDEVICES are human-defined functions.  What human-defined functions do you need toimplement a bacterial flash mob?  Make sure to also connect each black box device to theothers as needed. **(up to 10 minutes)**


**Q.2.** Find another pair and talk thru how each other’s systems are expected to work.  Did youfind any problems with your device-level implementations?  If so, revise your design as needed.This is a type of “debugging” to quickly identify problems at a high-level of abstraction, beforeworrying about how to actually implement the details of any device. **(up to 10 minutes)**


**Q.3.** Returning to work with your partner.  Label each of your boxes via the generic systemarchitecture we learned about in class this week.  That is, for each of your black boxes, labeleach with the letter “S,” “C,” or “A” depending on if each box can best be thought of as a“Sensing,” “Computing,” or “Actuating” function, respectively.  **(up to 5 minutes)**


Take a break, look here: [iGEM-2006: Polkadorks](https://2006.igem.org/wiki/index.php/IAP2004:Polkadorks)


**Q.4.** Pick any “Computing” device that is used in your system.  Describe using simple words thebasic biological functions that could be used to implement such a device.  Note that this is hardwork if you don’t know anything about basic biological functions.  Ask for help as needed.  Thinkabout words like protein, DNA, gene expression, transcription, translation, ON, etc.  **(up to 7.5’)**

**Q.5.** Next, going down the abstraction hierarchy, you need parts.  Where to get parts?  Howabout a student-produced collection of thousands of DNA parts.  Sure! Go to the iGEM PartsRegistry (http://parts.igem.org/Catalog).  Find parts that could be used to implement yourdevice. If you can’t find what you want make a note and move on. **(up to 10 minutes)**


**Q.6.** Finally, sketch how your parts should be organized as DNA elements in relation to oneanother so that they would actually implement the Computing function as you desire.  Draw ablack box around your parts.  Add inputs and output arrows to the box as appropriate.  Sketch asimple transfer function (i.e., the expected relationship between the inputs and outputs).  Areyour input and output signals generic or specific to your device?  **(up to 7.5 minutes)**
