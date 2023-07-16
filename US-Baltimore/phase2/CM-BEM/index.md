# US-Baltimore: CM-BEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CM-BEM_US-Baltimore_baseline_attrs.md)
- [Detailed](CM-BEM_US-Baltimore_detailed_attrs.md)

### Error metrics

| flux     | experiment   |      MAE |        MBE |        nSD |          R |      5th |     95th |     RMSE |      cRMSE |       AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:---------|:-------------|---------:|-----------:|-----------:|-----------:|---------:|---------:|---------:|-----------:|-----------:|------------:|------------:|------------:|------------:|------------:|
| SWup     | baseline     | nan      | nan        | nan        | nan        | nan      | nan      | nan      | nan        | nan        | nan         | nan         |  nan        |  nan        | nan         |
| SWup     | detailed     |   6.2103 |  -0.240481 |   0.984217 |   0.943188 |   0.1268 |   2.0174 |  11.229  |   0.334782 |   0.240481 |   0.0157831 |   0.0568117 |    0.29034  |    0.568805 |   0.06357   |
| LWup     | baseline     | nan      | nan        | nan        | nan        | nan      | nan      | nan      | nan        | nan        | nan         | nan         |  nan        |  nan        | nan         |
| LWup     | detailed     |  16.8714 |  -8.0632   |   1.15121  |   0.965408 |  14.9691 |  21.8957 |  19.4446 |   0.320169 |   8.0632   |   0.151207  |   0.0345917 |    7.68366  |    0.526141 |   0.126746  |
| Qle      | baseline     | nan      | nan        | nan        | nan        | nan      | nan      | nan      | nan        | nan        | nan         | nan         |  nan        |  nan        | nan         |
| Qle      | detailed     |  34.0058 |  16.9764   |   1.18868  |   0.73176  |  15.5649 |  31.6182 |  61.7368 |   0.820549 |  16.9764   |   0.188676  |   0.26824   |    4.43176  |  119.544    |   0.0829187 |
| Qh       | baseline     | nan      | nan        | nan        | nan        | nan      | nan      | nan      | nan        | nan        | nan         | nan         |  nan        |  nan        | nan         |
| Qh       | detailed     |  36.6834 |   4.81171  |   0.641905 |   0.834635 |  28.4498 |  73.0425 |  51.9715 |   0.583549 |   4.81171  |   0.358096  |   0.165365  |    0.253943 |    0.598141 |   0.334657  |
| SoilTemp | baseline     | nan      | nan        | nan        | nan        | nan      | nan      | nan      | nan        | nan        | nan         | nan         |  nan        |  nan        | nan         |
| SoilTemp | detailed     | nan      | nan        | nan        | nan        | nan      | nan      | nan      | nan        | nan        | nan         | nan         |  nan        |  nan        | nan         |
| Qtau     | baseline     | nan      | nan        | nan        | nan        | nan      | nan      | nan      | nan        | nan        | nan         | nan         |  nan        |  nan        | nan         |
| Qtau     | detailed     | nan      | nan        | nan        | nan        | nan      | nan      | nan      | nan        | nan        | nan         | nan         |  nan        |  nan        | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![CM-BEM_US-Baltimore_subset_SWup_v0-9.png](CM-BEM_US-Baltimore_subset_SWup_v0-9.png)](CM-BEM_US-Baltimore_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - CM-BEM Qanth min value of -816.6700 is less than expected 0.0 [W/m2]
 - CM-BEM SWnet min value of -77.1605 is less than expected 0.0 [W/m2]
 - CM-BEM Qle max value of 1850.2094 is greater than expected 700.0 [W/m2]
 - CM-BEM Qle min value of -4547.0718 is less than expected -700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

