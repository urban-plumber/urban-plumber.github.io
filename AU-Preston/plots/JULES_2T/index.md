# AU-Preston: JULES_2T

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](JULES_2T_AU-Preston_baseline_attrs.md)
- [Detailed](JULES_2T_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |         MBE |      nSD |        R |          5th |       95th |      RMSE |    cRMSE |       AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|------------:|---------:|---------:|-------------:|-----------:|----------:|---------:|-----------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup   | G11          |  4.20396  |   3.32713   | 1.07444  | 0.996804 |  0.4522      | 11.0959    |  6.1623   | 0.111398 |  3.32713   | 0.0744362  | 0.00319649 |  0.0162307  |  0.0325805  | 0.0780082 |
| SWup   | baseline     | 12.8117   |  12.5544    | 1.24511  | 0.996798 |  0.258405    | 36.081     | 17.4739   | 0.260865 | 12.5544    | 0.245109   | 0.00320151 |  0.0135131  |  0.0252988  | 0.0905484 |
| SWup   | detailed     |  6.16191  |   5.63221   | 1.11713  | 0.996798 |  0.410686    | 17.3643    |  8.77689  | 0.144477 |  5.63221   | 0.117134   | 0.00320151 |  0.0135131  |  0.0252988  | 0.0843946 |
| LWup   | G11          | 15.3537   |  13.009     | 1.35722  | 0.971735 |  0.0169854   | 50.9218    | 23.019    | 0.452028 | 13.009     | 0.357219   | 0.0282649  |  0.146145   |  0.211853   | 0.088003  |
| LWup   | baseline     | 10.8605   |   9.62456   | 1.14222  | 0.981042 |  3.87599     | 24.6671    | 14.314    | 0.252063 |  9.62456   | 0.142222   | 0.018958   |  0.0405326  |  0.00227654 | 0.0925883 |
| LWup   | detailed     | 14.8769   |  10.3944    | 1.32266  | 0.964996 |  2.04021     | 44.8431    | 21.3447   | 0.443517 | 10.3944    | 0.322661   | 0.0350042  |  0.111665   |  0.0953477  | 0.0870497 |
| Qle    | G11          | 20.5977   |  -6.42689   | 0.669826 | 0.689523 |  9.2568      | 37.3379    | 35.9843   | 0.724532 |  6.42689   | 0.330174   | 0.310477   |  0.0463191  |  0.177377   | 0.210157  |
| Qle    | baseline     | 21.4422   | -10.4162    | 0.56634  | 0.711097 | 10.4052      | 46.1628    | 36.5838   | 0.717841 | 10.4162    | 0.43366    | 0.288903   |  0.0419888  |  0.323122   | 0.257425  |
| Qle    | detailed     | 20.1111   |   2.77718   | 0.936171 | 0.743759 |  9.70925     | 10.8248    | 34.0958   | 0.695589 |  2.77718   | 0.0638294  | 0.256241   |  0.122754   |  0.696014   | 0.191262  |
| Qh     | G11          | 21.4388   |  -0.425775  | 1.18565  | 0.953425 | 15.034       | 46.7642    | 34.8931   | 0.380668 |  0.425775  | 0.185649   | 0.0465749  |  0.0185361  |  0.0362094  | 0.145592  |
| Qh     | baseline     | 21.8139   |   1.34475   | 1.08938  | 0.932447 | 10.8492      | 17.3221    | 36.1183   | 0.393918 |  1.34475   | 0.0893809  | 0.0675532  |  0.0250396  |  0.0732313  | 0.0765481 |
| Qh     | detailed     | 19.9172   |  -8.71517   | 1.0012   | 0.944831 | 17.1028      | 14.3031    | 31.6766   | 0.332373 |  8.71517   | 0.00120164 | 0.0551687  |  0.00517232 |  0.0385489  | 0.102228  |
| Qtau   | G11          |  0.106743 |   0.0448502 | 1.01827  | 0.872054 |  0.0002      |  0.0309    |  0.164622 | 0.510783 |  0.0448502 | 0.0182666  | 0.127946   |  0.221512   |  0.400749   | 0.0949631 |
| Qtau   | baseline     |  0.174036 |   0.144466  | 1.30036  | 0.864589 |  0.00855345  |  0.300265  |  0.251615 | 0.665116 |  0.144466  | 0.300357   | 0.135411   |  0.208708   |  0.365067   | 0.185593  |
| Qtau   | detailed     |  0.111315 |   0.0499339 | 1.05839  | 0.867377 |  0.000441444 |  0.0585278 |  0.17249  | 0.53305  |  0.0499339 | 0.0583871  | 0.132623   |  0.200406   |  0.356055   | 0.0923341 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![JULES_2T_AU-Preston_Albedo.png](JULES_2T_AU-Preston_Albedo.png)](JULES_2T_AU-Preston_Albedo.png)

### <a name="datasheet"></a>Datasheet
[![JULES_2T_AU-Preston_Datasheet.png](JULES_2T_AU-Preston_Datasheet.png)](JULES_2T_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![JULES_2T_AU-Preston_Distributions.png](JULES_2T_AU-Preston_Distributions.png)](JULES_2T_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![JULES_2T_AU-Preston_closure_baseline.png](JULES_2T_AU-Preston_closure_baseline.png)](JULES_2T_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![JULES_2T_AU-Preston_closure_detailed.png](JULES_2T_AU-Preston_closure_detailed.png)](JULES_2T_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![JULES_2T_AU-Preston_subset_Qh.png](JULES_2T_AU-Preston_subset_Qh.png)](JULES_2T_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![JULES_2T_AU-Preston_subset_Qle.png](JULES_2T_AU-Preston_subset_Qle.png)](JULES_2T_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![JULES_2T_AU-Preston_subset_SWup.png](JULES_2T_AU-Preston_subset_SWup.png)](JULES_2T_AU-Preston_subset_SWup.png)

### out of range: baseline


### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

