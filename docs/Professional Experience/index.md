---
title: Professional Experience
layout: default
nav_order: 2
---

- TOC
{:toc}

# Academic Research

I've been involved in computational academic research throughout undergrad. I've been in two research groups and done a few projects with each.
Undergraduate research has taught me to actively and consistently communicate about my work in a rigourous way. My work product had to fit into a larger field, so standards and rigor were paramount. I've also learned more about my own work timeline management. There are no deadlines, but progress must be made, so I've learned to accurately predict the speed of future progress.

## Highlighted Projects

### The Nanorod Walker (March 2024 - January 2025) <br>
This was a project I had complete ownership over during a summer research fellowship. I designed and successfully simulated a walking robot that could move distances thousands of times its body length per second. There were some major challenges not presented in the poster:

Simulation Workspace. I worked hard to convert all my potential computing resources to useful information. The final set up was an array of computers controlled by a central "task assignment" script that optimized simulation efficiency.

Simulation Workflow. Computational Science requires careful forethought to refine questions so that computational resources can inform you efficiently. What do you do while your most insightful simulation is running? You better not be "just waiting." Personally, I found it useful to write down my possible outcomes and plan for each in order of likelihood. That way, I was usually ready to take the next step as I learned my results.

Biology Content Knowledge. Before starting this project, I had not taken a biology course since 2018. To understand the engineering and computational techniques behind this project, I had to read textbooks, papers, and speak to professors about molecular biology and the principles I would need to simulate proteins accurately.

<details markdown="block">
<summary> <b>Poster summarizing the project </b> (It will take ~2 seconds to load.) </summary>
![](/assets/images/poster.jpg)
</details>

### Cylinder-Triangle Intersection (March 2025 - May 2025) <br>
This project was focused on improving a simulation engine that detected intersections between cylinders and triangle in 3D space. My algorithm below improved detection efficiency by over 500% and improved accuracy by 11%.

1. Organize information. Triangles are defined as three points in 3D space (9 Real numbers) and cylinders are defined by a midpoint, radius, length, and an axis (8 Real numbers). Intersections will be detected between the i<sup>th</sup> cylinder and i<sup>th</sup> triangle.
2. Convert triangles to the respective "cylinder frame," a translation from the origin to midpoint of the cylinder and a rotation from the Z axis to the cylinder's axis.
3. Count out triangle edges that don't occupy the cylinder's region along it's axis.
4. Test if remaining edges fall within cylinder radius with axis region.
5. Return positives and negatives.

Designing and implementing this algorithm gave me experience converting abstract geometry into actionable information.
<br> Testing and formatting my implementation this into a larger simulation engine gave me great appreciation for the rigor of academia, and I'd like to take the same validation discipline wherever I go. In fact, I decided to volunteer to validate and create tests for the entire engine as my next project!

### PyElastica Validation Suite (May 2025 - August 2025) <br>

This project is unexciting to most, but it was extremely rewarding to validate 100% of a large, soft-body simulation code base. Using PyTest and mostly common-sense validation, I actually caught two small errors that cancelled each other out during initial testing. They would have broken everything if the default parameters were changed by an end user.

### Sand/Mud/Snow Model (September 2025 - December 2025) <br>

The most fun I've ever had doing research! In PyElastica, my group wanted to implement a bead-based granular media (sand / dirt / gravel) feature.<br> ***That means computing sand with just about every grain.*** <br> My Pi = 10<sup>1/2</sup> physics brain screamed, and I suggested a height-field approximation since all of our expected applications were using the granular media as a ground material, so they made me do it!

My algorithm for time evolution is complicated, so I won't describe it in detail here for now.
Here are some important characteristics that make it fast and accurate:
- Balanced Momentum
- Local (Each column of sand only "feels" the sand directly around it)

## My Takeaways From Research

It would have been impossible to do undergraduate research not refine my technical toolset. I learned some more math, some more physics, a lot of biology, and a lot of p

