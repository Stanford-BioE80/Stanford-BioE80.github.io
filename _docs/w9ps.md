---
title: "Week 9 Problem setslass"
permalink: /docs/w9ps/
---

**DUE:** Next Week, beginning of class.

**NOTES:** 
  - All BIOE.80 problem sets must be completed individually unless plainly noted otherwise.
  - Please turn in your completed problem sets as an electronic copy via Canvas. 
  - Please make sure to not go over the word limits and when appropriate show your work (e.g., calculations).


**Goals:** Welcome to PSET-9: After this problem set you will be able to quantitatively estimateand describe what happens in diffusing systems (e.g., how long does it take for a protein tomove inside a cell).  
You will also be able to describe how simple rules can give rise to complexpatterns both in living matter 
and abiotic systems.

## (Q1) Diffusion, Diffusion constant, and Diffusion time (20 pts)

 In the class material you were introduced to diffusion both qualitatively and quantitatively.
 In this PSET you will use these concepts for simple estimations. First let's warm up:
 
 1.a. A diffusion coefficient is quantitatively described by the following equation.   
 Where D=kTB/6πνa is Boltzmann's constant (1.3807 x 10 ^-23 J/K), T is the temperature (K) of the   
 surrounding medium ,ν is viscosity of surrounding medium (NxS/m^2), “a” is a measure of length 
 (radius of a sphere approximating the molecule).  What are the units for a diffusion coefficient? (5 pts)
 
 
1.b. You learn that the diffusion coefficient for a protein (~30 kDa GFP) in water is about 100 µm^2/s.
The diffusion constant for the same protein is in the cytoplasm of a eukaryotic cell is only 30 µm^2/s.
Intuitively do these numbers make sense? (Yes or No) Why? (Bullet points)
Using these numbers estimate the viscosity of the cytoplasm relative to the viscosity of water? 
(10 pts) (HINT: solve for using the equation given above).

Next, let’s estimate the time it takes for a protein to diffuse spontaneously across different typesof cells 
(diffusion time τ). We’ll use the formula τ = R^2/6D, where R is the traverse distance.


Add Figure-1 here. 

1.c. Calculate the times it takes for the same protein (~30 kDa GFP) with a diffusion constant D=30 µm^2/s to diffuse across four different cell types: 

(i) *E.coli* with R≈1 μm, 
(ii)  Yeast cell with R≈10 μm, 
(iii) HeLa cell with R≈20 μm, and
(iv) A neuronal cell axon with R≈1 cm.
What doesthe the diffusion time for the axon suggests to you? (5 pts)


## (Q2) Physical Limitations on Development (40 points) - Remove

Here’s a sketch of a planarian, which is a type of very flat worm. The aquatic species of these worms can grow to be a few centimeters long. Notably, these worms have no circulatory system, so all nutrient and essential transport processes are entirely passive; which means that diffusion dominates. How do these worms handle transport of oxygen? Humans have a circulatory system which ensures that cells all across our many tissues have an adequate oxygen supply. However, planarians have no circulatory system but they do have a gut cavity! Their gut cavity has many branching tubes that supply oxygen to the worm’s tissues by allowing oxygen to passively diffuse out of the water and into the worm. In this question, we’re going to understand, from an engineering perspective, how the planarian is optimized to handle the “logistics” of its oxygen supply. 


Add Figure-2 here. 


2.a. Consider a model cross-section of a planarian on the left. Oxygen rich water flows within the gut and around the worm in the surrounding fluid. Assume that the concentration of oxygen is C0 both inside the gut and outside the worm (anywhere there is blue). Assume that the tissue consumes oxygen at some rate k. Use the graph on the right to draw your best guess for what the concentration of oxygen looks like across the planarian tissue. Plot some additional curves showing the concentration of oxygen as the rate of oxygen consumption k increases and decreases. Make sure you label your curves so we know whether k is increasing or decreasing. (15 points)


2.b. Now that we’ve thought about things in the abstract, let’s get quantitative. Consider the reaction-diffusion equation (15 points):

Equation-1 goes here 

At this point, we don’t expect you to solve partial differential equations from scratch, but we can use this equation to get to a point where you can come up with a closed-form solution. First, we make a steady state assumption, which means that anything as a function of time is constant because things aren’t changing at a dynamic steady-state. Therefore, we can set:

Equation-2 goes here 

Now the equation is a simple differential equation that can be solved with integration.

Equation-3 goes here 

Solve the equation above for C(x). You’ll need to use these equations to solve for the constants of integration: C(0) = C0  and C(L) = C0 ... These are called boundary conditions, and they signify that we know that the concentration of oxygen inside the worm’s gut and outside in the surrounding water are both fixed at C0. Finally, assume that the length of the worm’s tissue from gut to outside is L. (**Note:** If you are not familiar with calculus, please seek help during office hours)

2.c. Assume that planarian tissue requires at least 13C0 concentration of oxygen to survive. What’s the maximum tissue thickness L that can be attained? (5 points)

2.d. Why do you think a planarian is so flat? (5 points)


## (Q3) Dancing Droplets (20 pts) 

3.a. Were you able to get droplets chase one another? If you have two different droplets, why dothey chase each other? What other behaviors have you observed? (Include photos with figure captions - if you have)(Max 100 words, 10 pts)


3.b. Why does the sharpie marker create a physical barrier and how do the droplets respond to it?(Max 75 words, 10 pts)


3.c. To what extent were you able to enable increasingly autonomous droplet behavior?(Max 75 words,  5 pts)


3.d. How good do we have to become at implementing these different frames of reference inorder to engineer living matter? 
(Max 50 words,  5 pts)


**Final Notes:**  In week 5 you explored the intersection of physics and living matter. You explore ddiffusion, and how to use diffusion to engineer  both *temporary* and *permanent* pattern viacell states and functions. You further explored biased random walks and how cells move andfind resources.


**Your questions**
Do you have any unanswered questions (from this week, past weeks, or general BIOE) that you would like to share with us?


*Additional Resources*    

The following link takes you to a paper titled [Life at Low Reynolds Number](https://www2.gwu.edu/~phy21bio/Reading/Purcell_life_at_low_reynolds_number.pdf) that examines physics at the scale of a bacteria.  The following link takes you to a digital copy of a great book titled [The Machinery of life](https://searchworks.stanford.edu/view/11568895) which can help you with the concepts we have covered both this week and in previous weeks.

*The following links* are **explorables** that can help you explore and build an intuition aboutpatterns and pattern formation.  We hope that you take some time and examine them on your own:


(1) Fireflies and Patterns: http://ncase.me/fireflies/


(2) Diffusion limited aggregation: http://rocs.hu-berlin.de/explorables/explorables/dla/


(3) Reaction diffusion system: https://pmneila.github.io/jsexp/grayscott/

