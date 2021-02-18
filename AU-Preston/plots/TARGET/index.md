# AU-Preston: TARGET

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |     MAE |       MBE |      NSD |        R |
|:-------|:-------------|--------:|----------:|---------:|---------:|
| SWnet  | baseline     | 11.5424 | -11.2217  | 0.837595 | 0.99991  |
| SWnet  | detailed     | 11.5424 | -11.2217  | 0.837595 | 0.99991  |
| LWnet  | baseline     | 35.84   | -18.159   | 1.43953  | 0.810365 |
| LWnet  | detailed     | 40.6917 | -25.6682  | 1.51371  | 0.805983 |
| Qle    | baseline     | 32.5916 | -25.0604  | 0.126817 | 0.643414 |
| Qle    | detailed     | 32.3972 | -25.031   | 0.14024  | 0.641874 |
| Qh     | baseline     | 37.8259 |  -6.87361 | 0.885597 | 0.84176  |
| Qh     | detailed     | 38.5538 |  -6.75776 | 0.930376 | 0.841433 |

 - MAE: mean absolute error (close to 0 is better)
 - NME: absolute mean error normalised by difference from mean  (closer to 0 is better)
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
[![TARGET_AU-Preston_LWnet.png](TARGET_AU-Preston_LWnet.png)](TARGET_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![TARGET_AU-Preston_LWup.png](TARGET_AU-Preston_LWup.png)](TARGET_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![TARGET_AU-Preston_Qh.png](TARGET_AU-Preston_Qh.png)](TARGET_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![TARGET_AU-Preston_Qle.png](TARGET_AU-Preston_Qle.png)](TARGET_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![TARGET_AU-Preston_SWnet.png](TARGET_AU-Preston_SWnet.png)](TARGET_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![TARGET_AU-Preston_SWnet_subset_baseline.png](TARGET_AU-Preston_SWnet_subset_baseline.png)](TARGET_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![TARGET_AU-Preston_SWnet_subset_detailed.png](TARGET_AU-Preston_SWnet_subset_detailed.png)](TARGET_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![TARGET_AU-Preston_SWup.png](TARGET_AU-Preston_SWup.png)](TARGET_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![TARGET_AU-Preston_SWup_subset_baseline.png](TARGET_AU-Preston_SWup_subset_baseline.png)](TARGET_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![TARGET_AU-Preston_SWup_subset_detailed.png](TARGET_AU-Preston_SWup_subset_detailed.png)](TARGET_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![TARGET_AU-Preston_closure_baseline.png](TARGET_AU-Preston_closure_baseline.png)](TARGET_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![TARGET_AU-Preston_closure_detailed.png](TARGET_AU-Preston_closure_detailed.png)](TARGET_AU-Preston_closure_detailed.png)

### out of range: baseline

 - TARGET RoofSurfT max value of 358.9660 is greater than expected 353.0 [K]
 - TARGET PSurf min value of 974.2000 is less than expected 5000.0 [Pa]

### out of range: detailed

 - TARGET RoofSurfT max value of 360.3281 is greater than expected 353.0 [K]
 - TARGET PSurf min value of 974.2000 is less than expected 5000.0 [Pa]


[Link to variable definitions](../modelattrs/variable_definitions.md)

