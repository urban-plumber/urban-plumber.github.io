# AU-Preston: CM-BEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |     MAE |       MBE |      NSD |        R |
|:-------|:-------------|--------:|----------:|---------:|---------:|
| SWnet  | baseline     | 80.2654 |  -6.23773 | 0.877193 | 0.913098 |
| SWnet  | detailed     | 79.4669 |  -3.23525 | 0.883192 | 0.914998 |
| LWnet  | baseline     | 17.0533 |  -2.18544 | 1.19662  | 0.918179 |
| LWnet  | detailed     | 14.2488 |   3.81659 | 1.08754  | 0.933659 |
| Qle    | baseline     | 27.8082 | -14.5935  | 0.625117 | 0.594866 |
| Qle    | detailed     | 24.1384 |  -8.64399 | 0.640403 | 0.644817 |
| Qh     | baseline     | 34.9618 |  18.3685  | 0.831494 | 0.892799 |
| Qh     | detailed     | 30.5154 |  18.0798  | 1.02748  | 0.909328 |

 - MAE: mean absolute error (close to 0 is better)
 - NME: absolute mean error normalised by difference from mean  (closer to 0 is better)
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
[![CM-BEM_AU-Preston_Albedo.png](CM-BEM_AU-Preston_Albedo.png)](CM-BEM_AU-Preston_Albedo.png)

### <a name="lwnet"></a>LWnet
[![CM-BEM_AU-Preston_LWnet.png](CM-BEM_AU-Preston_LWnet.png)](CM-BEM_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![CM-BEM_AU-Preston_LWup.png](CM-BEM_AU-Preston_LWup.png)](CM-BEM_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![CM-BEM_AU-Preston_Qh.png](CM-BEM_AU-Preston_Qh.png)](CM-BEM_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![CM-BEM_AU-Preston_Qle.png](CM-BEM_AU-Preston_Qle.png)](CM-BEM_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![CM-BEM_AU-Preston_SWnet.png](CM-BEM_AU-Preston_SWnet.png)](CM-BEM_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![CM-BEM_AU-Preston_SWnet_subset_baseline.png](CM-BEM_AU-Preston_SWnet_subset_baseline.png)](CM-BEM_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![CM-BEM_AU-Preston_SWnet_subset_detailed.png](CM-BEM_AU-Preston_SWnet_subset_detailed.png)](CM-BEM_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![CM-BEM_AU-Preston_SWup.png](CM-BEM_AU-Preston_SWup.png)](CM-BEM_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![CM-BEM_AU-Preston_SWup_subset_baseline.png](CM-BEM_AU-Preston_SWup_subset_baseline.png)](CM-BEM_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![CM-BEM_AU-Preston_SWup_subset_detailed.png](CM-BEM_AU-Preston_SWup_subset_detailed.png)](CM-BEM_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![CM-BEM_AU-Preston_closure_baseline.png](CM-BEM_AU-Preston_closure_baseline.png)](CM-BEM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![CM-BEM_AU-Preston_closure_detailed.png](CM-BEM_AU-Preston_closure_detailed.png)](CM-BEM_AU-Preston_closure_detailed.png)

### out of range: baseline

 - CM-BEM SWnet min value of -34.4363 is less than expected 0.0 [W/m2]
 - CM-BEM SWup min value of -590.9081 is less than expected 0.0 [W/m2]
 - CM-BEM Qanth_Qle min value of -1.9800 is less than expected 0.0 [W/m2]
 - CM-BEM alb min value of -0.9980 is less than expected 0.0 [1]

### out of range: detailed

 - CM-BEM SWnet min value of -29.6650 is less than expected 0.0 [W/m2]
 - CM-BEM SWup min value of -591.9839 is less than expected 0.0 [W/m2]
 - CM-BEM Qanth_Qle min value of -1.8900 is less than expected 0.0 [W/m2]
 - CM-BEM alb min value of -0.9985 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

