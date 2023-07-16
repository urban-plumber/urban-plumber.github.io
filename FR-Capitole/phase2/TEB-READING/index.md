# FR-Capitole: TEB-READING

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TEB-READING_FR-Capitole_baseline_attrs.md)
- [Detailed](TEB-READING_FR-Capitole_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |       MBE |        nSD |          R |       5th |      95th |     RMSE |      cRMSE |      AMBE |       1-nSD |          1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|---------:|----------:|-----------:|-----------:|----------:|----------:|---------:|-----------:|----------:|------------:|-------------:|------------:|------------:|------------:|
| SWup   | baseline     |   8.5371 |  -8.48032 |   0.845445 |   0.992165 |   2.67678 |  18.8707  |  10.6538 |   0.192704 |   8.48032 |   0.154555  |   0.00783475 |   0.0246652 |   0.060581  |   0.161138  |
| SWup   | detailed     |  12.8588 | -12.8536  |   0.753636 |   0.989185 |   2.72431 |  26.4275  |  15.857  |   0.277483 |  12.8536  |   0.246363  |   0.0108153  |   0.194845  |   0.376444  |   0.164945  |
| LWup   | baseline     |  11.9125 |   5.91504 |   1.28858  |   0.986221 |   8.74306 |  43.3998  |  19.0776 |   0.344656 |   5.91504 |   0.288578  |   0.0137788  |   0.306285  |   2.70929   |   0.09688   |
| LWup   | detailed     |  15.233  |   8.6924  |   1.36694  |   0.975111 |   8.56067 |  56.792   |  25.2366 |   0.450212 |   8.6924  |   0.366941  |   0.0248894  |   0.428954  |   3.77381   |   0.0946432 |
| Qle    | baseline     |  14.9176 |  -7.45327 |   1.02904  |   0.553322 |   2.47613 |  12.9387  |  21.1629 |   0.959241 |   7.45327 |   0.0290403 |   0.446678   |   1.84289   |   3.7211    |   0.396175  |
| Qle    | detailed     |  14.5304 |  -1.82144 |   1.14586  |   0.548809 |   2.15221 |   2.32305 |  21.2897 |   1.02727  |   1.82144 |   0.145855  |   0.451191   |   1.18601   |   2.10696   |   0.339408  |
| Qh     | baseline     |  28.034  |  -4.85374 |   1.15452  |   0.907212 |   1.78706 |  34.5943  |  40.4015 |   0.487984 |   4.85374 |   0.154519  |   0.0927882  |   0.163999  |   0.317063  |   0.193383  |
| Qh     | detailed     |  32.5711 |  -8.84387 |   1.22283  |   0.908349 |  16.095   |  38.0829  |  43.9081 |   0.523259 |   8.84387 |   0.22283   |   0.0916507  |   0.0479931 |   0.0335387 |   0.293153  |
| Qtau   | baseline     | nan      | nan       | nan        | nan        | nan       | nan       | nan      | nan        | nan       | nan         | nan          | nan         | nan         | nan         |
| Qtau   | detailed     | nan      | nan       | nan        | nan        | nan       | nan       | nan      | nan        | nan       | nan         | nan          | nan         | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TEB-READING_FR-Capitole_subset_SWup_v0-9.png](TEB-READING_FR-Capitole_subset_SWup_v0-9.png)](TEB-READING_FR-Capitole_subset_SWup_v0-9.png)

### out of range: baseline

 - TEB-READING Qanth min value of -3.9309 is less than expected 0.0 [W/m2]

### out of range: detailed

 - TEB-READING Qanth min value of -16.4954 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

