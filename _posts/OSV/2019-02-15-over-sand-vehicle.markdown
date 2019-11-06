---
title: Over Sand Vehicle
layout: post
date:  2016-05-04
daterange: January 2016 - May 2016
project: true
categories: []
tags: [AutoCAD, Fabrication]
excerpt: "fill!!"
comments: false
---
## draft

![OSV](\portfolio\OSV\20160426_114853.jpg)

One of the first required engineering courses at the University of Maryland in College Park is Introduction to Engineering Design otherwise known as ENES 100,  the goal of the class is to teach students the basics of engineering design through the experience of working on a semester long group project.  When I took the class in the Spring of 2016 the project was to create a robot capable of autonomously navigating a sandy course to complete certain mission objectives.  The group I was assigned to was given the mission objective of finding a pool of water in the course; then measuring and transmitting its depth, salinity and taking a water sample.

The group consisted of 8 1st and 2nd year students.  We worked quickly and never hesitated to try out solutions if they might work, by quickly testing things out we became the first group in our class to begin with a working prototype giving us more time to calibrate and work with the robot we had designed.  Within the group I was responsible for designing wheels and the plunger subassembly.  

Having seen previous attempts with 3D printing wheels fail due to sinking and/or lack of grip, I designed deep and large diameter wheels with paddles to help provide traction.  The wheels ended up having no issues moving over the sand and allowed the robot to easily navigate the sand course.

The design of the robot was made to be simple and easy to work with, the frame used was a block of wood that made it easy to mount components to and change, and was cheap enough that it could be easily scrapped if any problem came up.  We used 4 independantly controlled motors to more around, and a servo to control the plunger mechanism.  To determine the location in teh course we used 2 ultrasonic distance sensors to determine distance to the wall to the right and front of the robot.  An Arduino Mega with a motor shield was used to control the entire robot.

The plunger subassemply was powered by a servo mounted to a rack and pinion.  Salinity was measured by determining the resistance across a pair of wires, these wires were also used to determine when the plunger first contacted the water.  A contact switch was used to determine when the plunger had reached the bottom of the pool of water.  By comparing the difference in angles from when the plunger first reached the water to the angle when the contact switch was activated, the depth of water was calculated.  Using this method the depth of the water was measured to within ±1mm.

Teamwork: worked together and actually managed to get shit done on time by just going for it and dealing with the fucking consequences later on which worked out super well for use becasue we basically didn't have to wait around for shit to be designed and could deal with the early issues and solve the problem of making a skookumer design later on.

What the fuck did I do: designed some parts, not super managerial i'm not entierly sure.

End results: we slapped

Click [here](\portfolio\OSV\IMG2673127916211807558.jpg) for the final design presentation