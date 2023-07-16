# US-Minneapolis2: CM-BEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CM-BEM_US-Minneapolis2_baseline_attrs.md)
- [Detailed](CM-BEM_US-Minneapolis2_detailed_attrs.md)

### Error metrics

| flux     | experiment   |      MAE |       MBE |        nSD |          R |      5th |     95th |     RMSE |      cRMSE |      AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |     Overlap |
|:---------|:-------------|---------:|----------:|-----------:|-----------:|---------:|---------:|---------:|-----------:|----------:|-----------:|-----------:|------------:|------------:|------------:|
| SWup     | baseline     | nan      | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan        | nan        | nan         |  nan        | nan         |
| SWup     | detailed     |  35.2507 | -32.0802  |   0.575702 |   0.650283 |   1.2503 | 129.523  |  80.5849 |   0.763344 |  32.0802  |   0.424298 |   0.349717 |   0.633764  |    1.14843  |   0.114979  |
| LWup     | baseline     | nan      | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan        | nan        | nan         |  nan        | nan         |
| LWup     | detailed     |  13.5361 |  -9.17553 |   0.868617 |   0.982916 |   5.1276 |  30.6877 |  18.1921 |   0.216657 |   9.17553 |   0.131384 |   0.017084 |   0.751915  |    0.661301 |   0.0771679 |
| Qle      | baseline     | nan      | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan        | nan        | nan         |  nan        | nan         |
| Qle      | detailed     |  39.798  |  31.3128  |   1.53653  |   0.884447 |   0.7852 | 135.505  |  69.295  |   0.801848 |  31.3128  |   0.536525 |   0.115553 |   0.0904539 |    0.31466  |   0.180677  |
| Qh       | baseline     | nan      | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan        | nan        | nan         |  nan        | nan         |
| Qh       | detailed     |  35.1757 |  -1.83556 |   0.622009 |   0.592401 |  19.1535 |  51.1975 |  51.1443 |   0.806187 |   1.83556 |   0.377991 |   0.407599 |   0.406753  |    0.271759 |   0.304215  |
| Qg       | baseline     | nan      | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan        | nan        | nan         |  nan        | nan         |
| Qg       | detailed     |  24.671  |   1.51931 |   1.21113  |   0.753198 |  15.5117 |   2.4355 |  35.8194 |   0.801492 |   1.51931 |   0.211115 |   0.246802 |   1.28251   |   10.399    |   0.233029  |
| Qtau     | baseline     | nan      | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan        | nan        | nan         |  nan        | nan         |
| Qtau     | detailed     | nan      | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan        | nan        | nan         |  nan        | nan         |
| SoilTemp | baseline     | nan      | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan        | nan        | nan         |  nan        | nan         |
| SoilTemp | detailed     | nan      | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan        | nan        | nan         |  nan        | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![CM-BEM_US-Minneapolis2_subset_SWup_v0-9.png](CM-BEM_US-Minneapolis2_subset_SWup_v0-9.png)](CM-BEM_US-Minneapolis2_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - CM-BEM Qstor min value of -1880.1644 is less than expected -800.0 [W/m2]
 - CM-BEM Qanth max value of 7591.7500 is greater than expected 1000.0 [W/m2]
 - CM-BEM Qanth min value of -2014.1100 is less than expected 0.0 [W/m2]
 - CM-BEM Qg min value of -1880.1644 is less than expected -500.0 [W/m2]
 - CM-BEM SWnet min value of -93.5659 is less than expected 0.0 [W/m2]
 - CM-BEM Qle max value of 1023.9537 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

