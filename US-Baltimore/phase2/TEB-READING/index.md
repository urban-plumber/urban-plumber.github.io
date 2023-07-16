# US-Baltimore: TEB-READING

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TEB-READING_US-Baltimore_baseline_attrs.md)
- [Detailed](TEB-READING_US-Baltimore_detailed_attrs.md)

### Error metrics

| flux     | experiment   |       MAE |        MBE |        nSD |          R |        5th |      95th |     RMSE |      cRMSE |       AMBE |         1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:---------|:-------------|----------:|-----------:|-----------:|-----------:|-----------:|----------:|---------:|-----------:|-----------:|--------------:|------------:|------------:|------------:|------------:|
| SWup     | baseline     |   6.47868 |   1.76341  |   1.14739  |   0.972205 |   0.192245 |  14.9573  |   9.9631 |   0.292418 |   1.76341  |   0.147393    |   0.027795  |   0.48112   |    0.534135 |   0.0954472 |
| SWup     | detailed     |  19.7424  |  18.0395   |   1.5674   |   0.972356 |   0.567435 |  57.5962  |  28.0159 |   0.639215 |  18.0395   |   0.567396    |   0.0276438 |   0.412306  |    0.336944 |   0.193298  |
| LWup     | baseline     |   9.948   |   8.68363  |   1.17033  |   0.985408 |   0.499177 |  38.0534  |  16.3806 |   0.25133  |   8.68363  |   0.170326    |   0.0145922 |   6.51708   |    0.423161 |   0.0594906 |
| LWup     | detailed     |   9.1908  |   6.96145  |   1.18514  |   0.985405 |   3.35596  |  38.1186  |  16.0873 |   0.262434 |   6.96145  |   0.185137    |   0.0145954 |   6.58147   |    0.459104 |   0.0635151 |
| Qle      | baseline     |  32.3684  |   0.290139 |   0.999403 |   0.737917 |  14.541    |   1.1087  |  52.3574 |   0.723778 |   0.290139 |   0.000596894 |   0.262083  |   0.0174307 |    0.193088 |   0.29733   |
| Qle      | detailed     |  42.1618  |  21.7569   |   1.31335  |   0.724774 |  14.535    |  60.523   |  69.066  |   0.906158 |  21.7569   |   0.313347    |   0.275226  |   0.298317  |    0.816282 |   0.378003  |
| Qh       | baseline     |  49.5146  |  37.448    |   0.842304 |   0.843739 |  55.4692   |   6.51844 |  60.5634 |   0.536755 |  37.448    |   0.157697    |   0.156261  |   0.150536  |    0.577042 |   0.542067  |
| Qh       | detailed     |  33.3715  |   7.17752  |   0.745304 |   0.851904 |  41.1961   |  35.5825  |  47.933  |   0.534437 |   7.17752  |   0.254697    |   0.148096  |   0.0354137 |    0.362349 |   0.375248  |
| SoilTemp | baseline     | nan       | nan        | nan        | nan        | nan        | nan       | nan      | nan        | nan        | nan           | nan         | nan         |  nan        | nan         |
| SoilTemp | detailed     | nan       | nan        | nan        | nan        | nan        | nan       | nan      | nan        | nan        | nan           | nan         | nan         |  nan        | nan         |
| Qtau     | baseline     | nan       | nan        | nan        | nan        | nan        | nan       | nan      | nan        | nan        | nan           | nan         | nan         |  nan        | nan         |
| Qtau     | detailed     | nan       | nan        | nan        | nan        | nan        | nan       | nan      | nan        | nan        | nan           | nan         | nan         |  nan        | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TEB-READING_US-Baltimore_subset_SWup_v0-9.png](TEB-READING_US-Baltimore_subset_SWup_v0-9.png)](TEB-READING_US-Baltimore_subset_SWup_v0-9.png)

### out of range: baseline

 - TEB-READING Qanth min value of -5.1653 is less than expected 0.0 [W/m2]

### out of range: detailed

 - TEB-READING Qanth min value of -12.9143 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

