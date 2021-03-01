# AU-Preston: NOAH-SLUCM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |       MBE |      NSD |        R |
|:-------|:-------------|---------:|----------:|---------:|---------:|
| SWnet  | baseline     |  9.49879 |  -9.10534 | 0.845039 | 0.999898 |
| SWnet  | detailed     |  3.34888 |  -1.82168 | 0.866917 | 0.999899 |
| SWup   | baseline     |  9.46933 |   9.06654 | 1.04315  | 0.996725 |
| SWup   | detailed     |  3.34542 |   1.80236 | 0.917908 | 0.996648 |
| LWnet  | baseline     | 20.7038  | -20.3205  | 1.18352  | 0.958639 |
| LWnet  | detailed     | 22.8924  | -22.4303  | 1.25275  | 0.949317 |
| LWup   | baseline     | 20.7038  |  20.3205  | 1.29716  | 0.982714 |
| LWup   | detailed     | 22.8924  |  22.4304  | 1.37116  | 0.978412 |
| Qle    | baseline     | 25.8385  | -15.1047  | 0.452126 | 0.583739 |
| Qle    | detailed     | 25.8463  | -15.0832  | 0.453756 | 0.583015 |
| Qh     | baseline     | 20.6156  |   7.58881 | 1.11285  | 0.947624 |
| Qh     | detailed     | 21.0692  |   6.37277 | 1.14277  | 0.948948 |

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
 - [SWup](#swup)
 - [closure_baseline](#closure_baseline)
 - [closure_detailed](#closure_detailed)
 - [subset_Qg](#subset_qg)
 - [subset_Qh](#subset_qh)
 - [subset_Qle](#subset_qle)
 - [subset_SWnet](#subset_swnet)
 - [subset_SWup](#subset_swup)

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

### <a name="swup"></a>SWup
[![NOAH-SLUCM_AU-Preston_SWup.png](NOAH-SLUCM_AU-Preston_SWup.png)](NOAH-SLUCM_AU-Preston_SWup.png)

### <a name="closure_baseline"></a>closure_baseline
[![NOAH-SLUCM_AU-Preston_closure_baseline.png](NOAH-SLUCM_AU-Preston_closure_baseline.png)](NOAH-SLUCM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![NOAH-SLUCM_AU-Preston_closure_detailed.png](NOAH-SLUCM_AU-Preston_closure_detailed.png)](NOAH-SLUCM_AU-Preston_closure_detailed.png)

### <a name="subset_qg"></a>subset_Qg
[![NOAH-SLUCM_AU-Preston_subset_Qg.png](NOAH-SLUCM_AU-Preston_subset_Qg.png)](NOAH-SLUCM_AU-Preston_subset_Qg.png)

### <a name="subset_qh"></a>subset_Qh
[![NOAH-SLUCM_AU-Preston_subset_Qh.png](NOAH-SLUCM_AU-Preston_subset_Qh.png)](NOAH-SLUCM_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![NOAH-SLUCM_AU-Preston_subset_Qle.png](NOAH-SLUCM_AU-Preston_subset_Qle.png)](NOAH-SLUCM_AU-Preston_subset_Qle.png)

### <a name="subset_swnet"></a>subset_SWnet
[![NOAH-SLUCM_AU-Preston_subset_SWnet.png](NOAH-SLUCM_AU-Preston_subset_SWnet.png)](NOAH-SLUCM_AU-Preston_subset_SWnet.png)

### <a name="subset_swup"></a>subset_SWup
[![NOAH-SLUCM_AU-Preston_subset_SWup.png](NOAH-SLUCM_AU-Preston_subset_SWup.png)](NOAH-SLUCM_AU-Preston_subset_SWup.png)

### out of range: baseline

 - NOAH-SLUCM AvgSurfT max value of 370.4353 is greater than expected 333.0 [K]
 - NOAH-SLUCM Qfz min value of -0.0000 is less than expected 0.0 [kg/m2/s]

### out of range: detailed

 - NOAH-SLUCM Qfz min value of -0.0000 is less than expected 0.0 [kg/m2/s]


[Link to variable definitions](../modelattrs/variable_definitions.md)

