# AU-Preston: CM-BEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |       MBE |      NSD |        R |
|:-------|:-------------|---------:|----------:|---------:|---------:|
| SWnet  | baseline     |  8.99357 |  -5.50367 | 0.86693  | 0.998931 |
| SWnet  | detailed     |  5.6632  |  -2.85067 | 0.873651 | 0.999346 |
| SWup   | baseline     |  8.97902 |   5.48518 | 0.935472 | 0.96543  |
| SWup   | detailed     |  5.66625 |   2.84627 | 0.891637 | 0.977524 |
| LWnet  | baseline     | 13.4941  |  -2.26592 | 1.19602  | 0.952116 |
| LWnet  | detailed     | 12.4213  |  -3.19928 | 1.17497  | 0.958435 |
| LWup   | baseline     | 13.4941  |   2.26592 | 1.24987  | 0.961216 |
| LWup   | detailed     | 12.4213  |   3.19928 | 1.21419  | 0.962722 |
| Qle    | baseline     | 27.6249  | -14.2051  | 0.628255 | 0.596355 |
| Qle    | detailed     | 24.5262  |  -3.16591 | 0.786747 | 0.641364 |
| Qh     | baseline     | 33.7375  |  17.7222  | 0.852569 | 0.895123 |
| Qh     | detailed     | 32.2271  |   6.51606 | 0.759293 | 0.882962 |

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

### <a name="swup"></a>SWup
[![CM-BEM_AU-Preston_SWup.png](CM-BEM_AU-Preston_SWup.png)](CM-BEM_AU-Preston_SWup.png)

### <a name="closure_baseline"></a>closure_baseline
[![CM-BEM_AU-Preston_closure_baseline.png](CM-BEM_AU-Preston_closure_baseline.png)](CM-BEM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![CM-BEM_AU-Preston_closure_detailed.png](CM-BEM_AU-Preston_closure_detailed.png)](CM-BEM_AU-Preston_closure_detailed.png)

### <a name="subset_qg"></a>subset_Qg
[![CM-BEM_AU-Preston_subset_Qg.png](CM-BEM_AU-Preston_subset_Qg.png)](CM-BEM_AU-Preston_subset_Qg.png)

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

