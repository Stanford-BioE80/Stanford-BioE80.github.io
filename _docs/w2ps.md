---
title: "Week 2 Problem Set"
permalink: /docs/w2ps/
last_modified_at: 2018-11-25T22:21:33-05:00
toc: true
---

**DUE:** Next Friday(April.19), beginning of class.

**NOTES:** 
  - All BIOE.80 problem sets must be completed individually unless plainly noted otherwise.
  - Please turn in your completed problem sets as an electronic copy via Canvas. 
  - Please make sure to not go over the word limits and when appropriate show your work (e.g., calculations) 

**GOALS:** Reflect on the engineering design cycle: Design, Build, and Test (DBT) and its role in Bioengineering. 

## (Q1) MOSIS (20 pts)

[MOSIS](https://www.mosis.com/) (Metal Oxide Semiconductor Implementation Service) is a product of the VLSI revolution that changed the way we make the chips that power all of our electronics today. Before the advent of this shared implementation service, researchers and others looking to prototype and/or fabricate a chip had to be much more personally involved in the process of fabrication. The best results came when you knew someone in the fab facility, and could tailor your design to their skills. Recognizing a need, the clever minds behind MOSIS sought to help lower these barriers to entry (cost, specialized knowledge, and access to a foundry). 

In doing so, they created the "fabless foundry" industry that has helped shape our society today. Watch this [video](https://www.youtube.com/watch?v=d5SEFE_49Ug) made by MOSIS explaining the workflow for using their service. As you do, pay special attention to each step of the workflow, who is involved, and which part of the DBT cycle is shown.

**Q.1.a.** How does the MOSIS cycle compare (similarities and differences) to the DBT cycle you saw with KumaMax? Fill in the following table to compare and contrast the DBT workflow in each case, highlighting who is responsible for each step, and what tools they use in the completion of this task.

<table>
  <tr>
    <td></td>
    <td>KumaMax</td>
    <td>Mosis</td>
  </tr>
  <tr>
    <td>Design (Who, How)</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Build (Who, How)</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Test (Who, How)</td>
    <td></td>
    <td></td>
  </tr>
</table>


(Additional Resources: Reminiscences of the VLSI Revolution - Lynn Conway's memoir, see [here](http://ai.eecs.umich.edu/people/conway/Memoirs/VLSI/Lynn_Conway_VLSI_Reminiscences.pdf)) 

Engineering living matter has not yet undergone the same type of decoupling and standardization of different aspects of the DBT cycle that ushered in massive change in other fields (standardization of screws, outsourcing chip fabrication with MOSIS). People who want to make customized DNA often have to do so own their own, spending months to construct and validate a single piece of a DNA sequence. Recently, with the commercialization of DNA synthesis technologies, it has become possible to order customized genes, but this process is expensive. 

[Free Genes Project](https://biobricks.org/freegenes/) wants to bring ideas of decoupling and the "fabless foundry" to the engineering of DNA.

**Q.1.b.** Visit the Free Genes Project website. Briefly describe how it works. (bullet points)

## (Q2) Playing with the Amino Acid Alphabet (10 pts)

Proteins are composed of long chains of amino acids. As building blocks, amino acids contain the same backbone and connect in a particular direction: from the N-terminus (amino group) to the C-terminus (carboxyl group). See Figure 1 in this short [post](https://www.nature.com/scitable/topicpage/protein-structure-14122136).  Because of this, we can number each amino acid in a protein starting with the amino acid at the N-terminus as position 1. When we engineer proteins, it is useful to identify the changes that we made in the amino acid sequence, ie: V298T. This means that at position 298 (ie: the 298th amino acid in the chain), we originally had a Valine (V). We have mutated it so that instead of a Valine, we have swapped in a Threonine (T). These changes do not change the backbone of the amino acid chain. Instead, they change the "R" group, which often has structural and functional consequences.

Let's say we had a 3 amino acid protein with the sequence `CAT`. If we made a C1R mutation, we would now have the sequence `RAT`.

```
123
CAT
RAT
```
**Q.2.a.** Using the 20 natural amino acid alphabet, make 5 other English words from our original protein `CAT`. Write out the shorthand changes for each, starting from the original protein. (Hint: get creative. Make as many changes as you'd like. You can even insert amino acids. To add an extra amino acid at the end, designate this as `+4X`, where `+` indicates an addition to the original sequence, `4` indicates the new position, and `X` is your amino acid.) 

**Q.2.b.** Let's go back to our original protein. Write out the full amino acid names for `CAT`.

**Q.2.c.** Now let's take a look at the first mutation we made: C1R. Below, you can see the chemical structures for each of these amino acids. List 2 differences and give a brief explanation of why those differences might be biologically meaningful. ***INSERT FIGURES FOR CYSTEINE AND ARGININE***
![C Structure](https://commons.wikimedia.org/wiki/File:Cysteine.png "C")
![R Structure](https://commons.wikimedia.org/wiki/File:L-arginine.png "R")

<figure>
<a href="https://commons.wikimedia.org/wiki/File:L-arginine.png"><img width="512" alt="L-arginine" src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4b/L-arginine.png/512px-L-arginine.png"></a>
<figcaption><b>Amino Acid Structures</b>. 
<b>Left</b>. C. 
<b>Right</b>. R
</figcaption>
</figure>

<a title="C" href="https://commons.wikimedia.org/wiki/File:Cysteine.png"><img width="512" alt="L-cysteine" src="https://upload.wikimedia.org/wikipedia/commons/2/2f/Cysteine.png"></a> <a title="R" href="https://commons.wikimedia.org/wiki/File:L-arginine.png"><img width="512" alt="L-arginine" src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4b/L-arginine.png/512px-L-arginine.png"></a>



## (Q3) Revisiting Design Tools (PyMol) (15 pts)

In this problem, you will use PyMol to visualize green fluorescent protein (GFP). Unlike our 3 amino acid protein in Question 2, GFP is a 238 amino acid protein. For more information about GFP, check out the [Wikipedia page](https://en.wikipedia.org/wiki/Green_fluorescent_protein), or see the resources below.

Check out the website where the GFP structure is housed: [https://www.rcsb.org/structure/1gfl](https://www.rcsb.org/structure/1gfl). Notice that we are looking at a homo-dimer, meaning that 2 identical 238 amino acid chains are in the structure. 

**Q.3.a.** What is the experimental method used to get the structure of the protein? What is the listed resolution of the structure? (bullet points)

**Q.3.b.** Add a screenshot of your GFP structure in PyMol showing the "beta barrel" structure of fluorescent proteins. 

To do so:

1. Download PyMol from this [Pymol Link]( https://pymol.org/2/) and Open PyMol on your laptop or computer. 

2. Type in the command “fetch 1gfl” in PyMol. This command downloads the structure ofGreen Fluorescent Protein (GFP) from the Protein Data Bank (PDB)

3. In PyMol and take a look at the GFP structure.  Under the menus “H” and “S”  listed near the structure name on the toolbar on the right, click `Hide everything` and `Show cartoon`. 

4. Take a screenshot of the protein structure to share as part of the problem set.

**Q.3.c.**  Go back to the Protein Data Bank website and find a `.pdb` file for another fluorescent protein. Use PyMol to visualize this second protein. Provide a screenshot and tell us what color the protein fluoresces.

## (Q4) Making with Mushrooms(35 Points)

**Q.4.a.** Did you show up on Friday, make your mycelium material object? (Yes / No)

**Q.4.b.** Describe in broad terms what processes unique to living matter are enabling building with mushrooms possible. 
What are the potential and limitations of making with mushrooms? (bullet points)

**Q.4.c.**  How is making with mushrooms similar to or different from other manufacturing processes such as 3D printing? (bullet points)

**Q.4.d.**  Looking forward, how do we go from creating matter with an inert function (e.g., a chair) to create matter with biological function (i.e., growing a finger or a heart)? What new considerations need to be made? (3-4 sentences, provide drawings or diagrams if helpful)

## (Q5) Prepare for the Group Project (20 pts)

This question seeks to enable you to prepare for the group formation for the final project.  Specifically, you will prepare an introduction card that you will exchange with your classmates during the group formations to self organize into your group.

First, revisit [Kiva](https://www.kiva.org/about) from the pre-class reading. Note that you can select various sectors (health, food, agriculture, arts, education,  ... ) or locations across the world. [Kiva link-2]( https://www.kiva.org/lend)

**Q.5.a.** Name 3 sectors that are of interest to you?

**Q.5.b.**  What role, imagined or as yet unimagined, can bioengineering play in addressing the needs in these sectors? (2 to 3 sentences)

**Q.5.c.**   Pick a location (ideally a region that you are not familiar with).  What are 3 to 4 specific requests that people from this location have? 

**Q.5.d.**  What role, imagined or as yet unimagined, can bioengineering play in addressing these requests? (2 to 3 sentences).

Provide the answers as part of problem set-2.  
Additionally, we will have an online Google Spreadsheet for you to add in your ideas and share them with your classmates. This can help you find teams for your final project in preparation for Week 4 (Fri 26 April).  

**Extra Credit (5 points)**

There are several great spots on campus to explore and bioprospect in search of new mushrooms. For this activity you can explore the variety of fungal diversity outside (even the engineering quad has fungi to discover!).

**Please don’t disturb or eat any mushrooms you find for this extra credit.**

Find a mushroom on campus, take a photo of it, and note your location and other characteristics such as the surrounding ecology.  Document your finding by including a paragraph description, your photo, and the location of your find in your PSET submission. 

For more info/inspiration you might check out:

- http://www.namyco.org/photography.php

- https://www.mssf.org/

**Final Note:** This week you explored the concepts behind Design-Build-Test. You also practiced DBT in the context of *Making with Mushrooms* and the decoupled build from design: *The Free Genes Project*. You will explore and practice DBT in many BIOE classes: BIOE 44 (Fundamentals for Engineering Biology Lab), BIOE 123 (Biomedical System Prototyping Lab), and BIOE 141 A and B (Senior Capstone Design).

**Your questions**
Do you have any unanswered questions (from this week, past weeks, or general BIOE) that you would like to share with us?

### Additional Resources (Fluorescent Proteins):

1. Fluorescent Proteins and the Story Behind GFP (by Roger Tsien ibiology) [link](https://www.ibiology.org/talks/fluorescent-proteins/)

2. Introduction to Fluorescent Proteins [link](https://www.microscopyu.com/techniques/fluorescence/introduction-to-fluorescent-proteins)

3. Interactive graph describing Fluorescent protein properties [link](http://www.fpvis.org/FP.html)

## Extra learning (100% optional):

### (Q.6) When are we 'done'? (0 pts)

A crucial skill is determining when we are ready to exit the DBT cycle (if ever). This can be determined by a number of things, such as access to resources, allotted time, and meeting certain metrics of success. It can be challenging to know when you have found the proper balance of all of these. Luckily, our old friend DBT provides a guide to help with these considerations. That is what the Test part is all about: helping you determine when you have succeeded. 

Let's look at a real example of Test in action. Watch this [video](https://www.youtube.com/watch?v=bvim4rsNHkQ&feature=youtu.be), and answer the following questions.

**Q.6.a.** Are you surprised by the video? Why do you think the company behind this video wanted to share their testing process with the world? (<150 words)

**Q.6.b.** Can you guess what some of the design specifications and testing benchmarks were from the video? (<150 words)

Working from our design specifications and field standards, we can outline an acceptable margin of error. Once we get to a product that is within this range, we can say that we have succeeded and exit the cycle. But this is context, specific.

**Q.6.c.** How would you determine acceptable margins of error in the cases we have seen. Think about the stakeholders (who would be affected by a failure of the product), and how they would be impacted. Which do you think would have a larger margin of error? Why? (<150 words)

1. KumaMax: Creating an oral enzyme therapeutic to treat Celiac Disease

2. MOSIS: Building integrated circuits that are faithful to user-specified design

3. The Free Genes Project: DNA Synthesis

4. Falcon Heavy: Building a privately-funded rocket

By releasing videos of their failed launches, which include detailed annotations of which system failed the SpaceX team is reminding us that success can only be achieved after repeated failures. It is part of the process. They show us how to fail properly. 

### (Q7) Which Sector? (0 pts)

**Q.7.** Go to company websites (3 for the problem set) and determine in which "sector" they are situated (D, B, or T) and what do they do:

**[Twist Biosciences](https://twistbioscience.com/company/about)**

**[Ginkgo Bioworks](https://www.ginkgobioworks.com/)**

**[Amyris](https://amyris.com/)**

**[EnEvolv](http://enevolv.com/platform/)**

**[Bolt Threads](https://boltthreads.com/)**

**[Nektar](http://www.nektar.com/)**

**[MycoWorks](http://www.mycoworks.com/)**
