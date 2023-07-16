# UK-KingsCollege: CM-BEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CM-BEM_UK-KingsCollege_baseline_attrs.md)
- [Detailed](CM-BEM_UK-KingsCollege_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |       MBE |       nSD |           R |      5th |       95th |     RMSE |      cRMSE |      AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |    Overlap |
|:-------|:-------------|---------:|----------:|----------:|------------:|---------:|-----------:|---------:|-----------:|----------:|-----------:|-----------:|------------:|------------:|-----------:|
| SWup   | baseline     | nan      | nan       | nan       | nan         | nan      | nan        | nan      | nan        | nan       | nan        | nan        | nan         |  nan        | nan        |
| SWup   | detailed     |  18.4427 |   1.18686 |   1.18195 |   0.526781  |   4.8316 |   0.923098 |  25.3559 |   1.07319  |   1.18686 |   0.181948 |   0.473219 |   0.425213  |    2.56191  |   0.344088 |
| LWup   | baseline     | nan      | nan       | nan       | nan         | nan      | nan        | nan      | nan        | nan       | nan        | nan        | nan         |  nan        | nan        |
| LWup   | detailed     |  30.9456 | -15.1882  |   1.4588  |   0.758597  |  36.528  |  19.4089   |  39.3322 |   0.956457 |  15.1882  |   0.458797 |   0.241403 |   0.22854   |    0.961207 |   0.272837 |
| Qle    | baseline     | nan      | nan       | nan       | nan         | nan      | nan        | nan      | nan        | nan       | nan        | nan        | nan         |  nan        | nan        |
| Qle    | detailed     |  21.2821 |   3.20593 |   3.16655 |   0.0817636 |  12.2575 |  25.55     |  69.9552 |   3.2418   |   3.20593 |   2.16655  |   0.918236 |  17.3508    |  540.635    |   0.14792  |
| Qh     | baseline     | nan      | nan       | nan       | nan         | nan      | nan        | nan      | nan        | nan       | nan        | nan        | nan         |  nan        | nan        |
| Qh     | detailed     |  53.7356 |  21.2568  |   1.3952  |   0.601264  |   2.6593 |  92.2184   |  76.8406 |   1.12642  |  21.2568  |   0.395202 |   0.398736 |   0.0124877 |    0.524393 |   0.145692 |
| Qtau   | baseline     | nan      | nan       | nan       | nan         | nan      | nan        | nan      | nan        | nan       | nan        | nan        | nan         |  nan        | nan        |
| Qtau   | detailed     | nan      | nan       | nan       | nan         | nan      | nan        | nan      | nan        | nan       | nan        | nan        | nan         |  nan        | nan        |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![CM-BEM_UK-KingsCollege_subset_SWup_v0-9.png](CM-BEM_UK-KingsCollege_subset_SWup_v0-9.png)](CM-BEM_UK-KingsCollege_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - CM-BEM SWup min value of -23.9485 is less than expected 0.0 [W/m2]
 - CM-BEM Qanth max value of 4804.4500 is greater than expected 1000.0 [W/m2]
 - CM-BEM Qanth min value of -955.5600 is less than expected 0.0 [W/m2]
 - CM-BEM alb min value of -0.3357 is less than expected 0.0 [1]
 - CM-BEM SWnet min value of -23.3883 is less than expected 0.0 [W/m2]
 - CM-BEM Albedo min value of -0.1209 is less than expected 0.0 [1]
 - CM-BEM Qle max value of 5731.2715 is greater than expected 700.0 [W/m2]
 - CM-BEM Qle min value of -4649.1187 is less than expected -700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

