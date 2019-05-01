---
title: "Week 5 Problem sets"
permalink: /docs/w5ps/
---
**DUE:** Next Friday(), beginning of class via **Gradescope**.

**NOTES:**
  - All BIOE.80 problem sets must be completed individually unless plainly noted opetherwise.
  - Please turn in your completed problem sets as an electronic copy via **Gradescope**.
  - Please make sure to not go over the word limits and when appropriate show your work (e.g., calculations, units, and figure captions).

**GOALS:** Reflect on the utility of evolution both as an algorithm and as a service.

## (Q1) Microbial Resistance (5 points)

According to recent news reports, a patient with a multi-drug resistant bacterial infection was cured by injecting
phage (i.e., bacterial viruses [The Bacteriophage Video](https://www.youtube.com/watch?v=YI3tsmFsrOg)) directly into the bacterial cyst inside thepatient’s abdomen. The patient was ultimately cured. The treatment, however, was not easy...

“The learning curve was steep and unmarked. There were bouts of sepsis — a life-threatening omplication caused by massive infection. Despite improvement, (the) patient’s conditionremained precarious. Doctors discovered that the bacterium eventually developed resistance to the phage, what Schooley would characterize as “the recurring Darwinian dance,” but the team compensated by continually tweaking treatment with new phage strains — some that had derived from sewage — and antibiotics.” [source](https://health.ucsd.edu/news/releases/Pages/2017-04-25-novel-phage-therapy-saves-patient-with-multidrug-resistant-bacterial-infection.aspx)

**Q.1.a.** From the above text and thinking back to what you learned about evolution, what are the challenges associated with implementing Phage therapy?

## (Q2) Understanding the "Search Space" of Evolution (X points)
In class, we talked about thinking of evolution as an algorithm. In this problem, we will try and make some elements of this metaphor more concrete. We can think of evolution as a type of [optimization algorithm](https://en.wikipedia.org/wiki/Mathematical_optimization#Optimization_algorithms). In lecture we talked about so called "evolutionary algorithms," which are a type of optimization algorithm in the field of computer science which borrows heavily from biological evolution.

These optimization algorithms seek to find the best solution, or at least a really good one, from a set of possible choices. What is defined as "really good" depends on the particular problem being optimized, but generally engineers deal with systems where an input choice maps to an output number. The goal then becomes to maximize or minimize the output number over all possible choices. This output number could be something like a "cost of production," or an "energy consumption," or the "mass of product". We call the set of possible input choices the "search space" of an algorithm. In biological evolution, the search space is the space of all possible genomes (the **"genotype space"**) and the output is biological fitness.

**Q.2.a.** Recall that there are 4 nucleotides / letters in the DNA alphabet (A, C, T, G). If asked to make a genome that is one base long, how many possible genomes could you make? As in, how many unique genomes of length 1 could exist? How many unique genomes of length 2 could exist? Of length 3?

Note: it may be very helpful to write out all the possible genomes by hand.

**Q.2.b.** How does the number of unique genomes grow as you increased the length of the genome? Given a genome length of _n_, how many unique genome of length _n_ could exist?

**Q.2.c.** _E. coli_ has a genome of length _n<sub>E. coli</sub>_ = 4.3 Mb, We will approximate this length as _n<sub>E. coli</sub>_ ~ 10<sup>7</sup>. How many unique genome could be made of this length?

Physicists estimate that there are 10<sup>80</sup> atoms in the known Universe [link to popular science article describing how this number was estimated](https://www.universetoday.com/36302/atoms-in-the-universe/). How does the number of atoms in the known Universe compare to the number of unique genomes of the same length as the _E. coli._ genome?

## (Q3) How much of the Evolutionary "Search Space" have we Searched? (X points)
In the previous problem, we estimated how big is the space of all genomes as long as the _E. coli_ genome (spoiler: very big). In this problem, we will estimate how much of this space has been searched.

Thanks to a long-term evolution [experiment](http://myxo.css.msu.edu/) it is possible to estimate that *E. coli* has a mutation rate on the order of 10<sup>-10</sup> (mutations)/(base x generation) [bionumber-source](https://bionumbers.hms.harvard.edu/bionumber.aspx?&id=105813). Assume that *E. coli* has a genome size of 10^7 bases per genome.

**Q.3.a.**  What is the rate of mutations/genome x generation for *E. coli*? That is to say, how many mutations should we expect per individual bacterial genome replication event?

**Q.3.b.** Assume there are 10<sup>30</sup> _E. coli_ cells on Earth ([estimate from a 1998 study out of University of Georgia](https://www.pnas.org/content/95/12/6578)). If every one of these cells replicates all at once, how many mutations should we expect to occur in this replication cycle?

**Q.3.c.** Life on Earth is approximately 10<sup>9.5</sup> years old. _E. coli_ replicates at a rate of one generation per 20 minutes, or 3 replications per hour. If we assume that _E. coli_ has been around since the beginning of life on Earth, how many _E. coli_ generations have passed since life began?

**Q.3.d.** Let's assume that the global population size of _E. coli_ remains constant over time. Given your answers for 2.b. (the total number of mutations that arise every time all the _E. coli_ in the world replicate) and 2.c. (the number of times _E. coli_ could have replicated since life began), how many total mutation events would you expect have happened in Earth's history? Is this number bigger or smaller than the number of possible _E. coli_ genotypes?

Note: Question-3 is based on an entry from [*Cell Biology by the Numbers*](http://book.bionumbers.org/what-is-the-mutation-rate-during-genome-replication/), and from material from Dan Fisher's course Evolution by the Numbers [APPPHYS237/BIO251](https://explorecourses.stanford.edu/search?view=catalog&filter-coursestatus-Active=on&q=APPPHYS%20237:%20Evolution%20by%20the%20numbers&academicYear=20182019).

## (Q3) Brainstorming Report  (20 pts)

This part must be completed individually

**Q.3.a.**  Did you show up on Friday? (Yes / No)

**Q.3.b.**  Were you able to connect with everyone in your group? (Yes / No) Please share their names.

Drawing from your experiences in class Friday using [I like, I wish, What if](https://dschool-old.stanford.edu/wp-content/themes/dschool/method-cards/i-like-i-wish-what-if.pdf)

**Q.3.c.**  What audience, method and topic combinations did your group identify using the tool. (name top 3 here)

**Q.3.d.** Select one audience group from your top brainstorm list and further explore them individually. In a paragraph Describe wny the audience you have chosen would find that topic relevant. Identify additional stakeholders associated with your topic.

**Your questions**
Do you have any unanswered questions (from this week, past weeks, or general BIOE) that you would like to share with us?

## Extra learning (100% optional):

### (Q4) Evolution as a Service (0 points)

**Q.4.a.** Describe two challenges associated with using Directed Evolution as an engineering approach? (bullet points)

Imagine that you want to engineer the rate of evolution (increase or decrease) in an engineered living matter.

**Q.4.b.** Briefly describe a utility for engineering the rate of evolution itself.
Stated differently, Where and how you would use such an organism if you wanted to use evolution as a service?
(2-3 sentences)


### (Q5) Cystic Fibrosis (0 points)

Cystic fibrosis (CF) is an inherited disorder that causes severe damage to the lungs, digestive system, and other organs in the body.

“Cystic fibrosis affects the cells that produce mucus, sweat, and digestive juices. These secreted fluids are normally thin and slippery. But in people with cystic fibrosis, a defective gene causes the secretions to become sticky and thick. Instead of acting as a lubricant, the secretions plug up tubes, ducts, and passageways, especially in the lungs and pancreas.” [source-1](https://www.mayoclinic.org/diseases-conditions/cystic-fibrosis/symptoms-causes/syc-20353700). This thick mucus in the lungs and sinuses provides an ideal environment for chronic bacterial and fungal infections. As a result CF patients mayoften have sinus infections, bronchitis, or pneumonia [source-1](https://www.mayoclinic.org/diseases-conditions/cystic-fibrosis/symptoms-causes/syc-20353700). CF itself is caused by a mutation in the gene cystic fibrosis transmembrane conductance regulator (CFTR). The most common mutation is a deletion of three nucleotides that results in a loss of the amino acid phenylalanine (F) at the 508th position in the protein. This mutation accounts for two-thirds (66–70) of CF cases worldwide and 90% of cases in the United States; however, over 1500 other mutations can produce CF [source-2](https://en.wikipedia.org/wiki/Cystic_fibrosis)

**Q.5.a.** Phage therapy has been proposed and tested as a  potential solution for managing infections in cystic fibrosis. Thinking back to what you learned about evolution, what are the challenges associated with implementing this solution? (bullet points)

Imagine that we could forever remove the gene that causes *90% of cases* of CF by engineering the human genome.

**Q.5.b.** Who should get to decide if we would permanently delete the gene from the gene pool? If you could permanently remove the gene what would you choose? (2-3 sentences)  (In this open-ended question we are looking for your reasoning)

#### (Q6) Mutation Rate and Genome Replication (0 points)
**Q.6.b.** Assume there are 10^10  cells in a 5 mL overnight culture of *E. coli* (i.e., 10^10 genomes are replicating during the final doubling). Given the rate of mutation / genome x generation (from 3.a), how many novel mutations do you expect inside the overnight culture?

**Q.6.c.** Given your answer from 6.b and the size of *E.coli*'s genome, is 5mL of the overnight culture sufficent to ensure that you have every single nonlethal base pair substitution in culture? (Yes  / No, Explain your answer in 2-3 sentences)
