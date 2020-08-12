---
title: Q&A
---

## Questions and Answers

This page records questions or clarifications for the project. 


### Site data parameters

> **Q:** what is "**footpath_area_fraction**" (site parameter 12)

**A:** footpath_area_fraction could have been better named as “paved_area_fraction” or similar, as it is intended to include paths, courts, plazas, parking areas and any other hard ground covering.

---

> **Q:** what is "**impervious_area_fraction**" (site parameter 5)

**A:** impervious_area_fraction is the total area of urban “hard surfaces”. roof + road + footpaths = impervious_area_fraction

---

> **Q:** For models without explicit urban representation, what should "**impervious_area_fraction**" be?

**A:** Use whatever land type the model would normally apply to urban land points in a typical regional simulation (some use bare soil, some use grassland etc.). In the "detailed" experiment, surface albedo could be altered to match more closely with "average_albedo_at_midday".

---

> **Q:** What type of tree is "**tree_area_fraction**"? 

**A:** *Baseline*: Use default tree type, or plant functional type (PFT) for that geographic location (if your modelling system has that capability). 
*Detailed*: Use tree type(s) you think best represents the location.

---

> **Q:** What are the assumptions I should use for the **baseline**?

**A:** Where parameters are not provided in the baseline case (e.g. building height), models should use their default values, or values which modellers believe represent a generic, or average urban surface. These default values will be used in all baseline cases in the multi-site stage.

---

### Spinup

> **Q:** Is **spinup** compulsory?

**A:** The protocol recommends 10yr spinup to allow model soil state to equilibrate with local climate conditions, however this may not be a) useful or b) feasible for some models. If this is the case you may choose a reduced spinup. The submission checking system (on modelevaluation.org) will still expect a netCDF over the full forcing period (spinup + analysis, so for Preston starting 1993-01-01). If some/all spinup is not undertaken, submitted file should still begin at start of forcing, with non-simulated intervals being filled with the missing_float value (set as -9999. in the provided script). This will satisfy the automatic check on submission, and will record for us whether models undertook spinup. The primary analysis will still begin at “time_analysis_start” (2003-08-12 for Preston).

---

> **Q:** Should automatic (repeating) **spinup** be used?

**A:** No. Spinup and analysis periods should be run together without repetition.

---

