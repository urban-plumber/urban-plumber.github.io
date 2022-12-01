# AU-Preston: BEPCOL

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](BEPCOL_AU-Preston_baseline_attrs.md)
- [Detailed](BEPCOL_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |         MBE |      nSD |        R |        5th |       95th |      RMSE |    cRMSE |       AMBE |     1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|------------:|---------:|---------:|-----------:|-----------:|----------:|---------:|-----------:|----------:|-----------:|------------:|------------:|----------:|
| SWup   | G11          |  8.25845  |   3.01604   | 1.05762  | 0.977094 |  0.019153  |   9.11952  | 11.0153   | 0.227533 |  3.01604   | 0.0576219 | 0.0229056  |   0.0301804 |   0.0874008 | 0.0657742 |
| SWup   | baseline     |  6.12438  |  -5.97668   | 0.881309 | 0.998228 |  0.61      |  17.57     |  8.54885  | 0.131192 |  5.97668   | 0.118691  | 0.00177227 |   0.0808433 |   0.15975   | 0.0800089 |
| SWup   | detailed     |  3.52474  |  -3.17458   | 0.939464 | 0.998196 |  0.56      |   8.94     |  5.03895  | 0.083989 |  3.17458   | 0.0605364 | 0.00180396 |   0.0487501 |   0.0978257 | 0.0722935 |
| LWup   | G11          | 21.8735   |  21.3549    | 1.27324  | 0.954691 | 14.9128    |  53.8677   | 28.1327   | 0.435933 | 21.3549    | 0.273238  | 0.0453093  |   0.221633  |   0.30904   | 0.191607  |
| LWup   | baseline     | 15.477    |  14.9287    | 1.07774  | 0.979985 | 13.68      |  24.89     | 17.6004   | 0.221776 | 14.9287    | 0.0777363 | 0.0200149  |   0.13087   |   0.225667  | 0.183191  |
| LWup   | detailed     | 17.602    |  15.9184    | 1.1548   | 0.966136 | 12.61      |  36.54     | 20.8311   | 0.319647 | 15.9184    | 0.154796  | 0.0338643  |   0.207666  |   0.407375  | 0.175529  |
| Qle    | G11          | 28.1966   | -16.611     | 0.453881 | 0.360641 |  3.54614   |  71.4221   | 48.7246   | 0.937354 | 16.611     | 0.546119  | 0.639359   |   0.129721  |   0.867532  | 0.230268  |
| Qle    | baseline     | 27.6106   | -11.6994    | 0.703408 | 0.434276 |  0.52      |  44.09     | 47.3958   | 0.940126 | 11.6994    | 0.296592  | 0.565724   |   0.0766954 |   1.01179   | 0.135242  |
| Qle    | detailed     | 26.5415   | -14.107     | 0.698676 | 0.521604 |  2.07      |  41.3      | 44.8466   | 0.871369 | 14.107     | 0.301324  | 0.478396   |   0.115997  |   0.412903  | 0.174077  |
| Qh     | G11          | 32.4537   |  13.1684    | 1.10142  | 0.885188 |  5.24645   |  38.6492   | 48.8313   | 0.51303  | 13.1684    | 0.101422  | 0.114812   |   0.0481688 |   0.0923607 | 0.202004  |
| Qh     | baseline     | 35.7887   |  25.6532    | 1.34002  | 0.934239 |  9.17      | 103.27     | 55.7526   | 0.540239 | 25.6532    | 0.340024  | 0.0657607  |   0.0577847 |   0.171416  | 0.289005  |
| Qh     | detailed     | 36.4654   |  30.6323    | 1.17035  | 0.927601 | 27.56      |  73.63     | 51.0363   | 0.445517 | 30.6323    | 0.170355  | 0.0723988  |   0.213931  |   0.532217  | 0.417578  |
| Qtau   | G11          |  0.115236 |  -0.0755248 | 0.561671 | 0.875553 |  0.0119862 |   0.375112 |  0.193968 | 0.576133 |  0.0755248 | 0.438329  | 0.124447   |   0.166728  |   0.295373  | 0.181227  |
| Qtau   | baseline     |  0.529904 |   0.526593  | 1.19513  | 0.796516 |  0.25315   |   0.55623  |  0.572377 | 0.724193 |  0.526593  | 0.195132  | 0.203484   |   0.699043  |   0.935237  | 0.639741  |
| Qtau   | detailed     |  0.436904 |   0.431633  | 1.13362  | 0.808809 |  0.20722   |   0.44139  |  0.479172 | 0.671811 |  0.431633  | 0.133618  | 0.191191   |   0.608449  |   0.854924  | 0.589892  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![BEPCOL_AU-Preston_Albedo.png](BEPCOL_AU-Preston_Albedo.png)](BEPCOL_AU-Preston_Albedo.png)

### <a name="datasheet"></a>Datasheet
[![BEPCOL_AU-Preston_Datasheet.png](BEPCOL_AU-Preston_Datasheet.png)](BEPCOL_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![BEPCOL_AU-Preston_Distributions.png](BEPCOL_AU-Preston_Distributions.png)](BEPCOL_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![BEPCOL_AU-Preston_closure_baseline.png](BEPCOL_AU-Preston_closure_baseline.png)](BEPCOL_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![BEPCOL_AU-Preston_closure_detailed.png](BEPCOL_AU-Preston_closure_detailed.png)](BEPCOL_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![BEPCOL_AU-Preston_subset_Qh.png](BEPCOL_AU-Preston_subset_Qh.png)](BEPCOL_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![BEPCOL_AU-Preston_subset_Qle.png](BEPCOL_AU-Preston_subset_Qle.png)](BEPCOL_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![BEPCOL_AU-Preston_subset_SWup.png](BEPCOL_AU-Preston_subset_SWup.png)](BEPCOL_AU-Preston_subset_SWup.png)

### out of range: baseline

 - BEPCOL Qh max value of 777.1300 is greater than expected 600.0 [W/m2]

### out of range: detailed

 - BEPCOL Qh max value of 726.0000 is greater than expected 600.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

