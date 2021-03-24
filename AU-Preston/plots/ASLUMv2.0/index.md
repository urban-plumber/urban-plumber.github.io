# AU-Preston: ASLUMv2.0

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |       MBE |      NSD |        R |
|:-------|:-------------|---------:|----------:|---------:|---------:|
| SWnet  | baseline     |  6.68976 | -6.06484  | 0.852898 | 0.999908 |
| SWnet  | detailed     |  2.76374 |  0.972939 | 0.873164 | 0.999901 |
| SWup   | baseline     |  6.6712  |  6.0366   | 0.997824 | 0.996944 |
| SWup   | detailed     |  2.76226 | -0.978828 | 0.882102 | 0.996708 |
| LWnet  | baseline     | 10.3597  | -0.269825 | 1.05973  | 0.965073 |
| LWnet  | detailed     |  7.69127 |  1.71425  | 0.976912 | 0.975415 |
| LWup   | baseline     | 10.3597  |  0.269825 | 1.10718  | 0.969018 |
| LWup   | detailed     |  7.69127 | -1.71425  | 1.012    | 0.975802 |
| Qle    | baseline     | 24.5448  |  1.13798  | 0.874753 | 0.658375 |
| Qle    | detailed     | 27.6579  | 11.6081   | 1.05718  | 0.670964 |
| Qh     | baseline     | 20.3974  | -6.70737  | 0.859896 | 0.937881 |
| Qh     | detailed     | 22.086   |  1.23604  | 1.12194  | 0.921621 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)

### jump to figure:
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

### <a name="lwnet"></a>LWnet
[![ASLUMv2.0_AU-Preston_LWnet.png](ASLUMv2.0_AU-Preston_LWnet.png)](ASLUMv2.0_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![ASLUMv2.0_AU-Preston_LWup.png](ASLUMv2.0_AU-Preston_LWup.png)](ASLUMv2.0_AU-Preston_LWup.png)

### <a name="qanth"></a>Qanth
[![ASLUMv2.0_AU-Preston_Qanth.png](ASLUMv2.0_AU-Preston_Qanth.png)](ASLUMv2.0_AU-Preston_Qanth.png)

### <a name="qh"></a>Qh
[![ASLUMv2.0_AU-Preston_Qh.png](ASLUMv2.0_AU-Preston_Qh.png)](ASLUMv2.0_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![ASLUMv2.0_AU-Preston_Qle.png](ASLUMv2.0_AU-Preston_Qle.png)](ASLUMv2.0_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![ASLUMv2.0_AU-Preston_SWnet.png](ASLUMv2.0_AU-Preston_SWnet.png)](ASLUMv2.0_AU-Preston_SWnet.png)

### <a name="swup"></a>SWup
[![ASLUMv2.0_AU-Preston_SWup.png](ASLUMv2.0_AU-Preston_SWup.png)](ASLUMv2.0_AU-Preston_SWup.png)

### <a name="closure_baseline"></a>closure_baseline
[![ASLUMv2.0_AU-Preston_closure_baseline.png](ASLUMv2.0_AU-Preston_closure_baseline.png)](ASLUMv2.0_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![ASLUMv2.0_AU-Preston_closure_detailed.png](ASLUMv2.0_AU-Preston_closure_detailed.png)](ASLUMv2.0_AU-Preston_closure_detailed.png)

### <a name="subset_lwnet"></a>subset_LWnet
[![ASLUMv2.0_AU-Preston_subset_LWnet.png](ASLUMv2.0_AU-Preston_subset_LWnet.png)](ASLUMv2.0_AU-Preston_subset_LWnet.png)

### <a name="subset_lwup"></a>subset_LWup
[![ASLUMv2.0_AU-Preston_subset_LWup.png](ASLUMv2.0_AU-Preston_subset_LWup.png)](ASLUMv2.0_AU-Preston_subset_LWup.png)

### <a name="subset_qanth"></a>subset_Qanth
[![ASLUMv2.0_AU-Preston_subset_Qanth.png](ASLUMv2.0_AU-Preston_subset_Qanth.png)](ASLUMv2.0_AU-Preston_subset_Qanth.png)

### <a name="subset_qh"></a>subset_Qh
[![ASLUMv2.0_AU-Preston_subset_Qh.png](ASLUMv2.0_AU-Preston_subset_Qh.png)](ASLUMv2.0_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![ASLUMv2.0_AU-Preston_subset_Qle.png](ASLUMv2.0_AU-Preston_subset_Qle.png)](ASLUMv2.0_AU-Preston_subset_Qle.png)

### <a name="subset_swnet"></a>subset_SWnet
[![ASLUMv2.0_AU-Preston_subset_SWnet.png](ASLUMv2.0_AU-Preston_subset_SWnet.png)](ASLUMv2.0_AU-Preston_subset_SWnet.png)

### <a name="subset_swup"></a>subset_SWup
[![ASLUMv2.0_AU-Preston_subset_SWup.png](ASLUMv2.0_AU-Preston_subset_SWup.png)](ASLUMv2.0_AU-Preston_subset_SWup.png)

### out of range: baseline


### out of range: detailed

 - ASLUMv2.0 Qh max value of 744.3455 is greater than expected 600.0 [W/m2]
 - ASLUMv2.0 ESoil max value of 0.0003 is greater than expected 0.0003 [kg/m2/s]


[Link to variable definitions](../modelattrs/variable_definitions.md)

