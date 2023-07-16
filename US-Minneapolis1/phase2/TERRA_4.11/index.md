# US-Minneapolis1: TERRA_4.11

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TERRA_4.11_US-Minneapolis1_baseline_attrs.md)
- [Detailed](TERRA_4.11_US-Minneapolis1_detailed_attrs.md)

### Error metrics

| flux     | experiment   |       MAE |       MBE |        nSD |          R |        5th |      95th |      RMSE |      cRMSE |      AMBE |        1-nSD |          1-R |   nSkewness |   nKurtosis |     Overlap |
|:---------|:-------------|----------:|----------:|-----------:|-----------:|-----------:|----------:|----------:|-----------:|----------:|-------------:|-------------:|------------:|------------:|------------:|
| SWup     | baseline     |  39.2454  | -35.7754  |   0.720369 |   0.856262 |   1.63762  | 103.326   |  62.8904  |   0.534118 |  35.7754  |   0.279632   |   0.143738   |   0.295028  |    0.668371 |   0.21972   |
| SWup     | detailed     |  28.8119  | -25.4392  |   0.817162 |   0.870754 |   1.48366  |  82.37    |  54.2358  |   0.49463  |  25.4392  |   0.182839   |   0.129246   |   0.244383  |    0.586049 |   0.142     |
| LWup     | baseline     |  10.4556  |  -6.8848  |   0.996108 |   0.985253 |   9.56419  |  14.2636  |  14.2096  |   0.171445 |   6.8848  |   0.00389281 |   0.0147466  |   0.77026   |    0.485359 |   0.0603663 |
| LWup     | detailed     |   8.57535 |   3.2859  |   1.03385  |   0.990305 |   0.240473 |   4.82708 |  11.0545  |   0.145578 |   3.2859  |   0.033851   |   0.00969528 |   0.397894  |    0.453108 |   0.0585134 |
| Qle      | baseline     |  16.7278  |  -2.68824 |   0.911084 |   0.83013  |   3.46557  |   3.04005 |  31.4077  |   0.563416 |   2.68824 |   0.0889155  |   0.16987    |   0.0647792 |    0.345413 |   0.14011   |
| Qle      | detailed     |  18.1929  |  -2.25259 |   0.897306 |   0.813592 |   3.14244  |   6.73041 |  32.704   |   0.587432 |   2.25259 |   0.102694   |   0.186408   |   0.094532  |    0.369011 |   0.131204  |
| Qh       | baseline     |  41.1983  |  27.2995  |   1.10245  |   0.863455 |  38.8301   |  64.0029  |  54.2625  |   0.558177 |  27.2995  |   0.102446   |   0.136545   |   0.353105  |    1.00014  |   0.419826  |
| Qh       | detailed     |  35.3009  |  12.9442  |   1.20777  |   0.850001 |  16.8875   |  73.6463  |  55.0429  |   0.636783 |  12.9442  |   0.207764   |   0.149999   |   0.343421  |    0.887901 |   0.266375  |
| Qg       | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan          | nan          | nan         |  nan        | nan         |
| Qg       | detailed     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan          | nan          | nan         |  nan        | nan         |
| Qtau     | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan          | nan          | nan         |  nan        | nan         |
| Qtau     | detailed     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan          | nan          | nan         |  nan        | nan         |
| SoilTemp | baseline     |   5.66046 |  -3.01462 |   1.35326  |   0.923289 |  10.8965   |   3.47345 |   6.79213 |   0.576555 |   3.01462 |   0.353268   |   0.0767109  |   3.83943   |    0.311025 |   0.286588  |
| SoilTemp | detailed     |   5.49713 |  -3.49708 |   1.3202   |   0.928775 |  11.3255   |   1.8819  |   6.67931 |   0.539062 |   3.49708 |   0.3202     |   0.0712251  |   5.2656    |    0.304218 |   0.285037  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TERRA_4.11_US-Minneapolis1_subset_SWup_v0-9.png](TERRA_4.11_US-Minneapolis1_subset_SWup_v0-9.png)](TERRA_4.11_US-Minneapolis1_subset_SWup_v0-9.png)

### out of range: baseline

 - TERRA_4.11 SWup min value of -0.0002 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.0126 is less than expected 0.0 [1]

### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

