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

- Volume of storage facility = $10x10^6 m^3$
- Letters per cubic meter of typical government document = 10^9 letters/m^3
- Volume of a DNA base pair ~ 10^-27 m^3

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

**Q.2.** The following [paper](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002168) estimates that there are about 5.3 x 10^37 bases of DNA in the biosphere.  

Given the increasing trends in productivity of sequencing. In what century can a team of 10 sequence 5.3 x 10^37 bases in a month?  We will use the information from Carlson Curves to provide a projection. 

To do so you can use the following step by step approach. 

![Carlson Curves](/assets/images/PSET6_Crlson_Productivity.png
 "Productivity in DNA Sequencing and Synthesis")
 
 - Step.1: Determine the team's productivity given a month (assume 30 days per month).  

$
productivity= \frac{bases}{\lpersonxday} x \frac{10 person}{\team} x \frac{30day}{\month}
$

 - Step.2: Determine inital conditions from the curve.  
 Let's say we assume t=0, 
 
 

 
 
 Adjust the total sequence for time (assume there are 30 days per month) and team size (10 people).  To do so 
