---
title: "Week 2 Inclass"
permalink: /docs/w2inclass/
last_modified_at: 2018-11-25T22:21:33-05:00
toc: true
---

## Monday In Class

How do engineers engineer with, of, and for biology?

Puzzle Questions

- Q1 (True / False): The framework of design-build-test - while integral to engineering fields - can be used to engineer solutions to diverse problems, whether engineering a tangible object in a lab or developing a plan to alleviate widespread social need. 

- Q2 (True / False): The DBT process, if done correctly, helps you get to your goal on the first try. Which is good because it doesn't help you improve if you were to fail. 

- Q3 (True / False): Building off an iGem project, the team behind KumaMax used a unique approach to the development of a biologic therapeutic that alleviates diabetes. 

- Q4 (True / False): Mutations to Kumamolisin-As were modeled using the computational protein folding tool FoldIt.

- Q5 (True / False): The wild-type (original, found in nature) version of KumaMax actually didn't have specificity for gliadins. 

- Q6 (True / False): The wild-type version of KumaMax (Kumamolisin-As) was primarily chosen because it is active at low pH, making it a good match for the conditions in the small intestine. 

Q -- Kiva is a web platform that allows people to crowdfund presents and other non-essential purchases using Amazon's online gift registry system.

Q -- New or improved drugs can only be developed by project managers at big pharmaceutical companies.

Q -- The wild-type version of KumaMax (Kumamolisin-As) was primarily chosen because it is active at low pH, making it a good match for the conditions in the small intestine.

## Friday In Class GOOP
### Module 1: The Expression StatementIn 

this module we’ll learn about and execute the biomolecular equivalent of the ‘print’ statementby producing green fluorescent protein, or GFP. GFP and other fluorescent proteins are oftenused as an output to indicate the state of a genetic circuit, report on a sensor, or to identify cellscontaining a specific genetic payload. When it is produced, GFP is a visible yellow color (underambient light). When illuminated with light at 485 nm (blue), GFP produces fluorescent light at 510 nm (green).

**Figure 1.** GOOP tubes with and without the addition of expression statement (producing greenfluorescent protein).

### Safety
There are no special safety concerns for this module. Recall that GOOP both cannot replicate,and is based on a BSL-1 organism. The green fluorescent protein is not known to be hazardousto health or the environment.

### Unpacking the Central Dogma

In the Preclass introduction, we discussed the central dogma of biology. Here, we explain howa particular gene ends up as a functional protein both inside a cell, or inside tubes. When aspecific gene is transcribed and translated, we say that is is **expressed**.

First, our gene must be transcribed. For transcription to occur, the gene must be inside atranscription unit. A transcription unit is composed of two special DNA sequences, a **promoterand** a **terminator**.

During transcription, RNA polymerase recognises the promoter DNA sequence and binds to it,beginning transcription at the transcription start site, just downstream of the promoter sequence.It then transcribes DNA to RNA until it reaches the terminator sequence. At the terminator, theRNA polymerase releases the DNA and the new RNA transcript.

Now the RNA transcript must be translated to a protein. The ribosome binds to a specificsequence on the RNA transcript, the **ribosome binding site**, and then searches along thetranscript until it finds the beginning of the gene sequence. The gene sequence begins with a **start codon**. The ribosome then translates codons into amino acids until it reaches a **stop codon**.

This combination of promoter, ribosome binding site, gene sequence, and terminator gives usour transcription unit and a complete construct with which to express a gene. We can alsoconsider this transcription unit a simple genetic **device**. There are a number of differentpromoters, ribosome binding sites, and terminators. Each behaves differently: differentpromoters may only be transcribed under certain conditions, or at different levels; ribosomebinding sites may be more or less attractive to the ribosome, changing the level of translation,and terminators can be ‘leaky’, only terminating transcription some of the time. Together withthe enormous diversity of genes available across the tree of life, these components make up thesimplest ‘parts’ we can use to build complex circuits.

### Expression Device (the ‘print’ statement)

For our expression statement, we’ll need the following:
- **p70a** a promoter that is active by default in GOOP, and initiates transcription at a highlevel.
- **UTR1** a sequence containing an efficient ribosome binding site.
- **deGFP** the coding sequence, or gene, for a green fluorescent protein, optimized for expression in GOOP.
- **T500** a strong (non-leaky) transcriptional terminator.

### Visualizing GFP with PyMol

While your GOOP is running, check out the structure of the GFP protein encoded by the DNA you used. 

For more information about GFP check out: [PDB Link](http://pdb101.rcsb.org/motm/42)

 1. Open PyMol on your laptop. As part of the pre-class assignment, you should have downloaded PyMol from this [Pymol Link]( https://pymol.org/2/)
 
 2. Type in the command “fetch 1gfl” in PyMol. This command downloads the structure ofGreen Fluorescent Protein (GFP) from the Protein Data Bank (PDB)
 
3. Check out the website where the GFP structure is housed:https://www.rcsb.org/structure/1gfl
 
4. Go back to PyMol and take a look at the GFP structure.  Click Hide everything and ‘Show cartoon’, under the menus “H” and “S”  listed near the structure name on the toolbar on the right. The GFP structure is a *beta barrel*. This means it is made up of abarrel formed by *beta strands*, a known type of secondary structure proteins adopt.

5. Click on   <Mouse → 1 button viewing> to enable scrolling.

6. Click on   <Display → Sequence On> to see the amino acid sequence for GFP.

7. Select residues 64-66 SYG and color these residues red. This is the *chromophore* of GFP, the portion of the molecule responsible for the fluorescence.

8. Render the SYG portion of the protein as ‘sticks’. You should now be able to see the cyclized ring of the GFP chromophore. This cyclization, as shown below, is part of the *maturation* process of the protein -- after maturation, the protein is able to fluoresce.

9. Take a screenshot of your highlighted protein structure for the problem set 2.


### GOOP Experiment

To set up our prototype experiment, we will our GFP device in a GOOP tube, following theinstructions in the kit introduction. We will also set up a *negative control*: a reaction tube withno DNA at all. We do this so that we can observe what GOOP by itself looks like, and compareit to our prototyped device.

In your kit you have:

- 2x GOOP reaction tubes labeled (G)
- 1x Module 1 DNA parts kit  labeled (D)
- 1x Pure water  labeled (W)
- 2x Transfer pipettes

1. Set up two tubes following experiments (additional instructions from the Pre-class):

2. Note the time and let the reactions run. Take a photo of your tubes (at time zero). You shouldbegin seeing a color change after about 6 hours; after 12 hours there should be cleardifferences.

3. Take a photo of your GOOP tubes at the end of the experiment for the associated problemset. If you don’t see a difference between the tubes, don’t worry, but still take a photo. Note the time that you take your final photo (the endpoint of the experiment).


In today’s activity, you:
- Learned about the core genetic components necessary to express a gene
- Expressed your first gene in GOOP, producing green fluorescent protein
- Visualized the structure of the protein using PyMol.

By switching out the gene of our simple expression device, we can produce any protein from across the tree of life (although complications can arise). For example, by building an expression device with the gene you submitted to the Free Genesproject, you could produce the protein it encodes and test its function. Moreover, by changingother parts of the expression device (such as the promoter) you can control other aspects ofexpression, and by combining these simple devices we can build more complex circuits.

#### Additional Resources:

**Fluorescent Proteins:**
1. Fluorescent Proteins and the Story Behind GFP (by Roger Tsien ibiology) [link](https://www.ibiology.org/talks/fluorescent-proteins/)

2. Introduction to Fluorescent Proteins [link](https://www.microscopyu.com/techniques/fluorescence/introduction-to-fluorescent-proteins)

3. Interactive graph describing Fluorescent protein properties [link](http://www.fpvis.org/FP.html)

**Basic Parts:**

1. Adventures in Synthetic Biology - [comic book](http://web.mit.edu/endy/www/scraps/comic/AiSB.vol1.pdf)

2. iGEM Parts Expression [parts](http://parts.igem.org/Main_Page)

3. Expression statement DNA sequence designs [sequence](https://benchling.com/acjs/f_/MGZTmIMA-module-1/?sort=name&section=inventory&filter=archivePurposes%3ANOT_ARCHIVED)
