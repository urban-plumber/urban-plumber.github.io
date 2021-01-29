# AU-Preston: TEB-READING

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |   MAE |     MBE |    NSD |      R |
|:-------|:-------------|------:|--------:|-------:|-------:|
| SWnet  | baseline     | 17.42 |  15.262 | 0.9136 | 0.9985 |
| SWnet  | detailed     |  9.73 |   2.205 | 0.8727 | 0.9985 |
| LWnet  | baseline     | 17.07 | -16.673 | 1.2036 | 0.9629 |
| LWnet  | detailed     | 12.49 |  -7.867 | 1.0892 | 0.9592 |
| Qle    | baseline     | 24.74 |  -0.424 | 0.8361 | 0.6311 |
| Qle    | detailed     | 27.86 |   5.24  | 1.0831 | 0.642  |
| Qh     | baseline     | 62.79 |  61.64  | 1.2141 | 0.9327 |
| Qh     | detailed     | 35.25 |  31.477 | 1.1873 | 0.9401 |

MAE = mean absolute error, MBE = mean bias error, NSD = ratio of model:obs standard deviation, R = Pearson's correlation

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

[Link to variable definitions](variable_definitions.md)

### <a name="lwnet"></a>LWnet
[![TEB-READING_AU-Preston_LWnet.png](TEB-READING_AU-Preston_LWnet.png)](TEB-READING_AU-Preston_LWnet.png)

### <a name="lwup"></a>LWup
[![TEB-READING_AU-Preston_LWup.png](TEB-READING_AU-Preston_LWup.png)](TEB-READING_AU-Preston_LWup.png)

### <a name="qh"></a>Qh
[![TEB-READING_AU-Preston_Qh.png](TEB-READING_AU-Preston_Qh.png)](TEB-READING_AU-Preston_Qh.png)

### <a name="qle"></a>Qle
[![TEB-READING_AU-Preston_Qle.png](TEB-READING_AU-Preston_Qle.png)](TEB-READING_AU-Preston_Qle.png)

### <a name="swnet"></a>SWnet
[![TEB-READING_AU-Preston_SWnet.png](TEB-READING_AU-Preston_SWnet.png)](TEB-READING_AU-Preston_SWnet.png)

### <a name="swnet_subset_baseline"></a>SWnet_subset_baseline
[![TEB-READING_AU-Preston_SWnet_subset_baseline.png](TEB-READING_AU-Preston_SWnet_subset_baseline.png)](TEB-READING_AU-Preston_SWnet_subset_baseline.png)

### <a name="swnet_subset_detailed"></a>SWnet_subset_detailed
[![TEB-READING_AU-Preston_SWnet_subset_detailed.png](TEB-READING_AU-Preston_SWnet_subset_detailed.png)](TEB-READING_AU-Preston_SWnet_subset_detailed.png)

### <a name="swup"></a>SWup
[![TEB-READING_AU-Preston_SWup.png](TEB-READING_AU-Preston_SWup.png)](TEB-READING_AU-Preston_SWup.png)

### <a name="swup_subset_baseline"></a>SWup_subset_baseline
[![TEB-READING_AU-Preston_SWup_subset_baseline.png](TEB-READING_AU-Preston_SWup_subset_baseline.png)](TEB-READING_AU-Preston_SWup_subset_baseline.png)

### <a name="swup_subset_detailed"></a>SWup_subset_detailed
[![TEB-READING_AU-Preston_SWup_subset_detailed.png](TEB-READING_AU-Preston_SWup_subset_detailed.png)](TEB-READING_AU-Preston_SWup_subset_detailed.png)

### <a name="closure_baseline"></a>closure_baseline
[![TEB-READING_AU-Preston_closure_baseline.png](TEB-READING_AU-Preston_closure_baseline.png)](TEB-READING_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![TEB-READING_AU-Preston_closure_detailed.png](TEB-READING_AU-Preston_closure_detailed.png)](TEB-READING_AU-Preston_closure_detailed.png)

### out of range: baseline

 - TEB-READING SWup min value of -446.8446 is less than expected 0.0 [W/m2]
 - TEB-READING RoofSurfT max value of 348.9096 is greater than expected 343.0 [K]
 - TEB-READING alb min value of -0.9960 is less than expected 0.0 [1]

### out of range: detailed

 - TEB-READING SWup min value of -416.7891 is less than expected 0.0 [W/m2]
 - TEB-READING alb min value of -0.9993 is less than expected 0.0 [1]


[Link to variable definitions](variable_definitions.md)

