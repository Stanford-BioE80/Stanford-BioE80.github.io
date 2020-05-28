---
title: "Week 8 Problem Set"
permalink: /docs/w8ps/
2018: Week 4
---

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

## (Q4)Paper reading activity (15 points) 

Read the following paper, [Fail-safe genetic codes designed to intrinsically contain engineered organisms](https://academic.oup.com/nar/article/47/19/10439/5568210)

**Q.4.a** In your own words, what is the primary claim of the paper? What are the primary evidence in support of the claim? (2-3 sentences)

**Q.4.b** What are the paper’s strengths and significance?  (Bullet points) 


**Q.4.C** What are the paper’s shortcomings and deficiencies? How can the paper improve? (Bullet points) 

## Extra Credit - Design and solve a problem (20 points)

Design your own BIOE\ENGR 80 question based on any of the material that we have covered so far in the class.  A student successfully finishing BIOE\ENGR 80 should be able to answer your question.  

Start by thinking about your learning goals.  What do you expect the learner by engaging your question?  Next, provide an answer to the question. Your questions can have multiple parts.  Make sure to include references if you draw inspiration from a source. 

<sub><sup> [github source code](https://github.com/Stanford-BioE80/Stanford-BioE80.github.io/edit/master/_docs/w8ps.md) for teaching staff <sub><sup>
