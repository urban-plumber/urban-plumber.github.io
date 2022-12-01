# AU-Preston: CLMU5

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CLMU5_AU-Preston_baseline_attrs.md)
- [Detailed](CLMU5_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |        MBE |      nSD |        R |         5th |      95th |      RMSE |     cRMSE |       AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|-----------:|---------:|---------:|------------:|----------:|----------:|----------:|-----------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup   | G11          |  2.78087  | -0.234518  | 1.0146   | 0.996759 |  0.79831    |  2.39014  |  3.84382  | 0.0823991 |  0.234518  | 0.0146029  | 0.00324085 |   0.0287102 |   0.0582673 | 0.065477  |
| SWup   | baseline     |  2.98882  |  0.900153  | 1.00594  | 0.996055 |  0.478753   |  0.303116 |  4.25611  | 0.0892825 |  0.900153  | 0.00593605 | 0.00394465 |   0.0862664 |   0.178824  | 0.0687321 |
| SWup   | detailed     |  2.73408  | -0.179863  | 1.01329  | 0.996805 |  0.545667   |  2.26462  |  3.80392  | 0.0815523 |  0.179863  | 0.0132884  | 0.00319465 |   0.026849  |   0.051893  | 0.0630411 |
| LWup   | G11          | 14.8099   | 11.453     | 1.34012  | 0.965663 |  0.364105   | 48.9499   | 22.3111   | 0.455758  | 11.453     | 0.340123   | 0.034337   |   0.17057   |   0.239051  | 0.0756788 |
| LWup   | baseline     | 12.165    |  9.99624   | 1.19395  | 0.971578 |  5.33549    | 34.043    | 16.9204   | 0.324783  |  9.99624   | 0.193946   | 0.0284222  |   0.168029  |   0.191393  | 0.098717  |
| LWup   | detailed     | 12.7726   | 10.7239    | 1.22224  | 0.970236 |  4.52546    | 38.0502   | 18.1885   | 0.349498  | 10.7239    | 0.22224    | 0.0297643  |   0.162468  |   0.167039  | 0.0963169 |
| Qle    | G11          | 24.6929   | -2.94899   | 1.06206  | 0.717595 | 11.8668     | 15.1268   | 38.0835   | 0.776991  |  2.94899   | 0.0620611  | 0.282405   |   0.0605814 |   0.49772   | 0.179543  |
| Qle    | baseline     | 22.9981   | -3.8151    | 0.961195 | 0.706837 |  9.92824    | 11.1521   | 36.9223   | 0.751718  |  3.8151    | 0.0388051  | 0.293163   |   0.222072  |   0.207882  | 0.276339  |
| Qle    | detailed     | 22.6352   | -4.70518   | 0.922227 | 0.706583 |  9.52877    |  6.98892  | 36.4453   | 0.739759  |  4.70518   | 0.0777727  | 0.293417   |   0.172908  |   0.28871   | 0.300761  |
| Qh     | G11          | 24.1072   | -0.0355831 | 1.17937  | 0.950837 | 19.6253     | 41.2659   | 35.2768   | 0.384882  |  0.0355831 | 0.179366   | 0.049163   |   0.0972327 |   0.281432  | 0.219254  |
| Qh     | baseline     | 22.0153   |  4.92345   | 1.09166  | 0.946979 |  6.4021     | 22.3595   | 32.6596   | 0.35237   |  4.92345   | 0.0916602  | 0.0530215  |   0.104176  |   0.280542  | 0.131982  |
| Qh     | detailed     | 20.7623   |  4.6574    | 1.07353  | 0.949941 |  3.60948    | 19.4886   | 31.1353   | 0.335984  |  4.6574    | 0.0735258  | 0.0500589  |   0.0927799 |   0.279398  | 0.131572  |
| Qtau   | G11          |  0.10042  | -0.0526204 | 0.716047 | 0.867109 |  0.0041275  |  0.258664 |  0.169775 | 0.52052   |  0.0526204 | 0.283953   | 0.132891   |   0.253349  |   0.456799  | 0.110394  |
| Qtau   | baseline     |  0.148008 |  0.113241  | 1.14185  | 0.867191 |  0.013265   |  0.174603 |  0.209405 | 0.568697  |  0.113241  | 0.141848   | 0.132809   |   0.223513  |   0.382468  | 0.180886  |
| Qtau   | detailed     |  0.101659 |  0.0108203 | 0.838804 | 0.86662  |  0.00810055 |  0.11455  |  0.155165 | 0.499743  |  0.0108203 | 0.161196   | 0.13338    |   0.231101  |   0.405479  | 0.111969  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![CLMU5_AU-Preston_Albedo.png](CLMU5_AU-Preston_Albedo.png)](CLMU5_AU-Preston_Albedo.png)

### <a name="datasheet"></a>Datasheet
[![CLMU5_AU-Preston_Datasheet.png](CLMU5_AU-Preston_Datasheet.png)](CLMU5_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![CLMU5_AU-Preston_Distributions.png](CLMU5_AU-Preston_Distributions.png)](CLMU5_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![CLMU5_AU-Preston_closure_baseline.png](CLMU5_AU-Preston_closure_baseline.png)](CLMU5_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![CLMU5_AU-Preston_closure_detailed.png](CLMU5_AU-Preston_closure_detailed.png)](CLMU5_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![CLMU5_AU-Preston_subset_Qh.png](CLMU5_AU-Preston_subset_Qh.png)](CLMU5_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![CLMU5_AU-Preston_subset_Qle.png](CLMU5_AU-Preston_subset_Qle.png)](CLMU5_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![CLMU5_AU-Preston_subset_SWup.png](CLMU5_AU-Preston_subset_SWup.png)](CLMU5_AU-Preston_subset_SWup.png)

### out of range: baseline


### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

