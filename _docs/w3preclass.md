---
title: "Week 3 Preclass- Abstraction"
permalink: /docs/w3preclass/
last_modified_at: Feb.20.2019
2018: "Week 6"
---


## Abstraction as a tool for managing complexity in bioengineering

Please read and consider the below before start of each class.
The questions given are only study questions not homework to be graded.
Talk about it all with your classmates, friends, or TAs, as you like.

## Preclass for Monday

## Introduction: Abstraction as a tool for managing complexity in bioengineering.

Welcome to the pre-class material for Abstraction as a tool for managing complexity in bioengineering. 

**Goal-1:** After Week-3 you will able to describe the role of abstraction as a tool for helping 
to managecomplexity in biological systems - with an emphasis on the design step of the engineering cycle.

**Goal-2:** You will also be able to apply abstraction (in the form of black box diagrams) to decompose 
or synthesize the designs systems that could then be implemented in living matter for example viaengineered 
(i.e., designer) DNA.

## Example-1:  Bacterial Flash Mob

**Write down the DNA sequence** encoding a dynamic bacterial flash mob (see animation below in Figure.1 )

<figure>
<a href="/assets/images/w3_IEcolibratorMovie.gif"><img src="/assets/images/w3_IEcolibratorMovie.gif"></a>
</figure> 

**Figure-1** Bacterial flash mob. [Source](https://2006.igem.org/wiki/index.php/IAP2004:Polkadorks)

**Q.1. What is the first base of your DNA program?  A, T, C, or G?  
(Note: Do not spend more than 100 seconds pondering and answering this question.  Time’s up!).**  

*Figure 1.  Dynamic bacterial flash mob.* 
A collection of engineered bacteria (black dots)move randomly in two dimensions.One cell activates randomly, turns red, and secretes a diffusing attractant molecule (green circle).All other cells sense and move towards the source of the attractant.After a period of time all cells return to their original stateuntil the process repeats over and again.

**Q.2. Why is Q1 a difficult question to answer?**   
(Hint: Consider the difference between what you do and what must physically occur to use a smartphone to take a photograph and send an image to your best friend via text message.  Are you ever typing 0s and 1s into your phone?  What’s happening instead?)


One simple-but-powerful and general-purpose approach for organizing engineered systems is shown on the next slide.  Forexample, a computer has a keyboard that receives input via keys (sensors), performs logical operations (computation), andcan output via a display, printer or other device (actuation).  As a second example, a pilot can control a Boeing 787 airplaneby moving the yoke, whose inputs are combined with other inputs collected by additional sensors (e.g., air pressure), andthen a flight computer determines what the actuated flight surfaces on the wings and tail physically do, as controlled by a“fly-by-wire” system.


Note that our thinking about such systems can quickly become complicated by the details of any one example, but thateach example follows a similar pattern; inputs are received by one or more sensors; so-received information is computedupon as needed via an intermediate process; and finally some action is taken.  Please also note that in more complicatedsystems the output of a system can itself be an input, creating a “loop” or feedback to realize more sophisticated dynamics(e.g., repeating or other dynamically controlled behaviors, such as in the case of the looping bacterial flash mob).


<figure>
<a href="/assets/images/generic system arch.png"><img src="/assets/images/generic system arch.png"></a>
<figcaption><b>Figure 2</b>. Generic system architecture.</figcaption>
</figure>

A sensor measures environmentalproperties or inputs  (for example: a keyboard) and transfers this information to a computer (logic unit) to be processed. The results are then transferred to an actuator (e.g., a printer or a display) that can output these results.


This same framework can be applied to help manage the engineering of biological systems.Stated differently, the desired behavior of a complicated biological process can be represented at an intermediate level ofabstraction via a simpler-to-understand  “black box” diagram.


**Q.3. Revisit to the bacterial flash mob and develop a device-level block diagram that would result in the so-shownbehavior.  Label simple sensors, logic blocks, and actuators, as needed.  Connect outputs to inputs (i.e., connectboxes together via ines) where and as required.**  
(Hint: Only give simple device names (e.g., “coin flip,” “turn red,” etc.);do not describe any biology in any molecular detail).


**Key Concept:** What we are practicing via this generic system architecture is called **abstraction**. 
Abstraction is a tool that allows engineers (and others) to modularize and manage the complexity of a system. Abstraction establishes a level of simplicity at which a person interacts with the system, temporarily hiding more complex details for later consideration, only if and as such details must be considered.  

<figure>
<a href="/assets/images/w6pc_the laws of thought.png"><img src="/assets/images/w6pc_the laws of thought.png"></a>
</figure>

From a different perspective, note how George Boole observed ways in which human language results in a type of abstraction that can be used to organize and link our experiences to actions.  For example: if it is raining AND snowing then bundle up OR if it is warm AND sunny then go the beach.

But, returning to the Bacterial Flash Mob example.

**Q.4. When we go to actually implement any sensor, computer, or actuator, what exactly is inside the boxes?  Are there actually black boxes inside a cell?  What “wires” connect one box to another?**

These are challenging questions that we will resolve starting Monday!

*Useful Additional Resource:* 
Check out this free comic bolok that starts out simple but quickly begins to develop answers to **Question-4**: 
[Adventures in Synthetic Biology](https://openwetware.org/wiki/Adventures)

_______________________________________________________________________

## Preclass for Wednesday

There is no preclass for Wednesday Week-3. 

______________________________________________________

##  Preclass for Friday
### What is GOOP? (or an introduction to prototyping living matter)

The teaching team is excited to share with you a unique prototyping platform for engineering living matter:

After this introduction you should be able to: 
Describe what is GOOP and how it works
Describe the role of prototyping in the engineering cycle 
Get ready to to apply and use GOOP (apply and build with the central dogma of biology)  
Be ready to use PyMol to visualize protein structures
 
Let’s begin:

**Q.0.** In preparation for class on Friday, please download PyMol using the following [link](https://pymol.org/2/). PyMol is a molecule visualization toolkit that is heavily used by protein engineers and designers. 

You are now familiar with the engineering cycle of design, build, and test. 
Until recently our ability to rapidly and robustly build prototypes for the engineering of living matter was somewhat limited. This is in contrast with other fields, where prototyping is a major component. For example, in electrical engineering circuits and systems are either prototyped (with physical components) or simulated. 3D printing is another example of prototyping that you may be familiar with. 

**Q.1** What are the consequences of limited prototyping? Think about an example in engineering living matter and in another engineering field. 

Thanks to recent developments in bioengineering, for the first time we have the ability to prototype engineering living matter as part of the class. (We have to emphasize that developing with and creating these prototyping platforms themselves is still an active and exciting area of research in bioengineering.)

### What is GOOP? 

On friday you will receive the tubes that contain GOOP: Genetic Objects Operations and Programming mixture. With GOOP you can test your genetic program (similar to genes you ordered during the build class) on a timescale of hours instead of days (to be explained shortly). Your programs or input instructions (designs) are small pieces of (circular) DNA called plasmids. Each plasmid contains the instructions to encode a protein: a type of complex macromolecule that can perform an incredible diversity of tasks. The GOOP in the tube runs your DNA instructions. GOOP is extracted cellular machinery, in this case from E. coli cells, that makes proteins from the DNA inputs needing living cells. The name of the specific material that you have is 
TX-TL, for transcription-translation. What are transcription and translation? Read on.


### The Central Dogma of Biology

At the core of biology is a simple idea, known as the central dogma. For our purpose, we can think of central dogma as a process that transcribes the information encoded in DNA to RNA (transcription), and then translates the information encoded in RNA to form a protein (translation). If you aren’t familiar with the central dogma, check out this video explain how it happens inside a cell (in vivo): Central Dogma. We’ve also listed some additional resources at the end of this document. Figure. 1 describes the overall flows of this process, which is typically from DNA to RNA to protein (with some special exceptions). 

<figure>
<a href="/assets/images/w2pc_centraldogma.png"><img src="/assets/images/w2pc_centraldogma.png"></a>
</figure>


**Figure-1** An overview of central dogma - update with better quality

How is this related to GOOP? GOOP lets you to operate this process outside of living cells in a tube (in vitro). In fact, you can think of GOOP as the vertical blue arrows in Figure 1. When you add your plasmid instructions to GOOP and let it sit at room temperature, the GOOP will transcribe your DNA into messenger RNA, and translate it into the encoded proteins. This process will take a number of hours (up to overnight), but you will be able to see the real-time production of your protein product. In comparison, running a plasmid in cells requires a multi-step process that takes multiple days, requires more complex plasmid design, and needs more sophisticated lab equipment (although it does have some advantages, can you think of any?). If you’re interested in the in vivo approach, make sure to check out BIOE 44

**Q.2** What designs (devices, circuits or systems) you would like to build and test with GOOP? 

**Q.3** What do you think are some of the advantages and some of the disadvantages of prototyping living matter in GOOP? 

**Q.4** Why might a certain design work in GOOP and not inside a cell?

**Q.5** Why might some designs work in a cell but not in GOOP?

**Q.6**  In class on Friday, you will be instructed on how to use GOOP to express a fluorescent protein. Please read this web page to get a primer on what Green Fluorescent Protein (GFP) is and how it can be used in bioengineering applications: http://pdb101.rcsb.org/motm/42


### General Kit Operation 


1. Select the DNA parts you would like to use for each reaction and lay them out. Each part has been pre-measured in its tube.

2. Take the number of reaction tubes you need for the experiment out of the fridge or your insulated envelope.

3. Using the transfer pipettes, suck up each DNA part and transfer it into the appropriate reaction tube.
- Use a fresh pipette for each part transfer: DNA is a powerful molecule, and cross-contamination of even a tiny amount of one part into the wrong tube could lead to an unexpected outcome.
- Avoid creating bubbles: don’t squeeze too hard and suck up lots of air, and squeeze air out of the tip of the pipette before you lower it into the reaction mix.
- It may help to gently stir the reaction with the tip of a pipette once the parts have all been added.

4. If you need to add an input to the reaction—for example, an sample or an inducer—use a transfer pipette to add it as above.

5. Make sure all parts and the reaction mix are together in the bottom of the tube by holding it in your hand, extending your arm up, and rapidly moving it down, kind of like you’re throwing a baseball.
  - Don’t actually throw the tube.
  
6. Let the reactions run at room temperature. Depending on the reaction, you will begin to see visible changes after 6 hours. 

### Safety

Whenever we practise the engineering of living matter, we always want to consider the safety of what we’re doing, how we are doing it, and how it might affect others and the environment. 

In general, GOOP itself is safe because it not living and so cannot replicate, and because it is derived from an organism (E. coli K-12) that is Biosafety Level 1 (BSL-1). BSL-1 organisms are those which are well-characterized and do not cause disease in healthy humans. 

Because GOOP operates genetic programs, some sets of instructions may have additional potential to cause harm: compare DNA encoding a colorful protein to DNA encoding a toxin. We will not supply genetic code that could hurt you, and our GOOP prototyping modules will each contain a section on any specific considerations for that module. There are some proteins that are illegal to make. Also note that there are industry standards for the synthesis of DNA programs: what do you think about this as a means of promoting safety?

Finally, there are several specific instructions for the safe operation of GOOP:
Don’t eat it!
Don’t get it in your eyes!
Dispose of GOOP by closing the tubes and throwing it in the trash.

Contact your TAs if you have any specific questions.

### Conclusion

Congratulations. In this module:
- You were introduced to the importance of prototyping in the context of engineering living matter.
- You began to consider how we can use GOOP to apply and build with central dogma without using living cells.
- You considered the advantages and current challenges associated with cell-free systems such as GOOP.
- You considered the safety of biological prototyping with regard to yourself and the environment.
- You downloaded molecular visualization toolkit PyMol

Now you are ready to proceed to the in class activity where you will use GOOP to express your first DNA code. 

### Glossary

**Base** a single unit of DNA or RNA. Also called a base-pair when in double stranded form.

**Cell free** reaction mix a mixture of the cellular machinery, capable of running the central dogma, but without the cells. Usually made by growing up cells and then breaking them open.

**DNA** deoxyribonucleic acid, a polymeric molecule that encodes information. Usually double-stranded, in a characteristic double-helix shape.

**RNA** ribonucleic acid, a polymeric molecule that encodes information and is usually transcribed from DNA.
Plasmid a small, circular piece of double-stranded DNA. The staple of molecular bioengineering, plasmids can be easily built and added in to cells.

**Protein** a polymer of amino acids, which fold into a complex three-dimensional structure based on the amino acid sequence. The structure of a protein determines its function.

**Enzyme** a protein which catalyzes a chemical reaction.

**Transcription** the process of reading DNA and producing RNA based on the DNA sequence. Transcription is performed by an enzyme complex known as RNA polymerase (RNAP).

**Translation** the process of reading RNA and producing a chain of amino acids, a protein, based on the RNA sequence. 

**TX-TL** (What is GOOP) transcription/translation mix. A special kind of cell free reaction mix that uses the standard E. coli transcription and translation system.

**Central Dogma**
Khan Academy: Central Dogma https://www.khanacademy.org/science/biology/gene-expression-central-dogma
Bruce Alberts Molecular Biology of the Cell (2015) Chapter 6
https://www.ncbi.nlm.nih.gov/books/NBK21054/ (older edition)
Science Library QH581.2 .M64
Green Library QH581.2 .M64 (fifth edition)


## Pre class & In class for Friday for 2018


**Part 1:** Reconsider the hypothetical bacterial *“flash mob”* that you encountered in the pre-classmaterial for Monday of this week.  See the animation or text below:

<figure>
<a href="/assets/images/w3_IEcolibratorMovie.gif"><img src="/assets/images/w3_IEcolibratorMovie.gif"></a>
</figure> 

**Figure-1** bacterial flash mob. [Source](https://2006.igem.org/wiki/index.php/IAP2004:Polkadorks)

Or, in natural language, “We start with a collection of engineered e-coli moving randomly inmedia. The bacteria are represented by black dots in the animation. Under control of astochastic element, a few bacteria begin excreting an attractant. These bacteria we will call thesender cells. In the animation we have one sender cell represented by the red dot; the greencircle represents the attractant diffusing away from the sender cell.  Through chemotaxis, aprocess by which a cell along a chemical gradient swims toward or away from the stimulus (anattractant in this case), nearby bacteria start swimming towards the sender cells. These bacteriawe will call the receiver cells. This way, groups begin forming around the original sender cells onthe plate.  Additionally, all bacteria have been engineered with a quorum sensing mechanismwhich effectively senses local cell density. In the groups that have formed, the local cell density eventually reaches a certain threshold. The quorum sensing mechanism of the cells then stopssecretion of any attractant. The existing attractant then diffuses away. Since there is no moreattractant being secreted, the cells will diffuse away and eventually be spread out across theplate once again. Then by the stochastic element a few cells will begin excreting the attractantand the whole process is repeated.  Basically polkadots will form, diffuse, and form again inrandom areas on the plate. Our system should thus form time-varying patterns based on localrandom time-varying symmetry breaking.”


**Q.1.** Working with one partner, on a separate sheet of paper, quickly sketch a black box“device-level” systems diagram that would implement what is shown and described above.  Yourboxes should have very simple names, such as “change color,” “swim,” “secrete attractor,” “AND,” or whatever human-defined functions are needed and appropriate.  I.e., recall thatDEVICES are human-defined functions.  What human-defined functions do you need toimplement a bacterial flash mob?  Make sure to also connect each black box device to theothers as needed. **(up to 10 minutes)**


**Q.2.** Find another pair and talk thru how each other’s systems are expected to work.  Did youfind any problems with your device-level implementations?  If so, revise your design as needed.This is a type of “debugging” to quickly identify problems at a high-level of abstraction, beforeworrying about how to actually implement the details of any device. **(up to 10 minutes)**


**Q.3.** Returning to work with your partner.  Label each of your boxes via the generic systemarchitecture we learned about in class this week.  That is, for each of your black boxes, labeleach with the letter “S,” “C,” or “A” depending on if each box can best be thought of as a“Sensing,” “Computing,” or “Actuating” function, respectively.  **(up to 5 minutes)**


Take a break, look here: [iGEM-2006: Polkadorks](https://2006.igem.org/wiki/index.php/IAP2004:Polkadorks)


**Q.4.** Pick any “Computing” device that is used in your system.  Describe using simple words thebasic biological functions that could be used to implement such a device.  Note that this is hardwork if you don’t know anything about basic biological functions.  Ask for help as needed.  Thinkabout words like protein, DNA, gene expression, transcription, translation, ON, etc.  **(up to 7.5’)**

**Q.5.** Next, going down the abstraction hierarchy, you need parts.  Where to get parts?  Howabout a student-produced collection of thousands of DNA parts.  Sure! Go to the iGEM PartsRegistry (http://parts.igem.org/Catalog).  Find parts that could be used to implement yourdevice. If you can’t find what you want make a note and move on. **(up to 10 minutes)**


**Q.6.** Finally, sketch how your parts should be organized as DNA elements in relation to oneanother so that they would actually implement the Computing function as you desire.  Draw ablack box around your parts.  Add inputs and output arrows to the box as appropriate.  Sketch asimple transfer function (i.e., the expected relationship between the inputs and outputs).  Areyour input and output signals generic or specific to your device?  **(up to 7.5 minutes)**
