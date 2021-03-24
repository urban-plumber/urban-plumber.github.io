# AU-Preston: ASLUMv3.1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |        MBE |      NSD |        R |
|:-------|:-------------|---------:|-----------:|---------:|---------:|
| SWnet  | baseline     |  3.02626 |   0.576491 | 0.876172 | 0.999878 |
| SWnet  | detailed     |  5.23593 |   3.61087  | 0.881332 | 0.999686 |
| SWup   | baseline     |  3.02879 |  -0.577968 | 0.86509  | 0.995855 |
| SWup   | detailed     |  5.24386 |  -3.61657  | 0.84071  | 0.989358 |
| LWnet  | baseline     |  9.40801 |   3.18348  | 1.02737  | 0.971682 |
| LWnet  | detailed     |  7.17658 |   3.59277  | 0.936608 | 0.980553 |
| LWup   | baseline     |  9.40801 |  -3.18348  | 1.0628   | 0.973292 |
| LWup   | detailed     |  7.17658 |  -3.59277  | 0.938257 | 0.979169 |
| Qle    | baseline     | 25.639   |  -3.87873  | 0.831449 | 0.630058 |
| Qle    | detailed     | 27.2641  |   8.66475  | 1.02334  | 0.660351 |
| Qh     | baseline     | 23.5319  | -13.5878   | 0.755044 | 0.935658 |
| Qh     | detailed     | 21.9695  | -12.1149   | 0.919072 | 0.934107 |

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
[![ASLUMv3.1_AU-Preston_LWnet.png](ASLUMv3.1_AU-Preston_LWnet.png)](ASLUMv3.1_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![ASLUMv3.1_AU-Preston_LWup.png](ASLUMv3.1_AU-Preston_LWup.png)](ASLUMv3.1_AU-Preston_LWup.png)

### <a name="qanth"></a>Qanth
[![ASLUMv3.1_AU-Preston_Qanth.png](ASLUMv3.1_AU-Preston_Qanth.png)](ASLUMv3.1_AU-Preston_Qanth.png)

### <a name="qh"></a>Qh
[![ASLUMv3.1_AU-Preston_Qh.png](ASLUMv3.1_AU-Preston_Qh.png)](ASLUMv3.1_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![ASLUMv3.1_AU-Preston_Qle.png](ASLUMv3.1_AU-Preston_Qle.png)](ASLUMv3.1_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![ASLUMv3.1_AU-Preston_SWnet.png](ASLUMv3.1_AU-Preston_SWnet.png)](ASLUMv3.1_AU-Preston_SWnet.png)

### <a name="swup"></a>SWup
[![ASLUMv3.1_AU-Preston_SWup.png](ASLUMv3.1_AU-Preston_SWup.png)](ASLUMv3.1_AU-Preston_SWup.png)

### <a name="closure_baseline"></a>closure_baseline
[![ASLUMv3.1_AU-Preston_closure_baseline.png](ASLUMv3.1_AU-Preston_closure_baseline.png)](ASLUMv3.1_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![ASLUMv3.1_AU-Preston_closure_detailed.png](ASLUMv3.1_AU-Preston_closure_detailed.png)](ASLUMv3.1_AU-Preston_closure_detailed.png)

### <a name="subset_lwnet"></a>subset_LWnet
[![ASLUMv3.1_AU-Preston_subset_LWnet.png](ASLUMv3.1_AU-Preston_subset_LWnet.png)](ASLUMv3.1_AU-Preston_subset_LWnet.png)

### <a name="subset_lwup"></a>subset_LWup
[![ASLUMv3.1_AU-Preston_subset_LWup.png](ASLUMv3.1_AU-Preston_subset_LWup.png)](ASLUMv3.1_AU-Preston_subset_LWup.png)

### <a name="subset_qanth"></a>subset_Qanth
[![ASLUMv3.1_AU-Preston_subset_Qanth.png](ASLUMv3.1_AU-Preston_subset_Qanth.png)](ASLUMv3.1_AU-Preston_subset_Qanth.png)

### <a name="subset_qh"></a>subset_Qh
[![ASLUMv3.1_AU-Preston_subset_Qh.png](ASLUMv3.1_AU-Preston_subset_Qh.png)](ASLUMv3.1_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![ASLUMv3.1_AU-Preston_subset_Qle.png](ASLUMv3.1_AU-Preston_subset_Qle.png)](ASLUMv3.1_AU-Preston_subset_Qle.png)

### <a name="subset_swnet"></a>subset_SWnet
[![ASLUMv3.1_AU-Preston_subset_SWnet.png](ASLUMv3.1_AU-Preston_subset_SWnet.png)](ASLUMv3.1_AU-Preston_subset_SWnet.png)

### <a name="subset_swup"></a>subset_SWup
[![ASLUMv3.1_AU-Preston_subset_SWup.png](ASLUMv3.1_AU-Preston_subset_SWup.png)](ASLUMv3.1_AU-Preston_subset_SWup.png)

### out of range: baseline


### out of range: detailed

 - ASLUMv3.1 ESoil max value of 0.0003 is greater than expected 0.0003 [kg/m2/s]


[Link to variable definitions](../modelattrs/variable_definitions.md)

