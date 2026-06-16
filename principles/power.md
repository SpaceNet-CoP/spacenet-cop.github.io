---
layout: default
title: Satellite Power Dynamics
---

# Satellite Power Dynamics

### Definition

Satellites are typically equipped with solar panels to power their on-board electronic components (e.g., radio transceivers, network processors, etc.) as well as batteries to smooth over interruptions in solar power supply.
Although satellites at higher altitudes (e.g., GEO) spend the vast majority of their time with ample Sun light, LEO orbits are close enough to the Earth that they regularly pass through the Earth's shadow where little to no Sun light is available.
Accordingly, the batteries on LEO satellites may be exposed to extremely challenging power dynamics over the course of their lifetimes, charging for ~45 minutes when the satellites is in Sun light and discharging for ~45 minutes when the satellite is behind the Earth.

### What happens?

If not carefully managed, this rapid oscillation of charge and discharge quickly degrades battery performance (e.g., Li-ion batteries typically used in satellites only last _O_(1k) charge cycles).
The extreme thermal variation further exacerbates challenges with maintaining battery performance in space.

### Takeaways

LSNs should be careful about the power demands of proposed networking processing and other computational function. Importantly, proposals seeking to offload significant computation to satellite payloads (e.g., CDN and/or AI workloads) must carefully consider the spatiotemporal dynamics of their power requirements.

[Back](/)
