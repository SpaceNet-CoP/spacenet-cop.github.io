---
layout: default
title: Home
---

Low-Earth orbit (LEO) satellite networks (LSNs) have emerged as a major focus of networking research.
However, unlike traditional networking research, most LSN research cannot be validated against accessible real-world infrastructure.
Due to this, researchers rely heavily on simulation frameworks and implicit modeling assumptions.
This creates a inherent **risk that proposed systems may satisfy networking objectives but violate constraints from orbital dynamics or space-environment realities**, leading to results that are physically infeasible or operationally irrelevant.

**The goal of this website is to establish a community-of-practice initiative to help ground LSN research in the realities of orbital mechanics and space physics.**
Concretely, we establish the following principles that LSN research should strive to abide by---regardless of what assumptions or simulations are utilized---in order to maintain alignment with realities of space operations.

This website is open-source and we encourage you to add your perspective and expertise by submitting [pull requests](https://github.com/SpaceNet-CoP/spacenet-cop.github.io/pulls) and [issues](https://github.com/SpaceNet-CoP/spacenet-cop.github.io/issues) or by joining discussion on existing threads.
Something important the community is missing? Submit a pr!
Something this website gets totally (or just slightly) wrong? Submit an issue!

# The Principles

[**Avoiding Collisions**](principles/collisions.html)
<br/>
We should be sure satellites in the same constellation will not collide with each other.

[**Near-Earth Hazards**](principles/hazards.html)
<br/>
LSN designs should account for the structure of near-Earth hazards like the Van Allen radiation belts.

[**Satellite Power Dynamics**](principles/power.html)
<br/>
LSN designs should account for power dynamics such as passages through Earth's shadow and expected battery lifetimes.

[**ISL Constraints**](principles/isls.html)
<br/>
Proposed use of inter-satellite links (ISLs) should leverage link setup time constraints.

[**Incremental Deployment**](principles/deployment.html)
<br/>
LSN operations should account for costs and constraints of incrementally launching new constellations.

[**Orbital Dynamics**](principles/dynamics.html)
<br/>
We should be sure that satellites are where we want them to be when we want them to be there over the LSN's full lifetime.
