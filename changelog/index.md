---
title: Change log
---

This page records changes made to instructions or resources.

### Protocol

**2020-05-29: v1**
Initial issue

**2020-06-02: v1.01**
Correct ALMA variables in Table 4: 
- Tveg -> TVeg
- Esoil -> ESoil
- Acond -> ACond

### create_netcdf_EXAMPLE_v1.py

**2020-05-29: v1**
Initial issue

**2020-06-02: v1.01**
Correct RootMoist long_name, standard_name and units

**2020-06-16: v1.02**
Includes x and y spatial dimension for all variables. This aligns with ALMA protocol and will make multi-site phase easier to process.

**2020-06-18: v1.03**
Change time datatype from i8 (64bit) to i4 (32bit) for ncview compatibility, add history

### Experiment script on modelevaluation.org

**2020-05-29: v1**
Initial issue, check critical variables only

**2020-05-29: v2**
check all requested variables


