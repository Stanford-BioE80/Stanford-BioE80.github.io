---
title: "Week 6 PSET"
permalink: /docs/w6ps/
2018:
---

## (Q1) Spatial DNA devices (20 pts)

Two DNA devices have been engineered for use in a *cell-free extract* solution (known as GOOP) (Figure, below).  GOOP is the transcription - translation machinary harvested from cells.  DNA devices gets activated when GOOP reachs them. 

- Device A expresses protein A in the absence of protein B.  

- Device B expresses protein B in the presence of protein A.  

- Device A can also make GFP.  

Each device is placed in a distinct reservoir within a micro-scale fluidic channel. 

Fresh GOOP is supplied from one end of the channel.   Using various channel lengths experimenters are testing a genetic system made from the two devices.

**1.a.**  By studying the diagram in Figure 1.B, describe the expected relationships and behavior of the system.  
(1-2 sentences max)

**1.b.** Fig. 1.C shows two spatial arrangements of the genetic system. In the top arrangement device A is 50 µm away from device B. In the lower arrangement device A is 150 µm away from device B. The time responses for each arrangement is measured by GFP production from device A as presented below.  Does “trace-1” come from the 50 µm or 150 µm arrangement?

**1.c.** Explain your choice. (Hint: think about diffusion) (1-2 sentences max or math)

<figure>
<a href="/assets/images/Spatial GOOP.png"><img src="/assets/images/Spatial GOOP.png"></a>
<figcaption><b>Figure 1</b>. Spatial GOOP .</figcaption>
</figure>


## (Q2) Diffusion, Diffusion constant, and Diffusion time (25 pts)

 In the class you were introduced to diffusion both qualitatively.
 In this question you will additionally explore diffusion quantitatively.

First let's warm up:

Diffusion coefficient is described by the following equation: D=k<sub>B</sub>T/6πηa

 - k<sub>B</sub> is Boltzmann's constant (1.3807 x 10 ^-23 J/K),
 - T is the temperature (K) of the surrounding medium ,
 - η is viscosity of surrounding medium (N x s / m^2),
 - “a” is a measure of length (radius of a sphere approximating the molecule).  

 **2.a.** Using above determine the units for diffusion coefficient? (show your work)

You learn that the diffusion coefficient for a protein (~30 kDa GFP) in water is about 100 µm^2/s.
The diffusion constant for the same protein is in the cytoplasm of a eukaryotic cell is only 30 µm^2/s.

**2.b.** Intuitively do these numbers make sense? (Yes or No) Why? (Bullet points)

Next, let’s estimate the time it takes for a protein to diffuse spontaneously across different types of cells
(diffusion time τ). We will use the formula $ τ=\frac{R^2}{6D} $, where R is the traverse distance.

**2.c.** Calculate the times it takes for the protein (~30 kDa GFP) with a diffusion constant D=30 µm^2/s to diffuse across four different cell types:

(i) *E.coli* with R≈1 μm,

(ii)  Yeast cell with R≈10 μm,

(iii) HeLa cell with R≈20 μm, and

(iv) A neuronal cell axon with R≈1 cm.

(Extra- activity create a plot that demonstrates the relationship between τ vs R)

**2.d.** What does the the diffusion time for the axon suggests to you?

This question is from the [Cell Biology by the Numbers](http://book.bionumbers.org/what-are-the-time-scales-for-diffusion-in-cells/)

## (Q3) Bacterial Edge Detection (10)

We have talked about engineered *E.coli* which detects light earlier in the quarter. 

Building on earlier [work](https://www.nature.com/articles/nature04405) first published in 2005, Jeff Tabor and colleagues eventually demonstrated a bacterial edge detection system. 

In their system a bacterial lawn (i.e., a uniform layer of identically engineered bacteria growing on a plate) detect a light-encoded image. The bacteria are initially all the same but, depending on whether they are exposed to light or not, send or receive small molecule-encoded signals that diffuse across the light/dark boundary.

Only bacteria positioned at the boundary between light and dark express an enzyme that results in formation of a dark pigment (HINT: see Figure and also the primary [source](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2775486/) article).

<figure>
<a href="/assets/images/pset8_fig.2.png"><img src="/assets/images/pset8_fig.2.png"></a>
<figcaption><b>Figure 2</b>. Bacterial edge detection.</figcaption>
</figure>

Take a look at the photo of the system in action. Note the edge detection in the case of a square or Alfred Hitchcock’s portrait.

**3.a.** What do you observe? Are all the edges uniform?  (1-2 sentences)

**3.b.** Using concepts from this week, why is there more pigment inside the corners of the square, or inside the bottom left angle of Alfred’s portrait?

## (Q4) Regrowing a newt arm (25 pts)

Please watch this [video of a newt regrowing its arm](http://www.hhmi.org/biointeractive/newt-limb-regeneration).  How does this work? Let's apply the concepts we've learned from dancing droplets challenges to figure this out from a programming patterns perspective. 

**Q.4.a. "The hand of god"**

Pictured below is a newt's body with five regenerative cells (green circles) that are ready to regenerate a limb. You are a sculptor of limbs and create a physical scaffold that outlines and limits the aggregate shape that the cells should grow into. The cells just need to grow into the shape that you’ve defined (the simple “bent-arm” solid line trace). 

***What do the cells need to do in order fill the physical form you have preshaped for them?***
<figure>
<a href="/assets/images/Week-6-pic1.png"><img src="/assets/images/Week-6-pic1.png" height="500"></a>
</figure>

**Q.4.b. "Celestial navigation"** 

Next, consider a different set of starting conditions: <i>You no longer exist</i>. In the picture below, the newt still has to regrow its arm into the shape indicated by the faint dotted line, but this time, without your barrier into which the cells could simply grow. However, two external beacon cells have been added to the system (purple, blue).  Each beacon cell emits a distinct and freely diffusing small molecule that the regenerative cells (green) can detect and respond to as you like (i.e., attract, repel, other). Purple and blue cells’ signaling molecules diffuse simply (see “time > 0” inset). 

***Develop a biological pseudo-code routine that details how the five green cells can grow into the desired pattern in response to the signals initially emanating from the external beacons.***
<figure>
<a href="/assets/images/Week-6-pic2.png"><img src="/assets/images/Week-6-pic2.png" height="500"></a>
</figure>

**Q.4.c. "Full autonomy"** 

Finally, pictured below is a newt that needs to regrow its arm using only its own regenerative cells (there are no external inputs to the system). The two outside regenerative cells have differentiated into distinct left and right cells (below). 

***Develop a biological pseudo-code routine that details how the five originating cells (purple, green, green, green, blue) can grow into the desired pattern by themselves, using no outside information or control.***
<figure>
<a href="/assets/images/Week-6-pic3.png"><img src="/assets/images/Week-6-pic3.png" height="500"></a>
</figure>


## (Q5) Paper reading activity (20 pts)

First examine,[A synchronized quorum of genetic clocks](https://www.nature.com/articles/nature08753).

**Q.5.a** In your own words, what is the primary claim of the paper? What are the primary evidence in support of the claim? (2-3 sentences)

**Q.5.b** In your opinion, what are the paper’s strengths and significance? What are the paper's shortcomings and deficiencies? How can the paper improve?

*Additional Resources*    

### (Q6)  Dancing Droplets (0 pts)

On Wednesday you experienced (or read about) the the Dancing Droplets.  Use pictures, diagrams, or drawings as appropriate.

**6.a.** What rule did you observe (or read) about - which droplets chase which?  

**6.b.** Why does the sharpie marker create a physical barrier and how do the droplets respond to it?

**6.c.** To what extent were you able to realize increasingly autonomous behavior? 

**6.d.** How would you use autonomous behaviors (with droplets or cells) to generate pattersn?  What patterns will you build - what will they do? How good do we have to become at implementing autonomous behaviors to achieve your patterns? 
(2-3 sentences)

*Extra-activity*  Make your own dancing droplet video (30 to 60 seconds) with your own choice of background music and share a link with us.


The following link takes you to a paper titled [Life at Low Reynolds Number](https://www2.gwu.edu/~phy21bio/Reading/Purcell_life_at_low_reynolds_number.pdf) that examines physics at the scale of a bacteria.  

*The following links* are **explorables** that can help you explore and build an intuition about patterns and pattern formation.  We hope that you take some time and examine them on your own:


(1) [Fireflies and Patterns](http://ncase.me/fireflies)

(2) [Explorables Collection ](http://www.complexity-explorables.org/explorables/)


<sub><sup> [github source code](https://github.com/Stanford-BioE80/Stanford-BioE80.github.io/edit/master/_docs/w6ps.md) for teaching staff <sub><sup>
