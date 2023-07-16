# MX-Escandon: Ensemble

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](Ensemble_MX-Escandon_baseline_attrs.md)
- [Detailed](Ensemble_MX-Escandon_detailed_attrs.md)

### Error metrics

| flux   | experiment   |         MAE |         MBE |        nSD |          R |          5th |       95th |       RMSE |      cRMSE |        AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |    Overlap |
|:-------|:-------------|------------:|------------:|-----------:|-----------:|-------------:|-----------:|-----------:|-----------:|------------:|------------:|------------:|------------:|------------:|-----------:|
| SWup   | baseline     |  16.2126    |  13.9294    |   1.50666  |   0.981597 |   2.63895    |  44.098    |  21.9278   |   0.558711 |  13.9294    |   0.506661  |   0.0184027 |   0.773595  |   0.0382015 |   0.236138 |
| SWup   | detailed     |   5.15473   |  -0.500469  |   1.12011  |   0.982978 |   2.76215    |   8.63718  |   6.96716  |   0.22926  |   0.500469  |   0.120114  |   0.0170219 |   0.635989  |   0.0176665 |   0.158202 |
| LWup   | baseline     | nan         | nan         | nan        | nan        | nan          | nan        | nan        | nan        | nan         | nan         | nan         | nan         | nan         | nan        |
| LWup   | detailed     | nan         | nan         | nan        | nan        | nan          | nan        | nan        | nan        | nan         | nan         | nan         | nan         | nan         | nan        |
| Qle    | baseline     |  23.9552    | -19.6791    |   0.445723 |   0.499573 |   2.93578    |  62.093    |  37.2373   |   0.867944 |  19.6791    |   0.554277  |   0.500427  |   1.0164    |   2.22098   |   0.40606  |
| Qle    | detailed     |  21.3471    | -16.3966    |   0.53097  |   0.586763 |   2.85638    |  46.2288   |  33.8058   |   0.811679 |  16.3966    |   0.46903   |   0.413237  |   0.339802  |   0.378935  |   0.352784 |
| Qh     | baseline     |  31.178     |  -1.76146   |   0.869718 |   0.794121 |  11.5168     |  15.9564   |  47.6422   |   0.612443 |   1.76146   |   0.130282  |   0.205879  |   0.20438   |   0.939405  |   0.30951  |
| Qh     | detailed     |  29.5448    |  -5.33206   |   1.05405  |   0.822718 |   0.00518889 |  12.8447   |  48.0059   |   0.613719 |   5.33206   |   0.0540544 |   0.177282  |   0.158067  |   0.551524  |   0.15716  |
| Qtau   | baseline     |   0.0980587 |  -0.0954738 |   0.389087 |   0.707534 |   0.00584355 |   0.300016 |   0.161944 |   0.775116 |   0.0954738 |   0.610913  |   0.292466  |   0.0623362 |   0.181498  |   0.312123 |
| Qtau   | detailed     |   0.114431  |  -0.113126  |   0.278151 |   0.687409 |   0.00681634 |   0.356399 |   0.180527 |   0.833643 |   0.113126  |   0.721849  |   0.312591  |   0.121907  |   0.252828  |   0.413339 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### out of range: baseline

 - Ensemble TairSurf max value of 684.8875 is greater than expected 333.0 [K]

### out of range: detailed

 - Ensemble TairSurf max value of 627.0530 is greater than expected 333.0 [K]


[Link to variable definitions](../modelattrs/variable_definitions.md)

