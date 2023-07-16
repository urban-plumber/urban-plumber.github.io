# NL-Amsterdam: Ensemble

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](Ensemble_NL-Amsterdam_baseline_attrs.md)
- [Detailed](Ensemble_NL-Amsterdam_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |        MBE |      nSD |        R |        5th |      95th |      RMSE |    cRMSE |      AMBE |     1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|-----------:|---------:|---------:|-----------:|----------:|----------:|---------:|----------:|----------:|----------:|------------:|------------:|----------:|
| SWup   | baseline     | 11.0444   |  10.9058   | 1.34638  | 0.985499 |  1.01309   | 28.1386   | 14.744    | 0.398778 | 10.9058   | 0.346374  | 0.0145012 |  0.031017   |    0.165204 | 0.0974475 |
| SWup   | detailed     |  3.93466  |   2.58541  | 1.05922  | 0.985169 |  0.655024  |  5.75204  |  5.32034  | 0.186884 |  2.58541  | 0.0592184 | 0.014831  |  0.0321783  |    0.167753 | 0.071557  |
| LWup   | baseline     |  6.9634   |   1.20822  | 1.15476  | 0.988664 |  8.1203    | 14.7001   |  8.82697  | 0.223901 |  1.20822  | 0.154763  | 0.0113355 |  0.0166067  |    0.270061 | 0.0816253 |
| LWup   | detailed     |  6.36037  |  -0.552764 | 1.12522  | 0.989455 |  7.24945   | 10.9148   |  7.77239  | 0.19852  |  0.552764 | 0.125214  | 0.0105452 |  0.00385772 |    0.284869 | 0.0761474 |
| Qle    | baseline     | 17.3211   | -10.9751   | 0.760443 | 0.682217 |  1.50286   | 20.2899   | 28.0509   | 0.735323 | 10.9751   | 0.239557  | 0.317783  |  0.0860635  |    0.629025 | 0.310288  |
| Qle    | detailed     | 16.5213   |  -9.39144  | 0.76486  | 0.684165 |  0.594948  | 17.3229   | 27.4191   | 0.733778 |  9.39144  | 0.23514   | 0.315835  |  0.0471261  |    0.755405 | 0.270764  |
| Qh     | baseline     | 28.7541   |  -2.4986   | 0.918522 | 0.87365  |  7.89373   |  1.68898  | 45.5972   | 0.488619 |  2.4986   | 0.0814774 | 0.12635   |  0.679708   |    0.678759 | 0.136343  |
| Qh     | detailed     | 28.503    |   6.41717  | 0.974009 | 0.877255 | 12.7148    | 18.3681   | 46.0766   | 0.489679 |  6.41717  | 0.0259907 | 0.122745  |  0.661727   |    0.69742  | 0.140656  |
| Qtau   | baseline     |  0.330545 |  -0.316505 | 0.409922 | 0.741172 |  0.0151761 |  1.01022  |  0.553684 | 0.748593 |  0.316505 | 0.590078  | 0.258828  |  0.268883   |    0.633617 | 0.266993  |
| Qtau   | detailed     |  0.293314 |  -0.266248 | 0.424936 | 0.748583 |  0.0157603 |  0.943114 |  0.52094  | 0.737815 |  0.266248 | 0.575064  | 0.251417  |  0.314689   |    0.672752 | 0.24077   |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### out of range: baseline


### out of range: detailed

 - Ensemble Qanth max value of 1991.3081 is greater than expected 1000.0 [W/m2]
 - Ensemble Qanth min value of -188.1553 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

