# AU-Preston: JULES_2T

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |       MBE |      NSD |        R |
|:-------|:-------------|---------:|----------:|---------:|---------:|
| SWnet  | baseline     | 11.7951  | -11.4818  | 0.836894 | 0.999915 |
| SWnet  | detailed     |  5.64829 |  -5.12229 | 0.856445 | 0.999915 |
| SWup   | baseline     | 11.7455  |  11.4291  | 1.08934  | 0.997179 |
| SWup   | detailed     |  5.6298  |   5.09296 | 0.977375 | 0.997179 |
| LWnet  | baseline     | 10.877   |  -9.64212 | 1.04882  | 0.978397 |
| LWnet  | detailed     | 14.9451  | -10.4523  | 1.18925  | 0.953101 |
| LWup   | baseline     | 10.877   |   9.64212 | 1.08881  | 0.980983 |
| LWup   | detailed     | 14.9451  |  10.4523  | 1.26052  | 0.965005 |
| Qle    | baseline     | 23.5403  | -11.761   | 0.529498 | 0.65858  |
| Qle    | detailed     | 22.1159  |   1.50517 | 0.815044 | 0.676896 |
| Qh     | baseline     | 23.4145  |   2.87694 | 1.08288  | 0.919828 |
| Qh     | detailed     | 21.5228  |  -6.36902 | 1.01617  | 0.928969 |

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
 - [subset_Qtau](#subset_qtau)
 - [subset_SWnet](#subset_swnet)
 - [subset_SWup](#subset_swup)

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![JULES_2T_AU-Preston_Albedo.png](JULES_2T_AU-Preston_Albedo.png)](JULES_2T_AU-Preston_Albedo.png)

### <a name="lwnet"></a>LWnet
[![JULES_2T_AU-Preston_LWnet.png](JULES_2T_AU-Preston_LWnet.png)](JULES_2T_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![JULES_2T_AU-Preston_LWup.png](JULES_2T_AU-Preston_LWup.png)](JULES_2T_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![JULES_2T_AU-Preston_Qh.png](JULES_2T_AU-Preston_Qh.png)](JULES_2T_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![JULES_2T_AU-Preston_Qle.png](JULES_2T_AU-Preston_Qle.png)](JULES_2T_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![JULES_2T_AU-Preston_SWnet.png](JULES_2T_AU-Preston_SWnet.png)](JULES_2T_AU-Preston_SWnet.png)

### <a name="swup"></a>SWup
[![JULES_2T_AU-Preston_SWup.png](JULES_2T_AU-Preston_SWup.png)](JULES_2T_AU-Preston_SWup.png)

### <a name="closure_baseline"></a>closure_baseline
[![JULES_2T_AU-Preston_closure_baseline.png](JULES_2T_AU-Preston_closure_baseline.png)](JULES_2T_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![JULES_2T_AU-Preston_closure_detailed.png](JULES_2T_AU-Preston_closure_detailed.png)](JULES_2T_AU-Preston_closure_detailed.png)

### <a name="subset_qg"></a>subset_Qg
[![JULES_2T_AU-Preston_subset_Qg.png](JULES_2T_AU-Preston_subset_Qg.png)](JULES_2T_AU-Preston_subset_Qg.png)

### <a name="subset_qh"></a>subset_Qh
[![JULES_2T_AU-Preston_subset_Qh.png](JULES_2T_AU-Preston_subset_Qh.png)](JULES_2T_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![JULES_2T_AU-Preston_subset_Qle.png](JULES_2T_AU-Preston_subset_Qle.png)](JULES_2T_AU-Preston_subset_Qle.png)

### <a name="subset_qtau"></a>subset_Qtau
[![JULES_2T_AU-Preston_subset_Qtau.png](JULES_2T_AU-Preston_subset_Qtau.png)](JULES_2T_AU-Preston_subset_Qtau.png)

### <a name="subset_swnet"></a>subset_SWnet
[![JULES_2T_AU-Preston_subset_SWnet.png](JULES_2T_AU-Preston_subset_SWnet.png)](JULES_2T_AU-Preston_subset_SWnet.png)

### <a name="subset_swup"></a>subset_SWup
[![JULES_2T_AU-Preston_subset_SWup.png](JULES_2T_AU-Preston_subset_SWup.png)](JULES_2T_AU-Preston_subset_SWup.png)

### out of range: baseline

 - JULES_2T SnowFrac min value of -0.0000 is less than expected 0.0 [1]
 - JULES_2T SWE min value of -0.0000 is less than expected 0.0 [kg/m2]

### out of range: detailed

 - JULES_2T SnowFrac min value of -0.0000 is less than expected 0.0 [1]
 - JULES_2T SWE min value of -0.0000 is less than expected 0.0 [kg/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

