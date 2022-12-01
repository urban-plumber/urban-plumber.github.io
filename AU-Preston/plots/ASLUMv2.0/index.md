# AU-Preston: ASLUMv2.0

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](ASLUMv2.0_AU-Preston_baseline_attrs.md)
- [Detailed](ASLUMv2.0_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |        MBE |        nSD |          R |        5th |      95th |      RMSE |       cRMSE |       AMBE |       1-nSD |          1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|-----------:|-----------:|-----------:|-----------:|----------:|----------:|------------:|-----------:|------------:|-------------:|------------:|------------:|------------:|
| SWup   | baseline     |   7.07367 |   6.47789  |   1.14646  |   0.996798 |   0.431483 |  22.508   |  10.2209  |   0.169685  |   6.47789  |   0.14646   |   0.00320229 |   0.0582332 |   0.122175  |   0.0805525 |
| SWup   | detailed     |   2.90233 |  -0.999638 |   1.01841  |   0.99656  |   0.644255 |   3.55325 |   4.1167  |   0.0857122 |   0.999638 |   0.0184102 |   0.00344048 |   0.0866575 |   0.171671  |   0.0623104 |
| LWup   | baseline     |  10.3639  |   0.253094 |   1.16718  |   0.969079 |   9.46368  |  18.1906  |  13.3029  |   0.316433  |   0.253094 |   0.167178  |   0.0309213  |   0.0406004 |   0.229517  |   0.0991481 |
| LWup   | detailed     |   7.69455 |  -1.72907  |   1.05953  |   0.975839 |   6.95816  |   3.85912 |   9.98529 |   0.233972  |   1.72907  |   0.0595299 |   0.0241612  |   0.0784251 |   0.197506  |   0.0743081 |
| Qle    | baseline     |  22.5174  |   1.72535  |   1.01632  |   0.707193 |  10.4915   |  25.7408  |  37.7376  |   0.771645  |   1.72535  |   0.0163164 |   0.292807   |   0.163784  |   0.304923  |   0.220646  |
| Qle    | detailed     |  25.7254  |  11.915    |   1.24675  |   0.720527 |  10.4915   |  62.9363  |  44.1647  |   0.870489  |  11.915    |   0.246749  |   0.279473   |   0.150434  |   0.299601  |   0.114431  |
| Qh     | baseline     |  19.2647  |  -6.69855  |   0.844545 |   0.945098 |   7.99726  |  39.888   |  32.0358  |   0.341907  |   6.69855  |   0.155455  |   0.0549016  |   0.0607251 |   0.0821599 |   0.147352  |
| Qh     | detailed     |  19.1552  |  -1.68565  |   1.04544  |   0.942992 |   7.74516  |   6.67697 |  31.9511  |   0.348225  |   1.68565  |   0.0454369 |   0.0570078  |   0.0115838 |   0.0568677 |   0.127506  |
| Qtau   | baseline     | nan       | nan        | nan        | nan        | nan        | nan       | nan       | nan         | nan        | nan         | nan          | nan         | nan         | nan         |
| Qtau   | detailed     | nan       | nan        | nan        | nan        | nan        | nan       | nan       | nan         | nan        | nan         | nan          | nan         | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![ASLUMv2.0_AU-Preston_Albedo.png](ASLUMv2.0_AU-Preston_Albedo.png)](ASLUMv2.0_AU-Preston_Albedo.png)

### <a name="datasheet"></a>Datasheet
[![ASLUMv2.0_AU-Preston_Datasheet.png](ASLUMv2.0_AU-Preston_Datasheet.png)](ASLUMv2.0_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![ASLUMv2.0_AU-Preston_Distributions.png](ASLUMv2.0_AU-Preston_Distributions.png)](ASLUMv2.0_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![ASLUMv2.0_AU-Preston_closure_baseline.png](ASLUMv2.0_AU-Preston_closure_baseline.png)](ASLUMv2.0_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![ASLUMv2.0_AU-Preston_closure_detailed.png](ASLUMv2.0_AU-Preston_closure_detailed.png)](ASLUMv2.0_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![ASLUMv2.0_AU-Preston_subset_Qh.png](ASLUMv2.0_AU-Preston_subset_Qh.png)](ASLUMv2.0_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![ASLUMv2.0_AU-Preston_subset_Qle.png](ASLUMv2.0_AU-Preston_subset_Qle.png)](ASLUMv2.0_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![ASLUMv2.0_AU-Preston_subset_SWup.png](ASLUMv2.0_AU-Preston_subset_SWup.png)](ASLUMv2.0_AU-Preston_subset_SWup.png)

### out of range: baseline


### out of range: detailed

 - ASLUMv2.0 Qh max value of 744.3455 is greater than expected 600.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

