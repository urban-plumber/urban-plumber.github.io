# AU-Preston: K-UCMv1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](K-UCMv1_AU-Preston_baseline_attrs.md)
- [Detailed](K-UCMv1_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |        MBE |        nSD |          R |       5th |       95th |      RMSE |      cRMSE |       AMBE |       1-nSD |          1-R |   nSkewness |    nKurtosis |     Overlap |
|:-------|:-------------|----------:|-----------:|-----------:|-----------:|----------:|-----------:|----------:|-----------:|-----------:|------------:|-------------:|------------:|-------------:|------------:|
| SWup   | baseline     |   4.95258 |   0.557459 |   1.03275  |   0.990034 |   0.1906  |   5.6562   |   6.87948 |   0.147169 |   0.557459 |   0.0327539 |   0.00996648 |   0.102441  |   0.235283   |   0.065613  |
| SWup   | detailed     |   7.14691 |  -6.10656  |   0.943582 |   0.987501 |   0.3461  |   5.507    |   9.76745 |   0.163616 |   6.10656  |   0.0564177 |   0.0124989  |   0.298564  |   0.7053     |   0.0865385 |
| LWup   | baseline     |  15.8329  | -13.2712   |   1.14007  |   0.977045 |  18.8155  |   4.12031  |  17.4145  |   0.268252 |  13.2712   |   0.140068  |   0.0229549  |   0.065158  |   0.00876894 |   0.214411  |
| LWup   | detailed     |   7.86139 |  -2.43556  |   1.09421  |   0.980628 |   7.41561 |   8.08271  |   9.82445 |   0.22643  |   2.43556  |   0.0942143 |   0.019372   |   0.0158271 |   0.169445   |   0.093102  |
| Qle    | baseline     |  25.6678  |  12.745    |   0.950316 |   0.698791 |  17.0344  |  24.6955   |  39.1753  |   0.758259 |  12.745    |   0.0496836 |   0.301209   |   0.0388639 |   0.435266   |   0.305828  |
| Qle    | detailed     |  22.4412  |   3.56106  |   0.785201 |   0.694172 |  16.2134  |   0.269899 |  35.6243  |   0.725543 |   3.56106  |   0.214799  |   0.305828   |   0.164829  |   0.28467    |   0.329308  |
| Qh     | baseline     |  27.4417  |   6.47673  |   0.915176 |   0.903844 |   3.5406  |  16.1291   |  39.7485  |   0.428013 |   6.47673  |   0.0848238 |   0.0961564  |   0.046027  |   0.0285114  |   0.221741  |
| Qh     | detailed     |  28.1726  |   0.937871 |   0.78352  |   0.898034 |  10.9006  |  48.9299   |  41.6627  |   0.454586 |   0.937871 |   0.21648   |   0.101966   |   0.0263    |   0.0117709  |   0.239658  |
| Qtau   | baseline     | nan       | nan        | nan        | nan        | nan       | nan        | nan       | nan        | nan        | nan         | nan          | nan         | nan          | nan         |
| Qtau   | detailed     | nan       | nan        | nan        | nan        | nan       | nan        | nan       | nan        | nan        | nan         | nan          | nan         | nan          | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![K-UCMv1_AU-Preston_Albedo.png](K-UCMv1_AU-Preston_Albedo.png)](K-UCMv1_AU-Preston_Albedo.png)

### <a name="datasheet"></a>Datasheet
[![K-UCMv1_AU-Preston_Datasheet.png](K-UCMv1_AU-Preston_Datasheet.png)](K-UCMv1_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![K-UCMv1_AU-Preston_Distributions.png](K-UCMv1_AU-Preston_Distributions.png)](K-UCMv1_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![K-UCMv1_AU-Preston_closure_baseline.png](K-UCMv1_AU-Preston_closure_baseline.png)](K-UCMv1_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![K-UCMv1_AU-Preston_closure_detailed.png](K-UCMv1_AU-Preston_closure_detailed.png)](K-UCMv1_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![K-UCMv1_AU-Preston_subset_Qh.png](K-UCMv1_AU-Preston_subset_Qh.png)](K-UCMv1_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![K-UCMv1_AU-Preston_subset_Qle.png](K-UCMv1_AU-Preston_subset_Qle.png)](K-UCMv1_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![K-UCMv1_AU-Preston_subset_SWup.png](K-UCMv1_AU-Preston_subset_SWup.png)](K-UCMv1_AU-Preston_subset_SWup.png)

### out of range: baseline

 - K-UCMv1 SWnet min value of -13.9929 is less than expected 0.0 [W/m2]

### out of range: detailed

 - K-UCMv1 SWnet min value of -8.7294 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

