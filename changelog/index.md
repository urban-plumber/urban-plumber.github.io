---
title: Change log
---

This page records changes made to instructions or resources.

### Protocol

**v1 (2020-05-29)**
Initial issue

**v1.01 (2020-06-02)**
Correct capitalisation of ALMA variables in Table 4:
- Tveg -> TVeg
- Esoil -> ESoil
- Acond -> ACond

**v1.02 (2020-06-27)**
Update acknowledgements, correct registration address.

**v1.03 (2020-09-24)**
- Include project website address in instructions
- Ondicate spinup is not compulsory
- Re-order modelevaluation instructions, indicate benchmarking disabled
- Update acknowledgements

**v1.04 (2020-12-22)**
- Match lat/lon decimal precision in Table 2 and AU-Preston_sitedata_v1.csv 
- Clarify language in section 6.3 for which variables to use in experiments

**v1.05 (2020-12-24)**
- Added to ACond description "*Vegetation canopy*" aerodynamic conductance and updated subgrid in Table 4.
- Changed SoilMoist, SoilTemp, RootMoist & SoilWet subgrids to "soil" from "all".

**v1.06 (2020-12-29)**
- ammended variable names in Table 4 to include (positive [direction]), added SWup/LWup

### create_netcdf_EXAMPLE_v1.py

**v1 (2020-05-29)**
Initial issue

**v1.01 (2020-06-02)**
Correct RootMoist long_name, standard_name and units

**v1.02 (2020-06-16**
Includes x and y spatial dimension for all variables. This aligns with ALMA protocol and will make multi-site phase easier to process.

**v1.03 (2020-06-18)**
Change time datatype from i8 (64bit) to i4 (32bit) for ncview compatibility, add history

**v1.04 (2020-06-19)**
Added x,y dimension variable definitions

**v1.05 (2020-12-22)**
Add compression to example (reduces filesize by 2/3) and SWup/LWup.

**v1.06 (2020-12-22)**
Clarify "positive" upward/downward etc in long_name

### Submission analysis on modelevaluation.org

**v1 (2020-05-29)**
Initial issue, check critical variables only

**v2 (2020-06-16)**
Check all requested variables, add percent "missing"


