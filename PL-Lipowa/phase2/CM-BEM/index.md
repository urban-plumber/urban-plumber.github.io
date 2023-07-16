# PL-Lipowa: CM-BEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CM-BEM_PL-Lipowa_baseline_attrs.md)
- [Detailed](CM-BEM_PL-Lipowa_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |       MBE |        nSD |          R |      5th |      95th |     RMSE |      cRMSE |      AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |    Overlap |
|:-------|:-------------|----------:|----------:|-----------:|-----------:|---------:|----------:|---------:|-----------:|----------:|------------:|------------:|------------:|------------:|-----------:|
| SWup   | baseline     | nan       | nan       | nan        | nan        | nan      | nan       | nan      | nan        | nan       | nan         | nan         | nan         |  nan        | nan        |
| SWup   | detailed     |   7.79468 |   1.49753 |   1.19953  |   0.874062 |   0.9666 |  12.2105  |  12.0128 |   0.584757 |   1.49753 |   0.199524  |   0.125938  |   0.0811339 |    2.09724  |   0.183653 |
| LWup   | baseline     | nan       | nan       | nan        | nan        | nan      | nan       | nan      | nan        | nan       | nan         | nan         | nan         |  nan        | nan        |
| LWup   | detailed     |  28.1904  | -27.1509  |   1.09462  |   0.984451 |  27.4339 |   5.24629 |  29.8235 |   0.207347 |  27.1509  |   0.0946196 |   0.0155486 |   0.806818  |    2.11855  |   0.227401 |
| Qle    | baseline     | nan       | nan       | nan        | nan        | nan      | nan       | nan      | nan        | nan       | nan         | nan         | nan         |  nan        | nan        |
| Qle    | detailed     |  16.597   |  -4.80482 |   0.662272 |   0.519595 |  15.4979 |  24.9963  |  28.5783 |   0.866244 |   4.80482 |   0.337729  |   0.480405  |   5.15276   |   73.239    |   0.35184  |
| Qh     | baseline     | nan       | nan       | nan        | nan        | nan      | nan       | nan      | nan        | nan       | nan         | nan         | nan         |  nan        | nan        |
| Qh     | detailed     |  58.4715  |  57.3311  |   1.21861  |   0.882169 |  39.6588 |  86.9076  |  69.2421 |   0.578767 |  57.3311  |   0.218611  |   0.117831  |   0.29864   |    0.748494 |   0.516663 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![CM-BEM_PL-Lipowa_subset_SWup_v0-9.png](CM-BEM_PL-Lipowa_subset_SWup_v0-9.png)](CM-BEM_PL-Lipowa_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - CM-BEM SWnet min value of -38.4137 is less than expected 0.0 [W/m2]
 - CM-BEM SWup min value of -0.3439 is less than expected 0.0 [W/m2]
 - CM-BEM Albedo min value of -0.0009 is less than expected 0.0 [1]
 - CM-BEM alb min value of -0.0009 is less than expected 0.0 [1]
 - CM-BEM Qle max value of 1486.1875 is greater than expected 700.0 [W/m2]
 - CM-BEM Qle min value of -1454.8547 is less than expected -700.0 [W/m2]
 - CM-BEM Qanth max value of 15731.0400 is greater than expected 1000.0 [W/m2]
 - CM-BEM Qanth min value of -5066.3600 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

