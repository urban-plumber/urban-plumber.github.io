# AU-Preston: NOAH-SLUCM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |       MBE |      NSD |        R |      NMAE |
|:-------|:-------------|---------:|----------:|---------:|---------:|----------:|
| SWnet  | baseline     |  9.49667 |  -9.10319 | 0.845026 | 0.999899 | 0.0327104 |
| SWnet  | detailed     |  3.34819 |  -1.82118 | 0.866903 | 0.999899 | 0.0115325 |
| LWnet  | baseline     | 20.7038  | -20.3205  | 1.18352  | 0.958639 | 0.292788  |
| LWnet  | detailed     | 22.8924  | -22.4303  | 1.25275  | 0.949317 | 0.323739  |
| Qle    | baseline     | 25.8385  | -15.1047  | 0.452126 | 0.583739 | 0.782574  |
| Qle    | detailed     | 25.8463  | -15.0832  | 0.453756 | 0.583015 | 0.782809  |
| Qh     | baseline     | 20.6156  |   7.58881 | 1.11285  | 0.947624 | 0.552308  |
| Qh     | detailed     | 21.0692  |   6.37277 | 1.14277  | 0.948948 | 0.56446   |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)

### jump to figure:
 - [Albedo](#albedo)
 - [LWnet](#lwnet)
 - [LWup](#lwup)
 - [Qh](#qh)
 - [Qle](#qle)
 - [SWnet](#swnet)
 - [SWnet_subset_baseline](#swnet_subset_baseline)
 - [SWnet_subset_detailed](#swnet_subset_detailed)
 - [SWup](#swup)
 - [SWup_subset_baseline](#swup_subset_baseline)
 - [SWup_subset_detailed](#swup_subset_detailed)
 - [closure_baseline](#closure_baseline)
 - [closure_detailed](#closure_detailed)

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![NOAH-SLUCM_AU-Preston_Albedo.png](NOAH-SLUCM_AU-Preston_Albedo.png)](NOAH-SLUCM_AU-Preston_Albedo.png)

### <a name="lwnet"></a>LWnet
[![NOAH-SLUCM_AU-Preston_LWnet.png](NOAH-SLUCM_AU-Preston_LWnet.png)](NOAH-SLUCM_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![NOAH-SLUCM_AU-Preston_LWup.png](NOAH-SLUCM_AU-Preston_LWup.png)](NOAH-SLUCM_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![NOAH-SLUCM_AU-Preston_Qh.png](NOAH-SLUCM_AU-Preston_Qh.png)](NOAH-SLUCM_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![NOAH-SLUCM_AU-Preston_Qle.png](NOAH-SLUCM_AU-Preston_Qle.png)](NOAH-SLUCM_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![NOAH-SLUCM_AU-Preston_SWnet.png](NOAH-SLUCM_AU-Preston_SWnet.png)](NOAH-SLUCM_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![NOAH-SLUCM_AU-Preston_SWnet_subset_baseline.png](NOAH-SLUCM_AU-Preston_SWnet_subset_baseline.png)](NOAH-SLUCM_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![NOAH-SLUCM_AU-Preston_SWnet_subset_detailed.png](NOAH-SLUCM_AU-Preston_SWnet_subset_detailed.png)](NOAH-SLUCM_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![NOAH-SLUCM_AU-Preston_SWup.png](NOAH-SLUCM_AU-Preston_SWup.png)](NOAH-SLUCM_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![NOAH-SLUCM_AU-Preston_SWup_subset_baseline.png](NOAH-SLUCM_AU-Preston_SWup_subset_baseline.png)](NOAH-SLUCM_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![NOAH-SLUCM_AU-Preston_SWup_subset_detailed.png](NOAH-SLUCM_AU-Preston_SWup_subset_detailed.png)](NOAH-SLUCM_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![NOAH-SLUCM_AU-Preston_closure_baseline.png](NOAH-SLUCM_AU-Preston_closure_baseline.png)](NOAH-SLUCM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![NOAH-SLUCM_AU-Preston_closure_detailed.png](NOAH-SLUCM_AU-Preston_closure_detailed.png)](NOAH-SLUCM_AU-Preston_closure_detailed.png)

### out of range: baseline

 - NOAH-SLUCM Qsm max value of 103.0613 is greater than expected 0.005 [kg/m2/s]
 - NOAH-SLUCM Qsm min value of -15.2233 is less than expected 0.0 [kg/m2/s]
 - NOAH-SLUCM Qfz min value of -0.0000 is less than expected 0.0 [kg/m2/s]
 - NOAH-SLUCM AvgSurfT max value of 370.4353 is greater than expected 333.0 [K]

### out of range: detailed

 - NOAH-SLUCM Qsm max value of 103.0613 is greater than expected 0.005 [kg/m2/s]
 - NOAH-SLUCM Qsm min value of -15.2233 is less than expected 0.0 [kg/m2/s]
 - NOAH-SLUCM Qfz min value of -0.0000 is less than expected 0.0 [kg/m2/s]


[Link to variable definitions](../modelattrs/variable_definitions.md)

