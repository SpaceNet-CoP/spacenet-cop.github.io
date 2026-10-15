---
layout: default
title: ISL Constraints
---

<div class="content-container" markdown="1">
<div class="content-block" markdown="1">

# ISL Constraints

</div>
</div>

<div class="content-container" markdown="1">
<div class="content-block" markdown="1">

### Definition

A significant theme in LSN research has been how to leverage the potential of inter-satellite links (ISLs) as an alternative to terrestrial wide-area network infrastructure.
ISLs escape common vulnerabilities of terrestrial fiber-optic infrastructure (e.g., fiber cuts, Earthquakes) and, in the case of free-space optic ISLs, potentially enable faster-than-fiber connectivity over long-distance links.
However, because each ISL transceiver adds to the satellite payload mass, particular satellites will always only be able to form ISLs with a limited number of other satellites.
Moreover, ISLs can only be formed between satellites that are physically visible to each other (e.g., their line-of-sight is not obstructed by the Earth) and take a non-negligible setup time of several seconds, potentially up to 30 seconds, before they can carry network traffic.

</div>
<div class="content-block" markdown="1">

### What happens?

Proposals that require particular satellites to form a large number of ISLs may be infeasible expensive because each ISL not only increases the per-satellite cost, but also all associated launch and maneuver costs due to the increased mass.
Moreover, proposals that assume ISLs can transmit data as soon as two satellites can see each other will face significantly reduced performance in practice.

</div>
<div class="content-block" markdown="1">

### Takeaways

The safest approach is to assume ISLs are static and do not change as satellites proceed through their orbits.
Any proposal that seeks to leverage dynamic ISLs to take advantage of changes in relative position between satellites (e.g., at different latitudes) must carefully account for ISL visibility and setup time latency constraints.

</div>
</div>

<div class="content-container" markdown="1">
<div class="content-block" markdown="1">

[Back](/)

</div>
</div>
