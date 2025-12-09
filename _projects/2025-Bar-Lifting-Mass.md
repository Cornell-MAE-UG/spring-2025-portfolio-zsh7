---
layout: project
title: Actuator Design
description: A frame I designed
technologies:
image: /assets/images/mechanism.jpg
---

Problem Statement: Given a 2D design space of 150cm long and 50cm tall, a rigid bar of a fixed length (your choice), 3 pin supports of which two need to be mounted on the ground and a linear actuator (pick from this online catalog, use max force values only), design a frame/mechanism to lift the maximum possible weight to the highest possible height. Assume all the supports and bar/actuator are rigid.


In 2025, I was tasked with building an actuator that could support a load. I was also informed that it could not deform ~2% of it's length. To solve this problem, I decided to come back to my original design and go from there. My process looked something like this. I stared off by doing a force balance, assuming the actuator was at the end of the rod. From there, I decided to put the weight at the middle of the rod and did my force balance to get the proper values. From there, I decided to take the internal bending moments and solve for everything required. I did this in two places. After doing this, I wanted to create my cross section and did some research into the appexdix in our textbook. I ended up settling on the W150 x 13.5 beam. I then solved for the intertia using the given equations. 

