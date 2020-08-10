---
title: Q&A
---

## Questions and Answers

This page records questions or clarifications for the project. 


### Site data parameters

> **Q:** what is "**impervious_area_fraction**" (site parameter 5)

**A:** impervious_area_fraction is the total area of urban “hard surfaces” i.e (roof + road + footpath) = impervious_area_fraction

---

> **Q:** what is "**footpath_area_fraction**" (site parameter 12)

**A:** footpath_area_fraction is all hard surfaces that are not roads or roofs, e.g. paths, sidewalks, paving etc.

---

> **Q:** What type of tree is "**tree_area_fraction**"? 

**A:** *Baseline*: Use default tree type, or plant functional type (PFT) for that geographic location (if your modelling system has that capability). 
*Detailed*: Use tree type(s) you think best represents the location.

---

> **Q:** What are the assumptions I should use for the **baseline**?

**A:** Where parameters are not provided in the baseline case (e.g. building height), models should use their default values, or values which modellers believe represent a generic, or average urban surface. These default values will be used in all baseline cases in the multi-site stage.

---

> **Q:** For models without explicit urban representation, what should "**impervious_area_fraction**" be?

**A:** Use whatever land type the model would normally apply to urban land points in a typical regional simulation (some use bare soil, some use grassland etc.). In the "detailed" experiment, surface albedo could be altered to match more closely with "average_albedo_at_midday".

---

### Spinup

> **Q:** Is **spinup** compulsory?

**A:** No, but highly recommended to allow soil hydrology to reach local conditions based on historical rainfall. If the 10-year spinup is a) not feasible, or b) not useful for your model, you may choose a shorter spinup. The submission checking system (modelevaluation.org) will expect a netCDF over the full simulation period (spinup+analysis). To use that system begin the netCDF at the beginning of "time_coverage_start" and fill with the missing float value (\_FillValue or missing_value in netCDF).

---

> **Q:** Should automatic (repeating) **spinup** be used?

**A:** No. Spinup and analysis periods should be run together without repetition.

---

