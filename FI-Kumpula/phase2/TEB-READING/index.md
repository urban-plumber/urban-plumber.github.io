# FI-Kumpula: TEB-READING

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TEB-READING_FI-Kumpula_baseline_attrs.md)
- [Detailed](TEB-READING_FI-Kumpula_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |      MBE |      nSD |        R |        5th |     95th |    RMSE |    cRMSE |     AMBE |     1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|---------:|---------:|---------:|-----------:|---------:|--------:|---------:|---------:|----------:|----------:|------------:|------------:|----------:|
| SWup   | baseline     | 11.1303  | -8.13696 | 0.818293 | 0.939342 |  0.0851065 | 20.0972  | 18.6206 | 0.363717 |  8.13696 | 0.181717  | 0.0606581 |  0.137822   |   0.390322  | 0.108581  |
| SWup   | detailed     | 10.471   | -4.59454 | 0.904253 | 0.922033 |  0.0999017 |  3.3672  | 18.4266 | 0.387519 |  4.59454 | 0.0957581 | 0.0779669 |  0.214351   |   0.620762  | 0.0934472 |
| LWup   | baseline     |  7.65248 |  6.43265 | 1.09944  | 0.989555 |  6.64564   | 24.8971  | 11.5197 | 0.181262 |  6.43265 | 0.0994388 | 0.010445  |  2.62045    |   0.391855  | 0.074624  |
| LWup   | detailed     |  7.37449 |  5.46536 | 1.10683  | 0.989696 |  5.5176    | 24.5231  | 11.18   | 0.184993 |  5.46536 | 0.10683   | 0.0103037 |  2.59598    |   0.309078  | 0.077318  |
| Qle    | baseline     | 14.8502  | -8.72093 | 0.707309 | 0.752507 |  5.01659   | 31.1204  | 26.4587 | 0.660133 |  8.72093 | 0.29269   | 0.247493  |  0.09444    |   0.0803059 | 0.291621  |
| Qle    | detailed     | 15.6727  | -2.46304 | 1.01292  | 0.745148 |  5.05718   |  9.93141 | 27.3058 | 0.718649 |  2.46304 | 0.0129211 | 0.254852  |  0.0818395  |   0.323609  | 0.279793  |
| Qh     | baseline     | 32.4317  | 22.985   | 0.771354 | 0.822927 | 36.9316    |  8.03373 | 40.7999 | 0.570483 | 22.985   | 0.228647  | 0.177073  |  0.00427961 |   0.0792391 | 0.493531  |
| Qh     | detailed     | 23.2172  |  1.37053 | 0.671886 | 0.818847 | 26.5403    | 43.7796  | 35.0387 | 0.592526 |  1.37053 | 0.328115  | 0.181153  |  0.152821   |   0.162331  | 0.335816  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TEB-READING_FI-Kumpula_subset_SWup_v0-9.png](TEB-READING_FI-Kumpula_subset_SWup_v0-9.png)](TEB-READING_FI-Kumpula_subset_SWup_v0-9.png)

### out of range: baseline

 - TEB-READING Qanth min value of -1.2932 is less than expected 0.0 [W/m2]

### out of range: detailed

 - TEB-READING Qanth min value of -6.3880 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

