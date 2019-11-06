---
title: Over Sand Vehicle
layout: post
date:  2016-05-04
daterange: January 2016 - May 2016
project: true
categories: []
tags: [AutoCAD, Fabrication]
excerpt: "Autonomous robot built for Intro to Engineering Design Class"
comments: false
---
## draft

![OSV](\portfolio\OSV\20160426_114853.jpg)

One of the first required engineering courses at the University of Maryland in College Park is Introduction to Engineering Design otherwise known as ENES 100,  the goal of the class is to teach students the basics of engineering design through the experience of working on a semester long group project.  When I took the class in the Spring of 2016 the project was to create a robot capable of autonomously navigating a sandy course to complete certain mission objectives.  The group I was assigned to was given the mission objective of finding a pool of water in the course; then measuring and transmitting its depth, salinity and taking a water sample.

The group consisted of 8 freshmen and sophomore engineering students.  We worked quickly and never hesitated to try out solutions if they might work focusing on simple designs that could be quickly made and tested.  This approach allowed us to be the first group in our class to have a working prototype which allowed us more time to calibrate and work with the robot we had designed.  Within the group I was responsible for designing wheels and the plunger subassembly.

![OSV CAD](\portfolio\OSV\OSV4.png)

The robot was designed with simple and cheap parts that would be easy to work with and replace if needed. The frame was made out of a block of wood with holes and screws drilled into it when needed for mounting components. Four motors mounted on the underside of the frame were attatched directly to the wheels, were controlled by a motor shield mounted to an Arduino Mega. Two ultrasonic distance sensors were used to determine the amound of space to the right and front of the robot, these were used in conjunction with the coordination data recieved over the radio from the course itself.  

The plunger subassembly was powered by a servo mounted to a rack and pinion.  Salinity was measured by determining the resistance across a pair of wires, these wires were also used to determine when the plunger first contacted the water.  A contact switch was used to determine when the plunger had reached the bottom of the pool of water.  By comparing the difference in angles from when the plunger first reached the water to the angle when the contact switch was activated, the depth of water was calculated.  Using this method the depth of the water was measured to within ±1mm.

![Plunger Subassembly](\portfolio\OSV\OSV8.png)

Having seen previous attempts with 3D printing wheels fail due to sinking and/or lack of grip, I designed deep and large diameter wheels with paddles to help provide traction.  The wheels ended up having no issues moving over the sand and allowed the robot to easily navigate the sand course.

![At the target](\portfolio\OSV\20160505_105130.jpg)

In the end our team managed to complete all of the the mission objectives when using the coordinates provided by the course, however when the course changed and a different coordination system was provided we ran into trouble during calibration and were unable to complete the course solely relying on our on board distance sensors.

The final design presentation for the Over Sand Vehicle can be found [here.](\portfolio\OSV\IMG2673127916211807558.jpg)