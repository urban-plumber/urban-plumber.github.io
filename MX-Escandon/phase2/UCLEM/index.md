# MX-Escandon: UCLEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](UCLEM_MX-Escandon_baseline_attrs.md)
- [Detailed](UCLEM_MX-Escandon_detailed_attrs.md)

### Error metrics

| flux   | experiment   |         MAE |        MBE |        nSD |          R |          5th |       95th |       RMSE |      cRMSE |       AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |    Overlap |
|:-------|:-------------|------------:|-----------:|-----------:|-----------:|-------------:|-----------:|-----------:|-----------:|-----------:|------------:|------------:|------------:|------------:|-----------:|
| SWup   | baseline     |  17.6657    |  15.5072   |   1.52854  |   0.984445 |   2.6983     |  42.7587   |  23.2556   |   0.571756 |  15.5072   |   0.528536  |   0.0155554 |    0.387223 |   0.0486658 |   0.253177 |
| SWup   | detailed     |   5.12609   |   0.222184 |   1.12816  |   0.984686 |   2.8115     |   7.1694   |   6.84744  |   0.225785 |   0.222184 |   0.128162  |   0.015314  |    0.276871 |   0.0631595 |   0.158882 |
| LWup   | baseline     | nan         | nan        | nan        | nan        | nan          | nan        | nan        | nan        | nan        | nan         | nan         |  nan        | nan         | nan        |
| LWup   | detailed     | nan         | nan        | nan        | nan        | nan          | nan        | nan        | nan        | nan        | nan         | nan         |  nan        | nan         | nan        |
| Qle    | baseline     |  26.4118    | -18.9038   |   0.776822 |   0.363085 |   2.7644     |  50.4853   |  41.6669   |   1.01948  |  18.9038   |   0.223178  |   0.636915  |    3.42667  |  20.9655    |   0.467256 |
| Qle    | detailed     |  26.8071    | -16.7792   |   0.978366 |   0.342284 |   1.8852     |  53.7015   |  44.6031   |   1.13465  |  16.7792   |   0.0216342 |   0.657716  |    3.57473  |  19.2772    |   0.405519 |
| Qh     | baseline     |  38.7115    | -22.8447   |   0.621148 |   0.684006 |   7.3106     |  82.8618   |  61.3311   |   0.73218  |  22.8447   |   0.378852  |   0.315994  |    0.532079 |   3.39526   |   0.297173 |
| Qh     | detailed     |  32.9814    |  -3.88047  |   1.05633  |   0.782208 |   6.9023     |  19.1879   |  53.0545   |   0.680657 |   3.88047  |   0.0563307 |   0.217792  |    0.328761 |   1.39141   |   0.282913 |
| Qtau   | baseline     |   0.0908117 |  -0.084546 |   0.514144 |   0.623128 |   0.00856638 |   0.268177 |   0.157822 |   0.789677 |   0.084546 |   0.485856  |   0.376872  |    3.19027  |  43.2491    |   0.255574 |
| Qtau   | detailed     |   0.139756  |  -0.121921 |   1.09864  |   0.127443 |   0.00856638 |   0.396477 |   0.264092 |   1.38816  |   0.121921 |   0.0986367 |   0.872557  |    7.05107  |  46.5935    |   0.55848  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![UCLEM_MX-Escandon_subset_SWup_v0-9.png](UCLEM_MX-Escandon_subset_SWup_v0-9.png)](UCLEM_MX-Escandon_subset_SWup_v0-9.png)

### out of range: baseline

 - UCLEM Qle max value of 1417.1621 is greater than expected 700.0 [W/m2]
 - UCLEM Qstor min value of -1075.8440 is less than expected -800.0 [W/m2]

### out of range: detailed

 - UCLEM Qle max value of 3684.3215 is greater than expected 700.0 [W/m2]
 - UCLEM Qstor min value of -1712.0471 is less than expected -800.0 [W/m2]
 - UCLEM Qh min value of -1815.8259 is less than expected -600.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

