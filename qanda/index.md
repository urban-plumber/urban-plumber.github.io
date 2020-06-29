---
title: Q&A
---

## Questions and Answers

This page records questions or clarifications for the project. 

1. **Q:** Should automatic spin up be used?
   **A:** No. Spinup and analysis periods should be run together without repetition.

2. **Q:** What type of tree is "tree_area_fraction"? 
   **A:** *Baseline*: Use default tree type, or plant functional type (PFT) for that geographic location (if your modelling system has that capability). 
   *Detailed*: Use tree type(s) you think best represents the location.

3. **Q:** For models without urban land types, what should "impervious_area_fraction" be?
   **A:** Use whatever land type the model would normally apply to urban land points in a typical regional simulation (some use bare soil, some use grassland etc.). In the "detailed" experiment, change surface albedo so that overall albedo close to "average_albedo_at_midday".

