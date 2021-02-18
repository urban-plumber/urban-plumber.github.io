# AU-Preston: VUCM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |       MBE |      NSD |        R |      NMAE |
|:-------|:-------------|---------:|----------:|---------:|---------:|----------:|
| SWnet  | baseline     |  5.56216 |  5.27462  | 0.890177 | 0.999897 | 0.0191584 |
| SWnet  | detailed     |  3.2509  |  1.72392  | 0.879909 | 0.999892 | 0.0111974 |
| LWnet  | baseline     |  7.95236 |  0.255234 | 0.878841 | 0.977267 | 0.11246   |
| LWnet  | detailed     | 14.4833  | 12.9604   | 0.87532  | 0.962424 | 0.204819  |
| Qle    | baseline     | 30.0776  |  2.05436  | 0.824714 | 0.482468 | 0.910963  |
| Qle    | detailed     | 30.265   |  1.68286  | 0.824737 | 0.470606 | 0.916642  |
| Qh     | baseline     | 27.5478  |  8.10283  | 1.01307  | 0.906859 | 0.738027  |
| Qh     | detailed     | 26.1149  |  8.94299  | 0.988445 | 0.914428 | 0.699638  |

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
[![VUCM_AU-Preston_LWnet.png](VUCM_AU-Preston_LWnet.png)](VUCM_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![VUCM_AU-Preston_LWup.png](VUCM_AU-Preston_LWup.png)](VUCM_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![VUCM_AU-Preston_Qh.png](VUCM_AU-Preston_Qh.png)](VUCM_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![VUCM_AU-Preston_Qle.png](VUCM_AU-Preston_Qle.png)](VUCM_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![VUCM_AU-Preston_SWnet.png](VUCM_AU-Preston_SWnet.png)](VUCM_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![VUCM_AU-Preston_SWnet_subset_baseline.png](VUCM_AU-Preston_SWnet_subset_baseline.png)](VUCM_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![VUCM_AU-Preston_SWnet_subset_detailed.png](VUCM_AU-Preston_SWnet_subset_detailed.png)](VUCM_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![VUCM_AU-Preston_SWup.png](VUCM_AU-Preston_SWup.png)](VUCM_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![VUCM_AU-Preston_SWup_subset_baseline.png](VUCM_AU-Preston_SWup_subset_baseline.png)](VUCM_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![VUCM_AU-Preston_SWup_subset_detailed.png](VUCM_AU-Preston_SWup_subset_detailed.png)](VUCM_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![VUCM_AU-Preston_closure_baseline.png](VUCM_AU-Preston_closure_baseline.png)](VUCM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![VUCM_AU-Preston_closure_detailed.png](VUCM_AU-Preston_closure_detailed.png)](VUCM_AU-Preston_closure_detailed.png)

### out of range: baseline

 - VUCM Qh max value of 606.7470 is greater than expected 600.0 [W/m2]
 - VUCM SWup min value of -0.3180 is less than expected 0.0 [W/m2]

### out of range: detailed

 - VUCM SWup min value of -0.3140 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

