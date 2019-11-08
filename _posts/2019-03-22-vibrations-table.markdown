---
title: Vibrations Table
layout: post
date:  2018-10-01
daterange: November 2018 - December 2018
project: true
categories: []
tags: [NX, MATLAB]
excerpt: "Demonstration table for structual dynamics and application of a tuned mass damper"
---
## draft

During my Vibrations and Aeroelasticity course another student and I volunteered to work on designing (and possibly building) a  demonstration table that our professor could use to demonstrate the effects of resonance within structures and how a tuned mass damper works to reduce vibrations on a structure. 

Given only a rough project description we set a few constraints:
- Must weight less than 10 lbs
- The structue must have a low fundamental frequency (0.5-2 Hz) and be large enough to visibly see from far away
- Be powered off of a battery
- The center of mass of the pendulum had to be easily tunable
- Cost less than $1,000 to purcahse all the parts

The design we came up with was a tall metal structure, bolted to a moving table mounted with linear bearings on rails. To move the table a motor would be attatched via rods, the motors speed would be controlled by an arduino with a motor shield.  The entire design could be mostly made out of scap materials found in the manufacturing building, only requiring the purchase of a motor, rails and linear bearings.

<figure class="half">
    <a href="/portfolio/Vibes_Table/AlumESSAY_fem3.png"><img src="/portfolio/Vibes_Table/AlumESSAY_fem3.png"></a>
    <a href="/portfolio/Vibes_Table/render.png"><img src="/portfolio/Vibes_Table/render.png"></a>
    <figcaption>Design Parameters for Vibration table demonstrator</figcaption>
</figure>

Using the NASTRAN solver in Siemens NX to calculate the modal frequencies of the tower we determined the tower by itself would have a modal frequency of 13 Hz, but the tower was designed with a space to easily add mass to the top of the structure to decrease the first fundamental frequency.  To tune the frequency of the pendulum washers mounted on a bolt would swing, and the height of the stack of washers could easily be changed by turning the nyloc nut holding the washers up.

Unfortunately due to budgets and schedules the materials were never purchased and the design was never built and tested.  However this small project turned out to be a way to learn more about finite element modelling and use the NASTRAN solver built into Siemens NX.