# AU-Preston: JULES_1T

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](JULES_1T_AU-Preston_baseline_attrs.md)
- [Detailed](JULES_1T_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |         MBE |      nSD |        R |         5th |       95th |      RMSE |    cRMSE |       AMBE |     1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|------------:|---------:|---------:|------------:|-----------:|----------:|---------:|-----------:|----------:|-----------:|------------:|------------:|----------:|
| SWup   | G11          |  4.20392  |   3.32715   | 1.07444  | 0.996804 |  0.4523     | 11.0958    |  6.16226  | 0.111397 |  3.32715   | 0.0744357 | 0.0031964  |   0.0162302 |   0.0325821 | 0.078131  |
| SWup   | baseline     | 12.8117   |  12.5544    | 1.24511  | 0.996798 |  0.258405   | 36.081     | 17.4739   | 0.260865 | 12.5544    | 0.245109  | 0.00320151 |   0.0135131 |   0.0252988 | 0.0905484 |
| SWup   | detailed     |  6.16191  |   5.63221   | 1.11713  | 0.996798 |  0.410686   | 17.3643    |  8.77689  | 0.144477 |  5.63221   | 0.117134  | 0.00320151 |   0.0135131 |   0.0252988 | 0.0843946 |
| LWup   | G11          | 15.6559   |  13.1096    | 1.37855  | 0.970251 |  0.243685   | 53.8544    | 23.8653   | 0.474681 | 13.1096    | 0.378553  | 0.0297487  |   0.182294  |   0.322585  | 0.0846454 |
| LWup   | baseline     | 11.7198   |  10.1429    | 1.09744  | 0.96966  |  5.92341    | 20.8761    | 15.405    | 0.275842 | 10.1429    | 0.0974412 | 0.0303405  |   0.028316  |   0.0128278 | 0.107588  |
| LWup   | detailed     | 13.4023   |  11.797     | 1.12468  | 0.960162 |  6.06177    | 24.8875    | 18.0267   | 0.324276 | 11.797     | 0.124679  | 0.039838   |   0.018708  |   0.0797417 | 0.115222  |
| Qle    | G11          | 20.5598   |  -6.43062   | 0.671255 | 0.689622 |  9.9425     | 37.4548    | 35.9787   | 0.724403 |  6.43062   | 0.328745  | 0.310378   |   0.059558  |   0.147549  | 0.194453  |
| Qle    | baseline     | 21.5421   | -10.4382    | 0.56014  | 0.710432 | 10.6271     | 46.6276    | 36.674    | 0.719635 | 10.4382    | 0.43986   | 0.289568   |   0.0409412 |   0.330383  | 0.229694  |
| Qle    | detailed     | 19.9993   |   3.10072   | 0.923471 | 0.745995 | 10.8382     | 10.36      | 33.8125   | 0.689194 |  3.10072   | 0.0765292 | 0.254005   |   0.108252  |   0.681008  | 0.214673  |
| Qh     | G11          | 23.5019   |  -1.0529    | 1.21235  | 0.946801 | 16.848      | 52.8654    | 38.2564   | 0.417234 |  1.0529    | 0.212349  | 0.0531992  |   0.0411946 |   0.0249098 | 0.165231  |
| Qh     | baseline     | 25.7291   |   0.943039  | 1.04079  | 0.90176  |  8.58729    |  5.16103   | 41.6133   | 0.454046 |  0.943039  | 0.0407897 | 0.0982397  |   0.0491746 |   0.183372  | 0.10031   |
| Qh     | detailed     | 29.4422   |  -9.99294   | 0.83905  | 0.858936 |  8.64363    | 55.6104    | 48.0072   | 0.512469 |  9.99294   | 0.16095   | 0.141064   |   0.0532736 |   0.374642  | 0.125696  |
| Qtau   | G11          |  0.108846 |   0.0456966 | 1.02043  | 0.869941 |  0.0043     |  0.0306    |  0.166293 | 0.515606 |  0.0456966 | 0.0204323 | 0.130059   |   0.228935  |   0.409606  | 0.0992274 |
| Qtau   | baseline     |  0.181613 |   0.151326  | 1.28927  | 0.859409 |  0.0110121  |  0.303494  |  0.256331 | 0.667979 |  0.151326  | 0.289271  | 0.140591   |   0.20645   |   0.353416  | 0.198512  |
| Qtau   | detailed     |  0.125539 |   0.0656333 | 1.03223  | 0.855805 |  0.00907779 |  0.0597523 |  0.181565 | 0.546556 |  0.0656333 | 0.0322253 | 0.144195   |   0.18819   |   0.317138  | 0.13101   |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![JULES_1T_AU-Preston_Albedo.png](JULES_1T_AU-Preston_Albedo.png)](JULES_1T_AU-Preston_Albedo.png)

### <a name="datasheet"></a>Datasheet
[![JULES_1T_AU-Preston_Datasheet.png](JULES_1T_AU-Preston_Datasheet.png)](JULES_1T_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![JULES_1T_AU-Preston_Distributions.png](JULES_1T_AU-Preston_Distributions.png)](JULES_1T_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![JULES_1T_AU-Preston_closure_baseline.png](JULES_1T_AU-Preston_closure_baseline.png)](JULES_1T_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![JULES_1T_AU-Preston_closure_detailed.png](JULES_1T_AU-Preston_closure_detailed.png)](JULES_1T_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![JULES_1T_AU-Preston_subset_Qh.png](JULES_1T_AU-Preston_subset_Qh.png)](JULES_1T_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![JULES_1T_AU-Preston_subset_Qle.png](JULES_1T_AU-Preston_subset_Qle.png)](JULES_1T_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![JULES_1T_AU-Preston_subset_SWup.png](JULES_1T_AU-Preston_subset_SWup.png)](JULES_1T_AU-Preston_subset_SWup.png)

### out of range: baseline

 - JULES_1T Qh max value of 617.2024 is greater than expected 600.0 [W/m2]

### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

