# AU-Preston: MUSE

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |       MBE |      NSD |        R |
|:-------|:-------------|---------:|----------:|---------:|---------:|
| SWnet  | baseline     | 18.8962  | -17.5747  | 0.843295 | 0.996354 |
| SWnet  | detailed     | 30.427   | -30.3402  | 0.803356 | 0.996384 |
| SWup   | baseline     | 15.5718  | -15.5716  | 0.613192 | 0.99625  |
| SWup   | detailed     |  3.2249  |  -2.1201  | 0.854583 | 0.996038 |
| LWnet  | baseline     |  9.44332 |   2.65839 | 0.957423 | 0.961202 |
| LWnet  | detailed     |  9.30593 |   4.23136 | 0.920004 | 0.966504 |
| LWup   | baseline     | 26.0854  | -24.6457  | 1.08015  | 0.972177 |
| LWup   | detailed     | 27.0384  | -26.2708  | 1.03807  | 0.975268 |
| Qle    | baseline     | 34.6724  | -28.0481  | 0.503132 | 0.5921   |
| Qle    | detailed     | 35.3962  | -29.2313  | 0.467269 | 0.587874 |
| Qh     | baseline     | 38.1814  |  28.1603  | 1.14194  | 0.897205 |
| Qh     | detailed     | 35.5633  |  24.103   | 1.08673  | 0.897112 |

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
[![MUSE_AU-Preston_LWnet.png](MUSE_AU-Preston_LWnet.png)](MUSE_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![MUSE_AU-Preston_LWup.png](MUSE_AU-Preston_LWup.png)](MUSE_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![MUSE_AU-Preston_Qh.png](MUSE_AU-Preston_Qh.png)](MUSE_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![MUSE_AU-Preston_Qle.png](MUSE_AU-Preston_Qle.png)](MUSE_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![MUSE_AU-Preston_SWnet.png](MUSE_AU-Preston_SWnet.png)](MUSE_AU-Preston_SWnet.png)

### <a name="swup"></a>SWup
[![MUSE_AU-Preston_SWup.png](MUSE_AU-Preston_SWup.png)](MUSE_AU-Preston_SWup.png)

### <a name="closure_baseline"></a>closure_baseline
[![MUSE_AU-Preston_closure_baseline.png](MUSE_AU-Preston_closure_baseline.png)](MUSE_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![MUSE_AU-Preston_closure_detailed.png](MUSE_AU-Preston_closure_detailed.png)](MUSE_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![MUSE_AU-Preston_subset_Qh.png](MUSE_AU-Preston_subset_Qh.png)](MUSE_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![MUSE_AU-Preston_subset_Qle.png](MUSE_AU-Preston_subset_Qle.png)](MUSE_AU-Preston_subset_Qle.png)

### <a name="subset_swnet"></a>subset_SWnet
[![MUSE_AU-Preston_subset_SWnet.png](MUSE_AU-Preston_subset_SWnet.png)](MUSE_AU-Preston_subset_SWnet.png)

### <a name="subset_swup"></a>subset_SWup
[![MUSE_AU-Preston_subset_SWup.png](MUSE_AU-Preston_subset_SWup.png)](MUSE_AU-Preston_subset_SWup.png)

### out of range: baseline

 - MUSE Qh max value of 655.5630 is greater than expected 600.0 [W/m2]

### out of range: detailed

 - MUSE Qh max value of 633.2700 is greater than expected 600.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

