# AU-Preston: NOAH-SLUCM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](NOAH-SLUCM_AU-Preston_baseline_attrs.md)
- [Detailed](NOAH-SLUCM_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |       MBE |      nSD |        R |       5th |     95th |     RMSE |    cRMSE |     AMBE |     1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|----------:|---------:|---------:|----------:|---------:|---------:|---------:|---------:|----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     | 10.0324  |   9.67462 | 1.20249  | 0.996473 |  0.333449 | 30.0588  | 14.1774  | 0.222453 |  9.67462 | 0.202492  | 0.00352686 |   0.0424786 |  0.0749453  | 0.0951892 |
| SWup   | detailed     |  3.52132 |   1.95148 | 1.0594   | 0.996392 |  0.504278 |  9.10053 |  5.29704 | 0.105705 |  1.95148 | 0.0594032 | 0.00360807 |   0.0466485 |  0.0822948  | 0.0691792 |
| LWup   | baseline     | 20.705   |  20.3217  | 1.36091  | 0.982742 |  2.32773  | 55.0061  | 26.9399  | 0.420986 | 20.3217  | 0.360909  | 0.0172582  |   0.0180799 |  0.0697307  | 0.153252  |
| LWup   | detailed     | 22.8938  |  22.4316  | 1.44066  | 0.978449 |  2.26386  | 66.5708  | 30.9108  | 0.506235 | 22.4316  | 0.440659  | 0.0215506  |   0.0631944 |  0.00121101 | 0.152207  |
| Qle    | baseline     | 25.5314  | -15.0382  | 0.464413 | 0.589371 | 10.7136   | 62.8932  | 45.1483  | 0.817469 | 15.0382  | 0.535587  | 0.410629   |   0.0510262 |  0.55588    | 0.239314  |
| Qle    | detailed     | 25.5393  | -15.0168  | 0.465385 | 0.58864  | 10.7134   | 62.8932  | 45.1543  | 0.817738 | 15.0168  | 0.534615  | 0.41136    |   0.0457572 |  0.543723   | 0.240312  |
| Qh     | baseline     | 20.5765  |   7.56441 | 1.11828  | 0.947885 |  4.38525  | 41.893   | 34.0884  | 0.361317 |  7.56441 | 0.118281  | 0.0521155  |   0.0293101 |  0.0360355  | 0.0970975 |
| Qh     | detailed     | 21.0314  |   6.34948 | 1.15005  | 0.949213 |  0.750236 | 48.1393  | 34.9202  | 0.373269 |  6.34948 | 0.150048  | 0.0507873  |   0.0189572 |  0.0693615  | 0.135171  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![NOAH-SLUCM_AU-Preston_Datasheet.png](NOAH-SLUCM_AU-Preston_Datasheet.png)](NOAH-SLUCM_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![NOAH-SLUCM_AU-Preston_Distributions.png](NOAH-SLUCM_AU-Preston_Distributions.png)](NOAH-SLUCM_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![NOAH-SLUCM_AU-Preston_closure_baseline.png](NOAH-SLUCM_AU-Preston_closure_baseline.png)](NOAH-SLUCM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![NOAH-SLUCM_AU-Preston_closure_detailed.png](NOAH-SLUCM_AU-Preston_closure_detailed.png)](NOAH-SLUCM_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![NOAH-SLUCM_AU-Preston_subset_LWup.png](NOAH-SLUCM_AU-Preston_subset_LWup.png)](NOAH-SLUCM_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![NOAH-SLUCM_AU-Preston_subset_Qh.png](NOAH-SLUCM_AU-Preston_subset_Qh.png)](NOAH-SLUCM_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![NOAH-SLUCM_AU-Preston_subset_Qle.png](NOAH-SLUCM_AU-Preston_subset_Qle.png)](NOAH-SLUCM_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![NOAH-SLUCM_AU-Preston_subset_SWup.png](NOAH-SLUCM_AU-Preston_subset_SWup.png)](NOAH-SLUCM_AU-Preston_subset_SWup.png)

### out of range: baseline

 - NOAH-SLUCM AvgSurfT max value of 370.4353 is greater than expected 333.0 [K]
 - NOAH-SLUCM Qfz min value of -0.0000 is less than expected 0.0 [kg/m2/s]
 - NOAH-SLUCM EvapF max value of 8.9437 is greater than expected 1.0 [1]
 - NOAH-SLUCM EvapF min value of -726.1538 is less than expected 0.0 [1]

### out of range: detailed

 - NOAH-SLUCM Qfz min value of -0.0000 is less than expected 0.0 [kg/m2/s]
 - NOAH-SLUCM EvapF max value of 23.3003 is greater than expected 1.0 [1]
 - NOAH-SLUCM EvapF min value of -66.9352 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

