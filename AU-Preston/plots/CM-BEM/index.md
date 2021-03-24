# AU-Preston: CM-BEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |       MBE |      NSD |        R |
|:-------|:-------------|---------:|----------:|---------:|---------:|
| SWnet  | baseline     |  8.99959 |  -5.50887 | 0.866923 | 0.998931 |
| SWnet  | detailed     |  5.66462 |  -2.85142 | 0.873644 | 0.999346 |
| SWup   | baseline     |  8.98023 |   5.48721 | 0.935423 | 0.965424 |
| SWup   | detailed     |  5.66482 |   2.84532 | 0.891591 | 0.977534 |
| LWnet  | baseline     | 13.4912  |  -2.27203 | 1.19606  | 0.95216  |
| LWnet  | detailed     | 12.4184  |  -3.20522 | 1.17501  | 0.958474 |
| LWup   | baseline     | 13.4912  |   2.27203 | 1.25018  | 0.961304 |
| LWup   | detailed     | 12.4184  |   3.20522 | 1.2145   | 0.962799 |
| Qle    | baseline     | 27.3048  | -14.1111  | 0.636087 | 0.604318 |
| Qle    | detailed     | 24.2048  |  -3.05408 | 0.796554 | 0.64985  |
| Qh     | baseline     | 33.7031  |  17.6874  | 0.852938 | 0.895228 |
| Qh     | detailed     | 32.198   |   6.47866 | 0.759621 | 0.883006 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)

### jump to figure:
 - [Albedo](#albedo)
 - [LWnet](#lwnet)
 - [LWup](#lwup)
 - [Qanth](#qanth)
 - [Qh](#qh)
 - [Qle](#qle)
 - [SWnet](#swnet)
 - [SWup](#swup)
 - [closure_baseline](#closure_baseline)
 - [closure_detailed](#closure_detailed)
 - [subset_LWnet](#subset_lwnet)
 - [subset_LWup](#subset_lwup)
 - [subset_Qanth](#subset_qanth)
 - [subset_Qh](#subset_qh)
 - [subset_Qle](#subset_qle)
 - [subset_SWnet](#subset_swnet)
 - [subset_SWup](#subset_swup)

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![CM-BEM_AU-Preston_Albedo.png](CM-BEM_AU-Preston_Albedo.png)](CM-BEM_AU-Preston_Albedo.png)

### <a name="lwnet"></a>LWnet
[![CM-BEM_AU-Preston_LWnet.png](CM-BEM_AU-Preston_LWnet.png)](CM-BEM_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![CM-BEM_AU-Preston_LWup.png](CM-BEM_AU-Preston_LWup.png)](CM-BEM_AU-Preston_LWup.png)

### <a name="qanth"></a>Qanth
[![CM-BEM_AU-Preston_Qanth.png](CM-BEM_AU-Preston_Qanth.png)](CM-BEM_AU-Preston_Qanth.png)

### <a name="qh"></a>Qh
[![CM-BEM_AU-Preston_Qh.png](CM-BEM_AU-Preston_Qh.png)](CM-BEM_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![CM-BEM_AU-Preston_Qle.png](CM-BEM_AU-Preston_Qle.png)](CM-BEM_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![CM-BEM_AU-Preston_SWnet.png](CM-BEM_AU-Preston_SWnet.png)](CM-BEM_AU-Preston_SWnet.png)

### <a name="swup"></a>SWup
[![CM-BEM_AU-Preston_SWup.png](CM-BEM_AU-Preston_SWup.png)](CM-BEM_AU-Preston_SWup.png)

### <a name="closure_baseline"></a>closure_baseline
[![CM-BEM_AU-Preston_closure_baseline.png](CM-BEM_AU-Preston_closure_baseline.png)](CM-BEM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![CM-BEM_AU-Preston_closure_detailed.png](CM-BEM_AU-Preston_closure_detailed.png)](CM-BEM_AU-Preston_closure_detailed.png)

### <a name="subset_lwnet"></a>subset_LWnet
[![CM-BEM_AU-Preston_subset_LWnet.png](CM-BEM_AU-Preston_subset_LWnet.png)](CM-BEM_AU-Preston_subset_LWnet.png)

### <a name="subset_lwup"></a>subset_LWup
[![CM-BEM_AU-Preston_subset_LWup.png](CM-BEM_AU-Preston_subset_LWup.png)](CM-BEM_AU-Preston_subset_LWup.png)

### <a name="subset_qanth"></a>subset_Qanth
[![CM-BEM_AU-Preston_subset_Qanth.png](CM-BEM_AU-Preston_subset_Qanth.png)](CM-BEM_AU-Preston_subset_Qanth.png)

### <a name="subset_qh"></a>subset_Qh
[![CM-BEM_AU-Preston_subset_Qh.png](CM-BEM_AU-Preston_subset_Qh.png)](CM-BEM_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![CM-BEM_AU-Preston_subset_Qle.png](CM-BEM_AU-Preston_subset_Qle.png)](CM-BEM_AU-Preston_subset_Qle.png)

### <a name="subset_swnet"></a>subset_SWnet
[![CM-BEM_AU-Preston_subset_SWnet.png](CM-BEM_AU-Preston_subset_SWnet.png)](CM-BEM_AU-Preston_subset_SWnet.png)

### <a name="subset_swup"></a>subset_SWup
[![CM-BEM_AU-Preston_subset_SWup.png](CM-BEM_AU-Preston_subset_SWup.png)](CM-BEM_AU-Preston_subset_SWup.png)

### out of range: baseline

 - CM-BEM SWnet min value of -0.3225 is less than expected 0.0 [W/m2]
 - CM-BEM Qanth_Qle min value of -1.9800 is less than expected 0.0 [W/m2]

### out of range: detailed

 - CM-BEM SWnet min value of -0.2861 is less than expected 0.0 [W/m2]
 - CM-BEM Qanth_Qle min value of -0.5000 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

