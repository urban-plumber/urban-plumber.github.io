# US-Minneapolis1: UCLEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](UCLEM_US-Minneapolis1_baseline_attrs.md)
- [Detailed](UCLEM_US-Minneapolis1_detailed_attrs.md)

### Error metrics

| flux     | experiment   |        MAE |         MBE |        nSD |          R |         5th |     95th |       RMSE |      cRMSE |        AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:---------|:-------------|-----------:|------------:|-----------:|-----------:|------------:|---------:|-----------:|-----------:|------------:|------------:|------------:|------------:|------------:|------------:|
| SWup     | baseline     |  39.3959   | -38.4745    |   0.521369 |   0.861392 |   1.6195    | 159.673  |  70.5976   |   0.611244 |  38.4745    |   0.478632  |   0.138608  |    0.582407 |    0.968316 |   0.164672  |
| SWup     | detailed     |  27.0359   | -17.0803    |   0.710493 |   0.842413 |   1.2207    | 101.992  |  56.3711   |   0.554746 |  17.0803    |   0.289508  |   0.157587  |    0.58018  |    0.989935 |   0.100152  |
| LWup     | baseline     |  16.9185   |  15.9782    |   1.0473   |   0.984654 |  11.351     |  22.619  |  20.8814   |   0.185421 |  15.9782    |   0.0472993 |   0.015346  |    0.293333 |    0.389442 |   0.120173  |
| LWup     | detailed     |  11.3738   |   4.08869   |   1.06913  |   0.98295  |   6.0769    |  15.0961 |  15.2802   |   0.203067 |   4.08869   |   0.0691266 |   0.0170501 |    0.356519 |    0.121361 |   0.0849129 |
| Qle      | baseline     |  21.5293   |  -6.24357   |   1.31181  |   0.761953 |  11.4286    |  28.5471 |  47.5968   |   0.84957  |   6.24357   |   0.311808  |   0.238047  |    1.05537  |    1.06482  |   0.136261  |
| Qle      | detailed     |  23.0858   |  -4.61014   |   1.37385  |   0.775289 |  12.5679    |  41.3878 |  48.5492   |   0.870172 |   4.61014   |   0.373848  |   0.224711  |    0.997957 |    0.835211 |   0.206895  |
| Qh       | baseline     |  29.0553   |  15.0633    |   0.938472 |   0.853675 |  26.6544    |   6.7381 |  46.821    |   0.527665 |  15.0633    |   0.0615296 |   0.146325  |    0.293129 |    2.2241   |   0.240311  |
| Qh       | detailed     |  24.9045   |   7.62535   |   1.04089  |   0.862949 |  13.2158    |   9.8055 |  45.6487   |   0.535707 |   7.62535   |   0.040888  |   0.137051  |    0.28892  |    2.09161  |   0.115482  |
| Qg       | baseline     | nan        | nan         | nan        | nan        | nan         | nan      | nan        | nan        | nan         | nan         | nan         |  nan        |  nan        | nan         |
| Qg       | detailed     | nan        | nan         | nan        | nan        | nan         | nan      | nan        | nan        | nan         | nan         | nan         |  nan        |  nan        | nan         |
| Qtau     | baseline     |   0.109206 |  -0.0700853 |   0.700724 |   0.758746 |   0.0026152 |   0.2122 |   0.167027 |   0.653966 |   0.0700853 |   0.299277  |   0.241254  |    0.100161 |    0.259296 |   0.158288  |
| Qtau     | detailed     |   0.149665 |  -0.146866  |   0.49882  |   0.801868 |   0.0052152 |   0.3883 |   0.213762 |   0.669959 |   0.146866  |   0.50118   |   0.198132  |    2.82332  |   54.456    |   0.312421  |
| SoilTemp | baseline     | nan        | nan         | nan        | nan        | nan         | nan      | nan        | nan        | nan         | nan         | nan         |  nan        |  nan        | nan         |
| SoilTemp | detailed     | nan        | nan         | nan        | nan        | nan         | nan      | nan        | nan        | nan         | nan         | nan         |  nan        |  nan        | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![UCLEM_US-Minneapolis1_subset_SWup_v0-9.png](UCLEM_US-Minneapolis1_subset_SWup_v0-9.png)](UCLEM_US-Minneapolis1_subset_SWup_v0-9.png)

### out of range: baseline

 - UCLEM Qh max value of 866.0164 is greater than expected 600.0 [W/m2]
 - UCLEM Qle min value of -1189.1748 is less than expected -700.0 [W/m2]

### out of range: detailed

 - UCLEM Qh max value of 1018.7186 is greater than expected 600.0 [W/m2]
 - UCLEM Qle min value of -1276.3920 is less than expected -700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

