# US-Minneapolis2: Ensemble

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](Ensemble_US-Minneapolis2_baseline_attrs.md)
- [Detailed](Ensemble_US-Minneapolis2_detailed_attrs.md)

### Error metrics

| flux     | experiment   |       MAE |         MBE |      nSD |        R |         5th |       95th |      RMSE |    cRMSE |       AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:---------|:-------------|----------:|------------:|---------:|---------:|------------:|-----------:|----------:|---------:|-----------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup     | baseline     | 40.3729   | -39.9023    | 0.504814 | 0.83995  |  1.49493    | 157.992    | 73.533    | 0.637809 | 39.9023    | 0.495187   | 0.16005    |    0.639106 |    1.11339  | 0.154728  |
| SWup     | detailed     | 36.8494   | -36.3104    | 0.535652 | 0.833802 |  1.34467    | 147.944    | 70.7827   | 0.627429 | 36.3104    | 0.464349   | 0.166198   |    0.644698 |    1.12488  | 0.1303    |
| LWup     | baseline     |  7.93824  |   5.523     | 0.990061 | 0.992571 |  9.52858    |   3.79885  | 10.4094   | 0.121696 |  5.523     | 0.00993972 | 0.00742942 |    0.138806 |    0.361929 | 0.0639413 |
| LWup     | detailed     |  6.64487  |   1.85616   | 0.992615 | 0.99264  |  5.53828    |   0.367841 |  8.97461  | 0.121106 |  1.85616   | 0.00738591 | 0.00736038 |    0.14543  |    0.386289 | 0.0524564 |
| Qle      | baseline     | 20.7373   |   5.73777   | 1.00298  | 0.889977 |  3.8853     |  10.8774   | 36.6696   | 0.469796 |  5.73777   | 0.00297534 | 0.110023   |    0.143618 |    0.474175 | 0.109451  |
| Qle      | detailed     | 20.2884   |   2.63542   | 0.920707 | 0.888194 |  3.92372    |   8.61596  | 35.608    | 0.460618 |  2.63542   | 0.0792934  | 0.111806   |    0.18913  |    0.557995 | 0.111268  |
| Qh       | baseline     | 27.8736   |  20.3349    | 1.07997  | 0.875694 | 19.7464     |  37.9714   | 38.9667   | 0.524299 | 20.3349    | 0.0799746  | 0.124306   |    0.119327 |    0.485434 | 0.239442  |
| Qh       | detailed     | 20.776    |   8.75086   | 1.01056  | 0.881345 | 14.3586     |  19.1095   | 32.2637   | 0.489824 |  8.75086   | 0.0105597  | 0.118655   |    0.177831 |    0.381785 | 0.146157  |
| Qg       | baseline     | 24.6819   |   0.768456  | 1.25184  | 0.770555 | 13.9416     |  10.9396   | 35.6693   | 0.798671 |  0.768456  | 0.251827   | 0.229445   |    0.404404 |    0.826683 | 0.232263  |
| Qg       | detailed     | 26.0147   |   0.978001  | 1.26303  | 0.752274 | 15.1434     |  10.9289   | 37.2353   | 0.83364  |  0.978001  | 0.263023   | 0.247726   |    0.432432 |    0.87568  | 0.240425  |
| Qtau     | baseline     |  0.10858  |  -0.0919214 | 0.504376 | 0.891812 |  0.0116382  |   0.359976 |  0.185179 | 0.595632 |  0.0919214 | 0.495624   | 0.108188   |    0.105647 |    0.251363 | 0.231237  |
| Qtau     | detailed     |  0.107002 |  -0.0943144 | 0.530605 | 0.903246 |  0.00520545 |   0.353669 |  0.180063 | 0.568337 |  0.0943144 | 0.469395   | 0.0967535  |    0.10016  |    0.233927 | 0.195324  |
| SoilTemp | baseline     |  2.70745  |  -2.34746   | 1.09245  | 0.98037  |  5.18328    |   1.07283  |  3.35301  | 0.226794 |  2.34746   | 0.0924528  | 0.0196296  |    3.05254  |    0.111634 | 0.194318  |
| SoilTemp | detailed     |  2.75667  |  -2.36237   | 1.09698  | 0.979873 |  5.11537    |   0.889721 |  3.3985   | 0.231433 |  2.36237   | 0.0969796  | 0.0201266  |    2.5448   |    0.101562 | 0.185866  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### out of range: baseline


### out of range: detailed

 - Ensemble Qanth min value of -68.4926 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

