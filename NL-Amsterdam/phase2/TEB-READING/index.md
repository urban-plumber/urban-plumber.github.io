# NL-Amsterdam: TEB-READING

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TEB-READING_NL-Amsterdam_baseline_attrs.md)
- [Detailed](TEB-READING_NL-Amsterdam_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |       MBE |        nSD |          R |        5th |      95th |      RMSE |      cRMSE |      AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|----------:|-----------:|-----------:|-----------:|----------:|----------:|-----------:|----------:|------------:|------------:|------------:|------------:|------------:|
| SWup   | baseline     |   5.06513 |   4.32559 |   1.10994  |   0.985796 |   0.744836 |   9.82583 |   6.76113 |   0.208846 |   4.32559 |   0.109936  |   0.0142037 |   0.0161802 |    0.141608 |   0.0818794 |
| SWup   | detailed     |   8.32231 |  -7.97403 |   0.718697 |   0.972811 |   0.207672 |  19.5089  |  11.6948  |   0.34382  |   7.97403 |   0.281304  |   0.0271887 |   0.286025  |    1.04939  |   0.117417  |
| LWup   | baseline     |   9.4291  |   6.02405 |   1.25298  |   0.981322 |   4.76563  |  31.3353  |  14.3275  |   0.332875 |   6.02405 |   0.252978  |   0.0186782 |   0.316101  |    0.470604 |   0.0834907 |
| LWup   | detailed     |  13.001   |  10.4575  |   1.36552  |   0.971995 |   3.71832  |  46.7423  |  20.7307  |   0.458352 |  10.4575  |   0.365515  |   0.0280053 |   0.447777  |    0.656713 |   0.0989698 |
| Qle    | baseline     |  22.3588  | -11.9134  |   1.02704  |   0.631281 |   3.74958  |   1.083   |  32.8068  |   0.870694 |  11.9134  |   0.0270372 |   0.368719  |   0.323353  |    0.414633 |   0.447061  |
| Qle    | detailed     |  21.0443  |  -9.0291  |   1.02799  |   0.634521 |   3.74958  |   1.91569 |  31.7585  |   0.867297 |   9.0291  |   0.0279928 |   0.365479  |   0.229856  |    0.455677 |   0.381662  |
| Qh     | baseline     |  33.2823  |  16.8435  |   1.0619   |   0.86997  |  16.9231   |  48.8143  |  52.1021  |   0.529141 |  16.8435  |   0.0618985 |   0.13003   |   0.618797  |    0.744496 |   0.121288  |
| Qh     | detailed     |  34.7465  |  15.2864  |   1.13356  |   0.869934 |   5.92835  |  58.2525  |  54.3022  |   0.559209 |  15.2864  |   0.133562  |   0.130066  |   0.518572  |    0.817185 |   0.13381   |
| Qtau   | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan         | nan         |  nan        | nan         |
| Qtau   | detailed     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan         | nan         |  nan        | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TEB-READING_NL-Amsterdam_subset_SWup_v0-9.png](TEB-READING_NL-Amsterdam_subset_SWup_v0-9.png)](TEB-READING_NL-Amsterdam_subset_SWup_v0-9.png)

### out of range: baseline

 - TEB-READING Qanth min value of -3.5007 is less than expected 0.0 [W/m2]

### out of range: detailed

 - TEB-READING Qanth min value of -17.0365 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

