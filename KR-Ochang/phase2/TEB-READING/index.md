# KR-Ochang: TEB-READING

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TEB-READING_KR-Ochang_baseline_attrs.md)
- [Detailed](TEB-READING_KR-Ochang_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |       MBE |      nSD |        R |      5th |     95th |    RMSE |    cRMSE |     AMBE |     1-nSD |       1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|----------:|---------:|---------:|---------:|---------:|--------:|---------:|---------:|----------:|----------:|------------:|------------:|----------:|
| SWup   | baseline     | 13.7268  | -12.6656  | 0.721415 | 0.933103 |  1.61258 | 33.3195  | 23.7514 | 0.41729  | 12.6656  | 0.278586  | 0.0668975 |    0.449428 |    1.0086   | 0.128207  |
| SWup   | detailed     |  8.47596 |  -5.61065 | 0.874079 | 0.940348 |  1.48314 |  9.23478 | 17.607  | 0.346608 |  5.61065 | 0.125922  | 0.0596519 |    0.42532  |    1.08407  | 0.0709252 |
| LWup   | baseline     | 19.3282  |  19.2617  | 1.17239  | 0.985783 |  9.33924 | 52.4189  | 24.9957 | 0.25111  | 19.2617  | 0.172391  | 0.0142174 |    4.63567  |    0.347951 | 0.0957788 |
| LWup   | detailed     | 18.0806  |  17.9512  | 1.15722  | 0.987447 |  8.79438 | 47.1452  | 23.2087 | 0.231883 | 17.9512  | 0.157214  | 0.012553  |    3.95483  |    0.271234 | 0.0964225 |
| Qle    | baseline     | 29.5435  |   4.93527 | 1.13813  | 0.660367 |  2.8503  | 36.4458  | 49.4941 | 0.890043 |  4.93527 | 0.138133  | 0.339633  |    0.220798 |    0.666891 | 0.267782  |
| Qle    | detailed     | 33.321   |  13.1288  | 1.2867   | 0.66638  |  3.07599 | 58.6454  | 55.2495 | 0.969917 | 13.1288  | 0.286703  | 0.33362   |    0.332221 |    0.822444 | 0.326495  |
| Qh     | baseline     | 39.1596  |  36.256   | 1.07324  | 0.903699 | 30.4094  | 46.8855  | 47.6391 | 0.460515 | 36.256   | 0.0732445 | 0.0963014 |    0.197747 |    0.530255 | 0.595363  |
| Qh     | detailed     | 21.9196  |  13.2466  | 0.950361 | 0.905502 | 19.0179  | 10.1245  | 31.5498 | 0.426707 | 13.2466  | 0.0496384 | 0.0944984 |    0.115835 |    0.396862 | 0.433344  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TEB-READING_KR-Ochang_subset_SWup_v0-9.png](TEB-READING_KR-Ochang_subset_SWup_v0-9.png)](TEB-READING_KR-Ochang_subset_SWup_v0-9.png)

### out of range: baseline

 - TEB-READING Qanth min value of -5.0283 is less than expected 0.0 [W/m2]

### out of range: detailed

 - TEB-READING Qanth min value of -9.6024 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

