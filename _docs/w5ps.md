---
title: "Week 5 Problem sets"
permalink: /docs/w5ps/
---
**DUE:** Next Friday (May 10th), beginning of class via **Gradescope**.

**NOTES:**
  - All BIOE.80 problem sets must be completed individually unless plainly noted otherwise.
  - Please turn in your completed problem sets as an electronic copy via **Gradescope**.
  - Please make sure to not go over the word limits and when appropriate show your work (e.g., calculations, units, and figure captions).

**GOALS:** Reflect on the utility of evolution both as an algorithm and as a service.


## (Q1) Evolution Fundamentals & Misconceptions (20 points)

True / False questions, please select the best answer.  If *False* please explain why (1-2 sentences). Please see preclass materials from Monday and Wednesday for background material.

**Q.1.a.** Individual mutations occur at random (True /  False)

**Q.1.b.** Evolution of living matter is independent of the environment (True /  False)

**Q.1.c.** Selection is random and unbiased (True /  False)

**Q.1.d.** Evolution works on the scale of individuals, not on populations (True /  False)

**Q.1.e.** Engineers, including bioengineers, can use evolution to optimize human-designed systems  (True /  False)

## (Q2) Understanding the "Search Space" of Evolution (30 points)

In class, we talked about thinking of evolution as an algorithm. In this problem we will try and make some elements of this metaphor more concrete. We can think of evolution as a type of [optimization algorithm](https://en.wikipedia.org/wiki/Mathematical_optimization#Optimization_algorithms). In lecture we talked about so called "evolutionary algorithms," which are a type of optimization algorithm in the field of computer science that borrows heavily from biological evolution.

These optimization algorithms seek to find the best solution, or at least a really good one, from a set of possible choices. What is defined as "really good" depends on the particular problem being optimized, but generally engineers deal with systems where an input choice maps to an output number. The goal then becomes to maximize or minimize the output number over all possible choices. This output number could be something like a "cost of production," or an "energy consumption," or the "mass of product". For example, a manufacturing engineer may wish to maximize the number of Foldscopes that can be made with $1M. The set of all possible input choices defines a "search space" over which the evolutionary algorithm seeks to find the best set of outputs.

In biological evolution, the search space is the space of all possible genomes (the **"genotype space"**) and the output is biological fitness.

**Q.2.a.** Recall that there are 4 nucleotides / letters in the DNA alphabet (A, C, T, G). If asked to make a genome that is one base long, how many possible genomes could you make? As in, how many unique genomes of length 1 could exist? How many unique genomes of length 2 could exist? Of length 3?

Note: it may be very helpful to write out all the possible genomes by hand.

**Q.2.b.** How does the number of unique genomes grow as you increased the length of the genome? Given a genome length of _n_, how many unique genome of length _n_ could exist?

**Q.2.c.** A microbial genome is approximately _n_ ~ 10<sup>7</sup>. How many unique microbial genomes could be made of this length? We will use this number for the rest of the problem set as an approximation for the number of possible microbial genomes.

**Q.2.d.** Physicists estimate that there are 10<sup>80</sup> atoms in the known Universe ([link to popular science article describing how this number was estimated](https://www.universetoday.com/36302/atoms-in-the-universe/)). How does the number of atoms in the known Universe compare to the number of possible microbial genomes?

## (Q3) How much of the Evolutionary "Search Space" has been Searched? (35 points)

In the previous problem, we estimated how big is the space of all possible microbial genomes (spoiler: very big). In this problem, we will estimate how much of this space has been searched. Thanks to a long-term evolution [experiment](http://myxo.css.msu.edu/) it is possible to estimate that *E. coli* has a mutation rate on the order of 10<sup>-10</sup> (mutations)/(base x generation) [bionumber-source](https://bionumbers.hms.harvard.edu/bionumber.aspx?&id=105813).

**Q.3.a.**  What is the rate of mutations/genome x generation for a typical microbe? That is to say, how many mutations should we expect per individual bacterial genome replication event? Assume the microbe has a mutation rate of 10<sup>-10</sup> (mutations)/(base x generation) and a genome length of _n_ = 10<sup>7</sup>.

**Q.3.b.** Assume there are 10<sup>30</sup> microbes on Earth ([estimate from a 1998 study out of University of Georgia](https://www.pnas.org/content/95/12/6578)). If every one of these microbes replicates all at once, how many mutations should we expect to occur in a single replication cycle?

**Q.3.c.** Life on Earth is approximately 10<sup>9.5</sup> years old. The fastest rate at which _E. coli_ can replicate is about one generation per 20 minutes, or 3 replications per hour. Assume that all microbes can double at this rate. How many microbial generations have passed since life began on Earth? That is to say, how many times would we expect a microbe to have doubled if that microbe had existed since the beginning of life on Earth?

**Q.3.d.** Let's assume that the global population size of microbes remains constant over time. Given your answers for 3.b. (the total number of mutations that arise every time all the microbes in the world replicate) and 3.c. (the number of times microbes could have replicated since life began), how many total mutation events would you expect have happened in Earth's history?

**Q.3.e.** Let's observe two things:

* Microbes in nature are really good at what they do and are highly optimized for their environments
* As you have just calculated, there has not been enough time to search hardly any part of the total search space.

Given that mutations are random, what else is at play in evolution that the resulting organisms are so highly optimized? (1 bullet point)

Note: Question-3 is based on an entry from [*Cell Biology by the Numbers*](http://book.bionumbers.org/what-is-the-mutation-rate-during-genome-replication/), and from material from Dan Fisher's course Evolution by the Numbers [APPPHYS237/BIO251](https://explorecourses.stanford.edu/search?view=catalog&filter-coursestatus-Active=on&q=APPPHYS%20237:%20Evolution%20by%20the%20numbers&academicYear=20182019).

## (Q4)Brainstorming Report-2 (15 pts)

This part must be completed individually

**Q.4.a.** Did you show up on Friday? (Yes / No)

**Q.4.b.** What gift should we get for Emilio? (2-3 sentences)

**Q.4.c.** What questions do you have for Michael about an effective interview? List 3.


# Final Project - Group Activity.2 (30 points)

NOTES:

* Due: Next Friday (May 10) beginning of class.
* Include your group number, names of your group members, and name of your digital (TA) mentor.
* This report is 30 points of your Final Project.
* Please turn in a single electronic copy of your Group Activity via Gradescope.

**Group Activity.2.a.** Please share your team's top selection for the final project. Include the audience, topic, and medium.

**Group Activity.2.b.** Please share two back-up selections for the final project.

**Group Activity.2.c.** Why did your team select your top choice? (about 150 words)

**Group Activity.2.d.** How did you reach your decision? (about 150 words)

**Your questions**
Do you have any unanswered questions (from this week, past weeks, or general BIOE) that you would like to share with us?

## (Extra credit - 5 points)

In Wednesday's lecture, the topic of human reproduction without sex was briefly mentioned. First, read more about this topic from the following interview with Hank Greely [source](https://www.theatlantic.com/health/archive/2017/06/babies-sex/531735/).

([Hank Greely](https://law.stanford.edu/directory/henry-t-greely/) is the Director of the Center for Law and the Biosciences at Stanford Law School. He is the author of the _End of Sex and the Future of Human Reproduction_)

**Extra credit.a.** Who should care about the topic of human reproduction? List six stakeholders and explain why they should care in 1-2 sentences each.

**Extra credit.b.** Who appears to care about this topic? Who is not paying attention but should be? Explain why in 2-3 sentences.

**Extra credit.c.** Imagine that you wanted to introduce this topic to the students in Introduction to Bioengineering next year. In 2-3 sentences state what you would want to make sure students learning about this for the first time would hear from you?

**Extra credit.d.** Do you believe that this future being discussed could come true? For example, could a woman use two skin cells to create a sperm and an egg needed for an embryo?

**Extra credit.e.** What questions do you have about this topic? List up to 5. We will revisit the topic in later weeks.


## Extra learning (100% optional):


#### (Q5) Evolution as a Service (0 points)

**Q.5.a.** Describe two challenges associated with using Directed Evolution as an engineering approach? (bullet points)

Imagine that you want to engineer the rate of evolution (increase or decrease) in an engineered living matter.

**Q.5.b.** Briefly describe a utility for engineering the rate of evolution itself.
Stated differently, Where and how you would use such an organism if you wanted to use evolution as a service?
(2-3 sentences)

#### (Q6) Mutation Rate and Genome Replication (0 points)
**Q.6.a.** Assume there are 10^10  cells in a 5 mL overnight culture of *E. coli* (i.e., 10^10 genomes are replicating during the final doubling). Given the rate of mutation / genome x generation (from 3.a), how many novel mutations do you expect inside the overnight culture?

**Q.6.b.** Given your answer from 6.a and the size of *E.coli*'s genome, is 5mL of the overnight culture sufficent to ensure that you have every single nonlethal base pair substitution in culture? (Yes  / No, Explain your answer in 2-3 sentences)

####  (Q7) Microbial Resistance (0 points)
According to recent news reports, a patient with a multi-drug resistant bacterial infection was cured by injecting
phage (i.e., bacterial viruses [The Bacteriophage Video](https://www.youtube.com/watch?v=YI3tsmFsrOg)) directly into the bacterial cyst inside thepatient’s abdomen. The patient was ultimately cured. The treatment, however, was not easy...

“The learning curve was steep and unmarked. There were bouts of sepsis — a life-threatening omplication caused by massive infection. Despite improvement, (the) patient’s conditionremained precarious. Doctors discovered that the bacterium eventually developed resistance to the phage, what Schooley would characterize as “the recurring Darwinian dance,” but the team compensated by continually tweaking treatment with new phage strains — some that had derived from sewage — and antibiotics.” [source](https://health.ucsd.edu/news/releases/Pages/2017-04-25-novel-phage-therapy-saves-patient-with-multidrug-resistant-bacterial-infection.aspx)

**Q.7.a.** From the above text and thinking back to what you learned about evolution, what are the challenges associated with implementing Phage therapy?


<sub><sup> [github source code](https://github.com/Stanford-BioE80/Stanford-BioE80.github.io/edit/master/_docs/w5ps.md) for teaching staff <sub><sup>
