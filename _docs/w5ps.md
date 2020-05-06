---
title: "Week 5 Problem sets"
permalink: /docs/w5ps/
---

**PSET #5**

ASSIGNED: Friday 08 May 2020

DUE: 5:00p Pacific 15 May 2020

**NOTES:**

- Given the unique circumstance of Spring 2020, we ask you to do your best to maximize your learning. Each problem set is an opportunity to assess your learning, identify gaps, reflect on what you have learned, and determine what you wish to learn next.
- You can discuss the PSET questions with other students. But your answers should be your own work. Please let us know if you collaborated with other students working on the PSET. 
- Please turn in your completed problem sets as an electronic copy via Gradescope. Please make sure to clearly indicate the starting and ending boundaries of your answers to each question on Gradescope.
- Please do not go over any word limits and where appropriate show your work (e.g., calculations with appropriate units).
- Please **type** your answers. 
- Please **label** and provide descriptions for the figures. 

**GOAL:** Welcome to PSET-5. This problem set will help you describe how DNA read and write work. You will examine the consequences of non-trivial *quantitative pacing* in the development of these technologies. Finally, you will examine the consequence of  interconvertability of matter and information as DNA read and write tools improve and discuss the *qualitative changes* that emerge.

## (Q1) DNA as a Storage Medium (35 pts)

The US government has been using an underground salt mine in Pennsylvania as a long term storage facility for physical documents, primarily retirement related papers. According to the Washington Post, in this facility approximately 1000 employees pass thousands of case files from cavern to cavern and then type in retirees’ personal data, one line at a time. Basic document retrieval involves a forklift and takes days. 

Given the trends in DNA read and write, consider using DNA as an alternative storage medium for these documents.

Helpful numbers:

- Volume of storage facility = $10*10^6 m^3$
- Letters per cubic meter of typical government document = 10^9 letters/m^3
- Volume of a DNA base pair ~ $10^-27 m^3$

Please round or simplify whenever convenient. **Please show your work and include units.**

**Q.1.a.** Since DNA has only 4 bases, but English has 26 letters, you will somehow have to map letters to bases. 
Briefly specify a simple encoding scheme for mapping bases into the 26 English letters. (You *do not* have to give a letter to DNA mapping for all letters. The first few will do the trick.)
 
Hint-1: In your encoding scheme, the length of bases should be consistent for the entire scheme. 
Hint-2: What is the minimum number of bases you need to map the entire 26 English letters. Consider what would be the problem if you pick 2 bases (AA, TA, CA, GA,...) to map 26 letters. 

**Q.1.b.** Using your letter to DNA mapping, how many total base pairs of DNA would be needed to store the archival contents of the salt mine. Assume that the salt mine is completely packed with documents.
Hint-3:  Your math should follow 

**Q.1.c.** What would be the physical volume of DNA encoding the salt mine documents?  Will the DNA fit into a thimble?  Yes / No

**Q.1.d.**  How expensive would it be to print the DNA (assume cost ~1 cents/base)?  Compare your number against the United States GDP (20.54 trillion USD - 2018)

**Q.1.e.** Give two major advantages and two major disadvantages of using DNA as storage medium (4 bullet points)

**Q.1.f.** Can information be stored in the DNA in a living organism as opposed to DNA stored in a frozen tube (-80 freezer). If yes, what are one advantage and one disadvantage of using live cell storage? (2 bullet points)

Helpful resources:
- [How DNA Could Store All the World's Data](https://www.nature.com/news/how-dna-could-store-all-the-world-s-data-1.20496), - [Taking Cells to the Movies](https://wyss.harvard.edu/taking-cells-out-to-the-movies-with-new-crispr-technology/)


## (Q2) Sequencing the Total DNA in the Biosphere (20 pts)

**Q.2.** The following [paper](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002168) estimates that there are about $5.3 * 10^37$ bases of DNA in the biosphere.  

Given the increasing trends in productivity of sequencing. In what century can a team of 10 sequence 5.3 x 10^37 bases in a month?  We will use the information from Carlson Curves to provide a projection. 

![Carlson Curves](/assets/images/PSET6_Crlson_Productivity.png
 "Productivity in DNA Sequencing and Synthesis")
 
 There are many ways to solve this problem. Your final number will deponds on and is sensetive to your assumptions.  
 You can use your own method or use the suggested assumptions and steps
   
Assumption.1:
- Let’s assume the trend in sequencing productivity since 2005 will continue.  
Specifically let’s estimate 2005 productivity 10^7 (bases\ person\day) and let’s estimate 2010 productivity to be $10^10  (bases\ person\day).  We can use these numbers to say every 5 years sequencing productivity will get 1000x better.

Assumption.2:
- From the graph we can estimate our current productivity at 10^11 (bases\ person\day)

Step-1 (you have do some math here):
- Let’s normalize total DNA: $5.3 x 10^37$ bases releative to our team size (10) and the required time (30 days).

$ productivity (bases\ person\day)= \frac{Total DNA}{\(team size x 30 days)}$

Step-2 (you have do some math here):
Construct a function with time as the variabl that relates the productivity rate, current productivity, and normalize total DNA.
 
- Normalize total DNA: Y(t)
- Current productivity: P0
- time with units of number of five year periods: t
- Current productivity rate: R (we estimated to be 1000)
 
$ Y(t) = function (P0, R, t)$
 
$ Y(t) = P0 * R^t $

To solve for number of five year periods you have to take $ log $ of both sides. 
 
 Step-3 (you have do some math here):
 Change number of five year periods to years and add to initial time (2015).
 
 
 
 
 
 
 
 
 
 
 ## Final Notes 

This week you learned about tools and technologies that enable DNA read and write. As part of your core bioengineering skills you should be able to describe how these technologies work. You also learned about the non-trivial speed of development in these technologies and the various ramifications of this development.

**Do you have any unanswered questions (from this week, past weeks, or general BIOE) that you would like to share with us?**


## Extra learning (100% optional):

### (Q4) (Nature + Nurture) or (Fab a Family) (0 pts)

Over the past 12 years the price of synthesizing genes has dropped from $4 to $0.04
per base pair; presume the future price of DNA synthesis will continue to drop two fold every two years.

Meanwhile Stanford’s undergraduate tuition is approximately $50,000 per year up from $25,000 in 2000.  
Presume Stanford’s tuition will continue to double every 15 years.

**Q.4.a.** If a human genome is 4 billion base pairs long then when will the cost of synthesizing the DNA encoding an entire human genome be roughly the same as the tuition cost associated with attending Stanford for one year?

Hint: Use the facts given. Keep your math simple, and write out the equations (i.e., show your work).
An approximate answer is fine.

**Q.4.b.**  What would be your estimate if the price of synthesizing genes continue to drop two fold every 2.5 years instead of 2 years (i.e., only a 6-month longer doubling time). An approximate answer is fine.

**Q.4.c.** Given your answer from part (a) presume that you could then design, build, and bring to life a human encoded by a genome that you design (e.g., with any and all mutations that you and your partner choose).  As potential parents would you prefer to spend your savings on college tuition for a natural child or on realizing a genetically engineered offspring who then has to make  their own way? Why? (2-3 sentences)

### (Q5)Sequencing and Synthesis technologies (0 pts)

In the pre-class material you were introduced to a DNA read method commonly referred to as next-generation sequencing (NGS) or massively parallel sequencing. Let’s examine an alternative approach, namely nanopore sequencing.

Watch this [video](https://nanoporetech.com/products/minion)

**5.a.** Describe how Nanopore sequencing works (use bullet points)

MinION is a product that uses Nanopores for sequencing.
While the error rate with Nanopore technology is between 5-10%. [additional Link](https://f1000research.com/articles/6-760/v1). This tool can be used to sequence and assemble a human genome
[additional link](https://www.nature.com/articles/nbt.4060).  Now briefly examine the various products sequencing technology from Illumina [link](https://www.illumina.com/systems/sequencing-platforms/comparison-tool.html).

**5.b.** How are NGS and Nanopore sequencing different?

**5.c.** Imagine that the storage of information in DNA from the previous question has become a routine platform.
You have been hired as a consultant for a library that seeks to store its archive inside the DNA medium.
Your task is to determine suitable reading platforms. What type of“read technology” would you recommend:
a sequencer that gives massive simultaneous short reads with very low error,
or fast readers that reads long sequences with error rates as high as 15 %.
Please include quantitative reasoning in your answer.  

**5.d.** Where would you use an Illumina sequencing machine instead of a minION sequencing machine?
and vice versa?

 
 
 Adjust the total sequence for time (assume there are 30 days per month) and team size (10 people).  To do so 
