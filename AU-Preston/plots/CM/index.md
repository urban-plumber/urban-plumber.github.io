# AU-Preston: CM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |     MAE |        MBE |      NSD |        R |     NMAE |
|:-------|:-------------|--------:|-----------:|---------:|---------:|---------:|
| SWnet  | baseline     | 68.2468 |  12.2746   | 0.911084 | 0.939294 | 0.23507  |
| SWnet  | detailed     | 68.099  |  11.7452   | 0.90949  | 0.939294 | 0.234561 |
| LWnet  | baseline     | 14.8245 |  -0.149043 | 1.17465  | 0.937762 | 0.209644 |
| LWnet  | detailed     | 21.8253 | -14.757    | 1.40861  | 0.916984 | 0.308647 |
| Qle    | baseline     | 25.0833 |  -8.11643  | 0.674395 | 0.577435 | 0.759701 |
| Qle    | detailed     | 26.6774 |  -7.32488  | 0.829358 | 0.542259 | 0.807983 |
| Qh     | baseline     | 33.1382 |   3.22276  | 0.585435 | 0.917409 | 0.887798 |
| Qh     | detailed     | 32.9066 |  -8.15679  | 0.499936 | 0.917306 | 0.881593 |

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
[![CM_AU-Preston_LWnet.png](CM_AU-Preston_LWnet.png)](CM_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![CM_AU-Preston_LWup.png](CM_AU-Preston_LWup.png)](CM_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![CM_AU-Preston_Qh.png](CM_AU-Preston_Qh.png)](CM_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![CM_AU-Preston_Qle.png](CM_AU-Preston_Qle.png)](CM_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![CM_AU-Preston_SWnet.png](CM_AU-Preston_SWnet.png)](CM_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![CM_AU-Preston_SWnet_subset_baseline.png](CM_AU-Preston_SWnet_subset_baseline.png)](CM_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![CM_AU-Preston_SWnet_subset_detailed.png](CM_AU-Preston_SWnet_subset_detailed.png)](CM_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![CM_AU-Preston_SWup.png](CM_AU-Preston_SWup.png)](CM_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![CM_AU-Preston_SWup_subset_baseline.png](CM_AU-Preston_SWup_subset_baseline.png)](CM_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![CM_AU-Preston_SWup_subset_detailed.png](CM_AU-Preston_SWup_subset_detailed.png)](CM_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![CM_AU-Preston_closure_baseline.png](CM_AU-Preston_closure_baseline.png)](CM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![CM_AU-Preston_closure_detailed.png](CM_AU-Preston_closure_detailed.png)](CM_AU-Preston_closure_detailed.png)

### out of range: baseline

 - CM SWup min value of -527.2600 is less than expected 0.0 [W/m2]
 - CM alb min value of -0.9988 is less than expected 0.0 [1]

### out of range: detailed

 - CM SWup min value of -525.7000 is less than expected 0.0 [W/m2]
 - CM alb min value of -0.9986 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

