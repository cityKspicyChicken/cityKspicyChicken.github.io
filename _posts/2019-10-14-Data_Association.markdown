---
layout: post
title: "Joint Probabilistic Data Association"
date: 2019-10-14 15:00:00 +0800
categories:Data Association 
tages: ADAS 
description: Algorithm
---
### Data Association - 01 JPDA 

*Definition:*
The *joint probabilistic data-association filter (JPDAF)* is a statistical approach to the problem of plot association(target-measurement assignment) in a target tracking algorithm. Like the probabilistic data association filter (PDAF), rather than choosing the most likely assignment of measurements to a target (or declaring the target not detected or a measurement to be a false alarm), the PDAF takes an expected value, which is the minimum mean square error (MMSE) estimate for the state of each target. At each time, it maintains its estimate of the target state as the mean and covariance matrix of a multivariate normal distribution. However, unlike the PDAF, which is only meant for tracking a single target in the presence of false alarms and missed detections, the JPDAF can handle multiple target tracking scenarios. 
