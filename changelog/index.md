---
title: Change log
---

This page records changes made to instructions or resources.

### Protocol

**v1 (2020-05-29)**
Initial issue

**v1.01 (2020-06-02)**
Correct ALMA variables in Table 4: 
- Tveg -> TVeg
- Esoil -> ESoil
- Acond -> ACond

### create_netcdf_EXAMPLE_v1.py

**v1 (2020-05-29)**
Initial issue

**v1.01 (2020-06-02)**
Correct RootMoist long_name, standard_name and units

**v1.02 (2020-06-16**
Includes x and y spatial dimension for all variables. This aligns with ALMA protocol and will make multi-site phase easier to process.

**v1.03 (2020-06-18)**
Change time datatype from i8 (64bit) to i4 (32bit) for ncview compatibility, add history

### Experiment script on modelevaluation.org

**v1 (2020-05-29)**
Initial issue, check critical variables only

**v2 (2020-06-16)**
check all variables requested in Table 4 of the protocol


