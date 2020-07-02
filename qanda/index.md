---
title: Q&A
---

## Questions and Answers

This page records questions or clarifications for the project. 


### Site data parameters

> **Q:** what is "impervious_area_fraction" (site parameter 5)

**A:** impervious_area_fraction is the total area of urban “hard surfaces” i.e (roof + road + footpath) = impervious, and (impervious + tree + grass + bare soil + water) = 1.

> **Q:** For models without urban land types, what should "impervious_area_fraction" be?

**A:** Use whatever land type the model would normally apply to urban land points in a typical regional simulation (some use bare soil, some use grassland etc.). In the "detailed" experiment, change surface albedo so that overall albedo close to "average_albedo_at_midday".

> **Q:** what is "footpath_area_fraction" (site parameter 12)

**A:** footpath_area_fraction is all hard surfaces that are not roads or roofs, e.g. paths, sidewalks, paving etc.

> **Q:** What type of tree is "tree_area_fraction"? 

**A:** *Baseline*: Use default tree type, or plant functional type (PFT) for that geographic location (if your modelling system has that capability). 
*Detailed*: Use tree type(s) you think best represents the location.


### Spinup

> **Q:** Is spinup compulsory?

**A:** No, but highly recommended to allow soil hydrology to reach local conditions based on historical rainfall. If the 10-year spinup is a) not feasible, or b) not useful for your model, you may chose a shorter spinup. The submission checking system (modelevaluation.org) will expect a netcdf over the full simulation period (spinup+analysis). To use that system begin the netcdf at the beginning of "time_coverage_start" and fill with the missing_float (\_FillValue)

> **Q:** Should automatic (repeating) spin up be used?

**A:** No. Spinup and analysis periods should be run together without repetition.

