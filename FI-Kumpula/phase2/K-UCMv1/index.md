# FI-Kumpula: K-UCMv1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](K-UCMv1_FI-Kumpula_baseline_attrs.md)
- [Detailed](K-UCMv1_FI-Kumpula_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |        MBE |        nSD |          R |      5th |     95th |     RMSE |      cRMSE |       AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|-----------:|-----------:|-----------:|---------:|---------:|---------:|-----------:|-----------:|-----------:|-----------:|------------:|------------:|------------:|
| SWup   | baseline     | nan       | nan        | nan        | nan        | nan      | nan      | nan      | nan        | nan        | nan        | nan        |  nan        |  nan        | nan         |
| SWup   | detailed     |  21.7641  | -19.3415   |   0.583817 |   0.68489  |   0.6941 |  39.0068 |  39.0071 |   0.735623 |  19.3415   |   0.41619  |   0.31511  |    0.275059 |    0.860548 |   0.203024  |
| LWup   | baseline     | nan       | nan        | nan        | nan        | nan      | nan      | nan      | nan        | nan        | nan        | nan        |  nan        |  nan        | nan         |
| LWup   | detailed     |   6.89126 |   4.7644   |   1.14176  |   0.897158 |   5.9316 |  10.5584 |  27.0429 |   0.504915 |   4.7644   |   0.141758 |   0.102842 |   78.5442   | 1057.67     |   0.0737529 |
| Qle    | baseline     | nan       | nan        | nan        | nan        | nan      | nan      | nan      | nan        | nan        | nan        | nan        |  nan        |  nan        | nan         |
| Qle    | detailed     |  14.9999  |   0.246846 |   1.88788  |   0.339086 |   7.0711 |  10.9697 |  68.5749 |   1.81212  |   0.246846 |   0.887879 |   0.660914 |   16.6821   |  285.636    |   0.175526  |
| Qh     | baseline     | nan       | nan        | nan        | nan        | nan      | nan      | nan      | nan        | nan        | nan        | nan        |  nan        |  nan        | nan         |
| Qh     | detailed     |  28.4575  | -16.9473   |   0.733874 |   0.578771 |   4.9879 |  77.8592 |  51.8965 |   0.830109 |  16.9473   |   0.266126 |   0.421229 |    7.14158  |  112.388    |   0.116113  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![K-UCMv1_FI-Kumpula_subset_SWup_v0-9.png](K-UCMv1_FI-Kumpula_subset_SWup_v0-9.png)](K-UCMv1_FI-Kumpula_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - K-UCMv1 Qstor max value of 820.8893 is greater than expected 800.0 [W/m2]
 - K-UCMv1 Qstor min value of -11376.7846 is less than expected -800.0 [W/m2]
 - K-UCMv1 LWnet min value of -3806.2485 is less than expected -500.0 [W/m2]
 - K-UCMv1 Qh max value of 2344.6156 is greater than expected 600.0 [W/m2]
 - K-UCMv1 SWnet min value of -19.8409 is less than expected 0.0 [W/m2]
 - K-UCMv1 LWup max value of 4110.0786 is greater than expected 1000.0 [W/m2]
 - K-UCMv1 Qle max value of 5465.4380 is greater than expected 700.0 [W/m2]
 - K-UCMv1 Qstar min value of -3741.6198 is less than expected -500.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

