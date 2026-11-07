---
layout: course
title: Robot Modelling, Kinematics and Dynamics
description: A master's course developing robot kinematics and dynamics from first principles, in the modern language of differential geometry.
year: 2025 # only used to order the courses, newest first
term: 2022–2025
location: University of Twente
course_id: robot-modelling-kinematics-dynamics
---

A master's course on robot kinematics and dynamics, which I co-taught at the University of Twente with
[Stefano Stramigioli](https://people.utwente.nl/s.stramigioli?tab=overview) and [Federico Califano](https://people.utwente.nl/f.califano).
Starting from first principles, the course develops the main results of the theory with full conceptual and technical rigour,
using the modern language of differential geometry.

The centrepiece of the course is the [lecture notes](https://github.com/vasilysent/robotics_course/blob/main/notes.pdf).
They are complemented by a practical [assignment](https://github.com/vasilysent/robotics_course/tree/main/Assignment), in which
students complete a Python library for the kinematics and control of serial-chain robots and implement geometric wrench control
for a trajectory-tracking task with a UR5e robot arm simulated in MuJoCo.

Some materials I developped are on GitHub: [vasilysent/robotics_course](https://github.com/vasilysent/robotics_course).

## Course outline

**I. Mathematical Foundations**

1. Sets, Maps and Notation
2. Linear Algebra
3. Groups and Manifolds

**II. Kinematics**

4. Euclidean Spaces and Rigid Motion
5. Rigid Body Velocity
6. Kinematics of Serial Robots
{: start="4"}

**III. Dynamics**

7. Rigid Body Dynamics
8. Dynamics of Serial Robots
{: start="7"}

## Background lecture

A good starting point is the recording of a background lecture on the fundamentals of linear algebra:

<iframe
  src="https://www.youtube-nocookie.com/embed/6FyaBA9BfBE"
  title="Fundamentals of Linear Algebra"
  style="width: 100%; aspect-ratio: 16 / 9; border: 0"
  allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
  allowfullscreen
></iframe>
