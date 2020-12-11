---
title: "EvoNoodles"
layout: archive-no-title
excerpt: "A natural selection simulator built with Python and PyGame <br/><img src='/images/aapc.png' width='110' height='110'>"
collection: portfolio
---

# EvoNoodles

### View on GitHub &nbsp; <a href="https://github.com/ggdurrant/EvoNoodles"> <img src="https://github.com/favicon.ico" alt="GitHub" width="25"> </a>
------

EvoNoodles is a natural selection simulator that looks at creatures, known as noodles, as they evolve in a competitive environment. which looks at how creatures, known as noodles, evolve their attributes in a competitive environment as they compete for resources. 

## Noodles
Noodles are simple, (mainly) vegetarian creatures which search for food in their nearby enviornment. They attempt to find food at all times to replenish their health, with the goal of reproducing. Food appears regularly in their environment, or at the location of a dead noodle, which they will also eat. 

They have a chance at reproducing after a certain number of timesteps, where they produce a genetically similar offspring that potentially has a mutation in their DNA to differ in a single trait from their parent. 

All noodles start with these attributes, which are random attributes, in the following ranges:
Attribute | Description | Range
-----|-----|-----
Size | size, max health | 6 - 10
Speed | increases velocity | 1 - 4
Sight | range of vision | 30 - 200
View | angle of vision | 40 - 140
Reproduction | % chance of reproducing | 15 - 35

These attributes all contribute to the loss function of a noodle, or how much energy they consume per timestep. The function can be edited to favor attributes over others, but the default function that allows for stable populations is: 
```python
loss = (size**2 + speed**3 + sight/3 + view/2) / 10
```

> loss = size\**3 + speed\**3 + sight

`test code is the fajsdfa sdf asdf`


## Preds
Preds are the predators of the environment, with their prey being the noodles. Preds are also smart creatures, which gives them two distinct advantages: 
 - Preds will chase the closest noodle to them, even if they already locked on another noodle, improving their hunting efficiency
 - Preds will only hunt noodles if their health drops below half, to reduce overeating and wasting resources

Their default starting attributes are also slightly different, with greater size, speed, and range of vision, with a much more narrow vision angle. 


## Summary 

## Simulation
 - To run the simulation simply run main.py
 - There are two settings in main.py, `SIMULATE` and `SAVE`, which can be set to `true`
  - `SIMULATE` will rapidly jump through generations of evolution, speeding up the sim and infrequently redrawing the Pygame window, the console will continue to log the epoch and population to keep track of time
  - `SAVE` will output the creature and attribute statistics in a CSV file, with noodle and pred staistics saved to `data/noodle_output.csv` and `data/pred_output.csv` by default 
 - The starting parameters can be found in sim/settings.py, where starting numbers of noodles, preds, food, as well as width and height for the pygame display and environment size can be edited

## Development

![demo1](/images/demo1.gif)

![demo2](/images/demo2.gif)

![demo3](/images/demo3.gif)

![demo4](/images/demo4.gif)


## Roadmap

## Credit
Written by George Durrant, with insipration from: 
 - Primer Learning: https://www.youtube.com/channel/UCKzJFdi57J53Vr_BkTfN3uQ
 - MinuteLabs.io's expansion on Primer's ideas: https://labs.minutelabs.io/evolution-simulator/#/s/16/about
 - Luke Garbutt's genetic steering algorithm: https://youtu.be/KMeT2k1ytYs?t=15m11s

Also inspired by neutral biodiversity theory and species abundance distributions, specifically from Hubbell, Etienne, and Olff
Relevant Papers:
 - Etienne, R.S. and Olff, H. (2004). A novel genealogical approach to neutral biodiversity theory. Ecology Letters, 7, 170-175.
 - Hubbell, S.P. (2001). The Unified Neutral Theory of Biodiversity and Biogeography. Princeton University Press, Princeton, NJ.