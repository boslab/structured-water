# Introduction

Cryptobiosis describes the suspended animation that some microbes enter under adverse conditions such as drought, cold, and lack of oxygen.
The kingdom fungi possesses a relatively well conserved and multifunctional signalling network called the Mitogen Activated Protein Kinase (MAPK) pathways that respond to changes in osmosis, light, pH, pheromones, etc.

This paper examines the physical chemical properties of supercooled aqueous solutions, and the physiological tolerances of filamentous fungi, to develop an inexpensive storage medium.
The parameters for success in this experiment include confirming that cultures are not only alive, but can also produce fruitbodies and spores upon revival.

Successful long-term culture storage is critical to any serious mushroom-related endeavor.
For basidiomycete (mushroom forming) fungi it remains an open problem.
The basidiomycete MAPK network, similar but different among species, is also implicated in
- cell morphology (highly variable from spore to shroom);
- sexual reproduction, including fruiting ability; and
- secondary metabolites of possible clinical significance.

My prior work on long-term storage
[diybio/water-cultures](https://pjc.is/diybio/water-cultures) and [diybio/perlite-protocol](https://pjc.is/diybio/perlite-protocol)
describes useful lessons in the state of the art.
This paper describes a novel medium informed by mammal flesh storage that
- uses a combination of nontoxic cryoprotectants like DMSO, glycerol, and tetralose;
- has a glass transition temperature around –20 °C for cell vitrification;
- quickly changes to a liqid at room temperature, allowing convenient revival;
- provides essential nutrients with low quantities of basal sugar and salt; and
- requires no specific equipment or recurring costs to successfully reproduce.

The medium should exhibit ideal properties at –20 °C, exert just enough osmotic stress to force hardship metabolism, and not otherwise starve the fungi.
A member of the Shroomery's PhD tribe inspired this work, suggesting that "sometimes the deep freeze isn't the answer."


# Materials and methods

The deionized water came from [add supplier] in [add city].
The USP glycerol came from [add supplier] in [add city].
The USP DMSO came from [add supplier] in [add city].

The cryotubes came from [add supplier] in [add city].
The freezer came from [add supplier] in [add city].


## Developing a test medium

I made blank tubes, standard 1.5 mL Eppendorfs, to produce multivariate freeze point data.
Equipment that measures ice granulation is beyond my grasp, so I reconstructed hypothetical curves from 30 data points.

Note that I used binary data (frozen or not?) and macro inspection (relative crystallization?) to estimate the curves.
All the measures below are in % w/v per 1 mL deionized water.
The basal saline is 50:50 sea salt and light malt extract.

| DMSO	| ×	| Glycerol	| ×	| Saline	|
| :--:	| :--:	| :--:		| :--:	| :--		|
|	|	| 5%		|	|		|
| 15%	|	| 10%		|	| 0.9% NaCl	|
|	| ×	| 15%		| ×	| 0.6% basal	|
| 20%	|	| 20%		|	| 0.3% basal	|
|	|	| 25%		|	|		|

I established scaled-down quantities to 1 mL test tubes with [Aqua-Calc's conversion tools](https://www.aqua-calc.com/calculate/weight-to-volume).
None of the tubes were made in a sterile environment, so random cells existed to act as possible granulation points.

| ![](DMSO.water.freezing.jpg)	|
| :--				|
| Freezing Point Data for DMSO Water Solutions from https://www.gaylordchemical.com/literature/dmso-physical-properties/ |

The goal was to find a ratio of glycerol, DMSO, and media that behaved like a thick liquid or gel at –20 °C and vitrified the cells.
Additionally, the solution had to exert the minimum osmotic stress necessary to activate the Hog1 (high osmolarity glycerol) orthologues of diverse fungi.

The value of the real parameters is error-tolerant ±5 °C as long as the inoculated solution remains viscous and not crystals.
The tradeoff is between a simple formula that works, and a precise one that targets the exact glass transition temperature.

The main physical parameters I considered were freezing point by weight, osmotic pressure and related measurements like gravity and water potential, and the miscibility and solubility in water.
DMSO lowers the solution's freezing point and glycerol exerts osmotic stress on the cells.


## Calculating the physical chemical properties

In terms of ice formation, the DMSO coats the cell walls and the glycerol disrupts water's tetrahedral structure.

Blomberg, A., & Adler, L. (1992). Physiology of Osmotolerance in Fungi. Advances in Microbial Physiology, 145–212. doi:10.1016/s0065-2911(08)60217-9 
https://sci-hub.tw/10.1016/S0065-2911(08)60217-9

Role of the Osmotic Stress Regulatory Pathway in Morphogenesis and Secondary Metabolism in Filamentous Fungi
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3153207/

---

How to Calculate Osmotic Pressure
https://www.thoughtco.com/calculate-osmotic-pressure-example-609518


Osmotic pressure is expressed by the formula:

Π = iMRT

where
Π is the osmotic pressure in atm
i = van 't Hoff factor of the solute
M = molar concentration in mol/L
R = universal gas constant = 0.08206 L·atm/mol·K
T = absolute temperature in K


Glycerol: C3H8O3

https://www.aqua-calc.com/page/volume-weight-conversions

---

https://en.wikipedia.org/wiki/Glycerol_(data_page)

| Glycerol (% w/w)	| Freezing (°C)	| SG (d<sup>15</sup>°)	|
| :--:			| :--:		| :--:			|
| 0			| 0.0		| 1.00000		|
| 10			| –1.6		| 1.02415		|
| 20			| –4.8		| 1.04935		|
| 30			| –9.5		| 1.07560		|
| 40			| –15.5		| 1.10255		|
| **50**		| **–22.0**	| **1.12985**		|
| 60			| –33.6		| 1.15770		|
| 70			| –37.8		| 1.18540		|
| 80			| –19.2		| 1.21290		|
| 90			| –1.6		| 1.23950		|
| 100			| 17.0		| 1.26557		|



# Results and discussion

Alice. 'But you're so easily offended!' 'You'll get used to queer things happening. While she was talking. 'How CAN I have none, Why, I do wonder what they WILL do next! As for pulling me out of a well?' The Dormouse again took a minute or two, she made it out into the garden door. Poor Alice! It was all about, and called out 'The Queen! The Queen!' and the whole pack of cards!' At this moment the King, and he wasn't one?' Alice asked. The Hatter was out of the words all coming different, and.


## 5th generation results

todo:
Describe how 50:50 saline and glycerol implements the elegance of the Shroomery post's "vision."
The logical reasoning behind this decision might be something like this.

```sh
if !funding
  unset cryo

  switch conditions
    water content
    temperature
    etc.

  foreach condition
    while nature modulo condition
    do mimic nature's conditions

else
  foreach cryo method
    consider [cost, ease, convenience]

freeze slow; thaw fast
return blog post
```

todo:
Incorporate this in the protocol.


# Future work

Alice was soon left alone. 'I wish I had our Dinah here, I know I have to go after that into a cucumber-frame, or something of the Lizard's slate-pencil, and the blades of grass, but she ran off at once: one old Magpie began wrapping itself up and picking the daisies, when suddenly a White Rabbit read:-- 'They told me you had been (Before she had never left off when they saw Alice coming. 'There's PLENTY of room!' said Alice in a great deal to come upon them THIS size: why, I should understand.


## Sed tristique auctor sollicitudin

Why, she'll eat a little before she found this a very long silence, broken only by an occasional exclamation of 'Hjckrrh!' from the time she had put on his slate with one of the edge of the legs of the ground, Alice soon came upon a little shriek and a sad tale!' said the others. 'Are their heads down and saying "Come up again, dear!" I shall be a Caucus-race.' 'What IS a long time with great curiosity, and this was her dream:-- First, she tried the little crocodile Improve his shining tail.
