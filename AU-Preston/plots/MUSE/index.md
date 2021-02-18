# AU-Preston: MUSE

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |       MBE |      NSD |        R |      NMAE |
|:-------|:-------------|---------:|----------:|---------:|---------:|----------:|
| SWnet  | baseline     | 18.8919  | -17.5707  | 0.843282 | 0.996355 | 0.0650716 |
| SWnet  | detailed     | 30.4202  | -30.3334  | 0.803343 | 0.996384 | 0.10478   |
| LWnet  | baseline     |  9.44332 |   2.65839 | 0.957423 | 0.961202 | 0.133545  |
| LWnet  | detailed     |  9.30593 |   4.23136 | 0.920004 | 0.966504 | 0.131602  |
| Qle    | baseline     | 34.6724  | -28.0481  | 0.503132 | 0.5921   | 1.05013   |
| Qle    | detailed     | 35.3962  | -29.2313  | 0.467269 | 0.587874 | 1.07205   |
| Qh     | baseline     | 38.1814  |  28.1603  | 1.14194  | 0.897205 | 1.02291   |
| Qh     | detailed     | 35.5633  |  24.103   | 1.08673  | 0.897112 | 0.952767  |

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
 - [SWnet_subset_baseline](#swnet_subset_baseline)
 - [SWnet_subset_detailed](#swnet_subset_detailed)
 - [SWup](#swup)
 - [SWup_subset_baseline](#swup_subset_baseline)
 - [SWup_subset_detailed](#swup_subset_detailed)
 - [closure_baseline](#closure_baseline)
 - [closure_detailed](#closure_detailed)

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

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![MUSE_AU-Preston_SWnet_subset_baseline.png](MUSE_AU-Preston_SWnet_subset_baseline.png)](MUSE_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![MUSE_AU-Preston_SWnet_subset_detailed.png](MUSE_AU-Preston_SWnet_subset_detailed.png)](MUSE_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![MUSE_AU-Preston_SWup.png](MUSE_AU-Preston_SWup.png)](MUSE_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![MUSE_AU-Preston_SWup_subset_baseline.png](MUSE_AU-Preston_SWup_subset_baseline.png)](MUSE_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![MUSE_AU-Preston_SWup_subset_detailed.png](MUSE_AU-Preston_SWup_subset_detailed.png)](MUSE_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![MUSE_AU-Preston_closure_baseline.png](MUSE_AU-Preston_closure_baseline.png)](MUSE_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![MUSE_AU-Preston_closure_detailed.png](MUSE_AU-Preston_closure_detailed.png)](MUSE_AU-Preston_closure_detailed.png)

### out of range: baseline

 - MUSE Qh max value of 655.5630 is greater than expected 600.0 [W/m2]

### out of range: detailed

 - MUSE Qh max value of 633.2700 is greater than expected 600.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

