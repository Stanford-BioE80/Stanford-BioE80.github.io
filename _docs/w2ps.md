---
title: "Week 2 Problem Set"
permalink: /docs/w2ps/
last_modified_at: 2018-11-25T22:21:33-05:00
toc: true
---

**DUE:** Next Friday, beginning of class.

**NOTES:** 
  - All BIOE.80 problem sets must be completed individually unless plainly noted otherwise.
  - Please turn in your completed problem sets as an electronic copy via Canvas. 
  - Please make sure to not go over the word limits and when appropriate show your work (e.g., calculations) 

**GOALS:** Reflect on the engineering design cycle: Design, Build, and Test (DBT) and its role in Bioengineering. Prepare for quantitative estimations in living matter (both related to what makes living matter unique and DBT cycles).

## (Q1) MOSIS (20 pts)

While many of you may not have heard of Mosis prior to this course, you have probably - in one way or another - benefited from its existence. How, you ask? As you recall, [Mosis](https://www.mosis.com/) (Metal Oxide Semiconductor Implementation Service) is a product of the VLSI revolution that changed the way we make the chips that power all of our electronics today. 

Before the advent of this shared implementation service, researchers and others looking to prototype and/or fabricate a chip had to be much more personally involved in the process of fabrication. Making masks was unreliable, which produced poor wafers. The best results came when you knew someone in the fab facility, and could tailor your design to their skills. In other words, there was a lack of standardization and a centralization of designing and building that increased latency and cost. Recognizing a need, the clever minds behind Mosis sought to help lower these barriers to entry (cost, specialized knowledge, access to a foundry, etc). 

In doing so, they created the "fabless foundry" industry that has helped shape our society today. Watch this [video](https://www.youtube.com/watch?v=d5SEFE_49Ug) made by Mosis explaining the workflow for using their service. As you do, pay special attention to each step of the workflow, who is involved, and which part of the DBT cycle is shown.

**Q.1.a.** How does Mosis work? What feature(s) makes this service better than others that had previously been used? (bullet points)

**Q.1.b.** How does the Mosis cycle compare (similarities and differences) to the DBT cycle you saw with KumaMax? Fill in the following table to compare and contrast the DBT workflow in each case, highlighting who is responsible for each step, and what tools they use in the completion of this task.

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

Engineering living matter has not yet undergone the same type of decoupling and standardization of different aspects of the DBT cycle that ushered in massive change in other fields (standardization of screws, outsourcing chip fabrication with Mosis). People who want to make customized DNA often have to do so own their own, spending months to construct and validate a single piece of a DNA sequence. Recently, with the commercialization of DNA synthesis technologies, it has become possible to order customized genes, but this process is expensive. 

**Q.1.c.** Thinking to the future, if more and more Design, Build, and Test companies blossom in industry, what would be the role of the researcher? Could you outsource a research project and would it be cheaper / faster? Is that good? (bullet points)

[Free Genes Project](https://biobricks.org/freegenes/) wants to bring ideas of decoupling and the "fabless foundry" to the engineering of DNA.

**Q.1.d.** Visit the Free Genes Project website. Briefly describe how it works. Who is responsible for each aspect? (bullet points)

## (Q2) Approximate and rapid numerical estimates (40 pts)

Approximations based on simple physical principles are known as Fermi problems. These problems will help you build quantitative intuition. This quantitative intuition will help you during the DBT cycle (estimating feasibility). Most of these estimates are rough: they are designed to give you a broad, order of magnitude intuition for the biology, so keep in mind that that the exactly correct number could be different. Give your answers to two significant figures and provide units where appropriate. You should only need simple math and arithmetic; a couple of lines of work at most. 

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

**Q.2.a.** Based on a spherocylinder model, calculate the volume of an _E. coli_ cell. 

**Q.2.b.** If an _E. coli_ cell were the size of a building, how big would a water molecule be?

**Q.2.c.** The mean diameter of a protein is roughly 4 nm. What is the upper bound on how many proteins could fit inside an *E. coli* cell?

**Q.2.d.** How would you go about estimating the total number of carbon atoms in an *E.coli* cell? You don't have to calculate this just define variables and describe your approach step by step. 

## (Q3) Making with Mushrooms(40 Points)

3.a. Did you show up on Friday, make your mycelium material object? (Yes / No)

3.b. Describe in broad terms what processes unique to living matter are enabling building withmushrooms possible. 
What are the potential and limitations of making with mushrooms? (bullet points)

3.c. How is making with mushrooms similar to or different from other manufacturing processessuch as 3D printing? (bullet points)

3.d. Looking forward, how do we go from creating matter with an inert function (e.g., a chair) to creat matter with biological function (i.e., growing a finger or a heart)? What new considerations need to be made? 

**Extra Credit (5 points)**

There are several great spots on campus to explore and bioprospect in search of newmushrooms that could potentially be used for making materials. 

For this activity you can explore the variety of fungal diversity outside (even the engineering quad has fungi to discover!).

**Please don’t disturb or eat any mushrooms you find for this extra credit.**

Find a mushroom on campus, take a photo of it, and note your location (GPS coordinates via your phone) and other characteristics such as the surrounding ecology.  Document your finding by including a paragraph description, your photo, and the location of your find in your PSET submission. 

For more info/inspiration you might check out:

- http://www.namyco.org/photography.php

- https://www.mssf.org/

**Final Note:** This week you explored the concepts behind Design-Build-Test. You also practiced DBT in the context of design tools for living matter (pyMol), decoupled build from design (ordered a gene to be synthesized), and tested a DNA device (via GOOP). DBT is an essential framework that you will apply to many (bio)engineering challenges. You will explore and practice DBT in many BIOE classes: BIOE 44 (Fundamentals for Engineering Biology Lab), BIOE 123 (Biomedical System Prototyping Lab), and BIOE 141 A and B (Senior Capstone Design).

**Your questions**
Do you have any unanswered questions (from this week, past weeks, or general BIOE) that you would like to share with us?

**Extra learning** (100% optional):

## (Q5) When are we 'done'? (0 pts)

A crucial skill is determining when we are ready to exit the DBT cycle (if ever). This can be determined by a number of things, such as access to resources, allotted time, and meeting certain metrics of success. It can be challenging to know when you have found the proper balance of all of these. Luckily, our old friend DBT provides a guide to help with these considerations. That is what the Test part is all about: helping you determine when you have succeeded. 

Let's look at a real example of Test in action. Watch this [video](https://www.youtube.com/watch?v=bvim4rsNHkQ&feature=youtu.be), and answer the following questions.

**Q.5.a.** Are you surprised by the video? Why do you think the company behind this video wanted to share their testing process with the world? (<150 words)

**Q.5.b.** Can you guess what some of the design specifications and testing benchmarks were from the video? (<150 words)

Working from our design specifications and field standards, we can outline an acceptable margin of error. Once we get to a product that is within this range, we can say that we have succeeded and exit the cycle. But this is context, specific.

**Q.5.c.** How would you determine acceptable margins of error in the cases we have seen. Think about the stakeholders (who would be affected by a failure of the product), and how they would be impacted. Which do you think would have a larger margin of error? Why? (<150 words)

1. KumaMax: Creating an oral enzyme therapeutic to treat Celiac Disease

2. Mosis: Building integrated circuits that are faithful to user-specified design

3. The Free Genes Project: DNA Synthesis

4. Falcon Heavy: Building a privately-funded rocket

By releasing videos of their failed launches, which include detailed annotations of which system failed the SpaceX team is reminding us that success can only be achieved after repeated failures. It is part of the process. They show us how to fail properly. 

**Q.5.d.** Give an example of a biological experiment you might conduct where using _both_ GFP and your selected fluorescent protein could be useful. Describe the experiment in no more than a few sentences. Draw upon what you've learned about how fluorescent proteins are expressed using DNA constructs (genes).

**Q.6.** Go to company websites (3 for the problem set) and determine in which "sector" they are situated (D, B, or T) and what do they do:

**[Twist Biosciences](https://twistbioscience.com/company/about)**

**[Ginkgo Bioworks](https://www.ginkgobioworks.com/)**

**[Amyris](https://amyris.com/)**

**[EnEvolv](http://enevolv.com/platform/)**

**[Bolt Threads](https://boltthreads.com/)**

**[Nektar](http://www.nektar.com/)**

**[MycoWorks](http://www.mycoworks.com/)**
