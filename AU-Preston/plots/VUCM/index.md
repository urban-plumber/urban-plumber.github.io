# AU-Preston: VUCM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |        MBE |      NSD |        R |
|:-------|:-------------|---------:|-----------:|---------:|---------:|
| SWnet  | baseline     |  5.56336 |   5.27575  | 0.890191 | 0.999897 |
| SWnet  | detailed     |  3.25157 |   1.72425  | 0.879923 | 0.999892 |
| SWup   | baseline     |  5.55657 |  -5.26949  | 0.784851 | 0.996321 |
| SWup   | detailed     |  3.25061 |  -1.72688  | 0.843778 | 0.996275 |
| LWnet  | baseline     |  7.95236 |   0.255234 | 0.878841 | 0.977267 |
| LWnet  | detailed     | 14.4833  |  12.9604   | 0.87532  | 0.962424 |
| LWup   | baseline     |  7.94685 |  -0.249221 | 0.825996 | 0.980059 |
| LWup   | detailed     | 14.4782  | -12.9552   | 0.80113  | 0.965787 |
| Qle    | baseline     | 30.0776  |   2.05436  | 0.824714 | 0.482468 |
| Qle    | detailed     | 30.265   |   1.68286  | 0.824737 | 0.470606 |
| Qh     | baseline     | 27.5478  |   8.10283  | 1.01307  | 0.906859 |
| Qh     | detailed     | 26.1149  |   8.94299  | 0.988445 | 0.914428 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)

### jump to figure:
 - [LWnet](#lwnet)
 - [LWup](#lwup)
 - [Qh](#qh)
 - [Qle](#qle)
 - [SWnet](#swnet)
 - [SWup](#swup)
 - [closure_baseline](#closure_baseline)
 - [closure_detailed](#closure_detailed)
 - [subset_Qh](#subset_qh)
 - [subset_Qle](#subset_qle)
 - [subset_SWnet](#subset_swnet)
 - [subset_SWup](#subset_swup)

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="lwnet"></a>LWnet
[![VUCM_AU-Preston_LWnet.png](VUCM_AU-Preston_LWnet.png)](VUCM_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![VUCM_AU-Preston_LWup.png](VUCM_AU-Preston_LWup.png)](VUCM_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![VUCM_AU-Preston_Qh.png](VUCM_AU-Preston_Qh.png)](VUCM_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![VUCM_AU-Preston_Qle.png](VUCM_AU-Preston_Qle.png)](VUCM_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![VUCM_AU-Preston_SWnet.png](VUCM_AU-Preston_SWnet.png)](VUCM_AU-Preston_SWnet.png)

### <a name="swup"></a>SWup
[![VUCM_AU-Preston_SWup.png](VUCM_AU-Preston_SWup.png)](VUCM_AU-Preston_SWup.png)

### <a name="closure_baseline"></a>closure_baseline
[![VUCM_AU-Preston_closure_baseline.png](VUCM_AU-Preston_closure_baseline.png)](VUCM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![VUCM_AU-Preston_closure_detailed.png](VUCM_AU-Preston_closure_detailed.png)](VUCM_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![VUCM_AU-Preston_subset_Qh.png](VUCM_AU-Preston_subset_Qh.png)](VUCM_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![VUCM_AU-Preston_subset_Qle.png](VUCM_AU-Preston_subset_Qle.png)](VUCM_AU-Preston_subset_Qle.png)

### <a name="subset_swnet"></a>subset_SWnet
[![VUCM_AU-Preston_subset_SWnet.png](VUCM_AU-Preston_subset_SWnet.png)](VUCM_AU-Preston_subset_SWnet.png)

### <a name="subset_swup"></a>subset_SWup
[![VUCM_AU-Preston_subset_SWup.png](VUCM_AU-Preston_subset_SWup.png)](VUCM_AU-Preston_subset_SWup.png)

### out of range: baseline

 - VUCM Qh max value of 606.7470 is greater than expected 600.0 [W/m2]
 - VUCM SWup min value of -0.3180 is less than expected 0.0 [W/m2]

### out of range: detailed

 - VUCM SWup min value of -0.3140 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

