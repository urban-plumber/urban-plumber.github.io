# US-Minneapolis2: SUEWS

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](SUEWS_US-Minneapolis2_baseline_attrs.md)
- [Detailed](SUEWS_US-Minneapolis2_detailed_attrs.md)

### Error metrics

| flux     | experiment   |      MAE |       MBE |        nSD |          R |        5th |      95th |     RMSE |      cRMSE |      AMBE |         1-nSD |         1-R |   nSkewness |   nKurtosis |    Overlap |
|:---------|:-------------|---------:|----------:|-----------:|-----------:|-----------:|----------:|---------:|-----------:|----------:|--------------:|------------:|------------:|------------:|-----------:|
| SWup     | baseline     |  43.1372 | -42.4827  |   0.501473 |   0.601531 |   1.12912  | 152.043   |  88.7875 |   0.805091 |  42.4827  |   0.498528    |   0.398469  |   0.583527  |    1.11134  |   0.153708 |
| SWup     | detailed     |  35.8097 | -30.8761  |   0.591605 |   0.645807 |   0.793089 | 125.334   |  80.2964 |   0.765422 |  30.8761  |   0.408396    |   0.354193  |   0.629576  |    1.14889  |   0.100052 |
| LWup     | baseline     |  13.9202 |  11.8237  |   1.00226  |   0.983569 |  11.8201   |   8.1592  |  17.6907 |   0.181496 |  11.8237  |   0.0022625   |   0.0164307 |   0.493465  |    0.553734 |   0.105995 |
| LWup     | detailed     |  13.6927 |  11.3332  |   0.999261 |   0.983231 |  11.53     |   7.13135 |  17.4531 |   0.183065 |  11.3332  |   0.000740294 |   0.0167686 |   0.510804  |    0.567494 |   0.105062 |
| Qle      | baseline     |  48.9382 |  -5.07683 |   1.16289  |   0.414032 |   5.84909  |  19.4986  |  91.0121 |   1.17871  |   5.07683 |   0.162891    |   0.585968  |   0.416659  |    0.857015 |   0.258946 |
| Qle      | detailed     |  42.2136 |  -5.01457 |   1.12291  |   0.517787 |   4.48977  |  30.5247  |  80.9402 |   1.04789  |   5.01457 |   0.122912    |   0.482213  |   0.321211  |    0.549658 |   0.242099 |
| Qh       | baseline     | 112.539  | 102.544   |   2.22465  |   0.699919 |  29.2657   | 271.898   | 148.02   |   1.68372  | 102.544   |   1.22465     |   0.300081  |   0.0994612 |    0.830148 |   0.373488 |
| Qh       | detailed     |  50.5927 |   1.58931 |   1.65394  |   0.656688 |  19.0269   | 117.825   |  79.2839 |   1.25031  |   1.58931 |   0.653935    |   0.343312  |   0.432904  |    0.113631 |   0.289804 |
| Qg       | baseline     |  25.942  |  14.0636  |   1.30589  |   0.777069 |   1.26552  |  33.4471  |  39.3082 |   0.82208  |  14.0636  |   0.30588     |   0.222931  |   0.301225  |    0.765622 |   0.193751 |
| Qg       | detailed     |  24.7186 |  12.4766  |   1.24708  |   0.781597 |   1.58784  |  26.5588  |  36.9241 |   0.778319 |  12.4766  |   0.247071    |   0.218403  |   0.320386  |    0.786669 |   0.193177 |
| Qtau     | baseline     | nan      | nan       | nan        | nan        | nan        | nan       | nan      | nan        | nan       | nan           | nan         | nan         |  nan        | nan        |
| Qtau     | detailed     | nan      | nan       | nan        | nan        | nan        | nan       | nan      | nan        | nan       | nan           | nan         | nan         |  nan        | nan        |
| SoilTemp | baseline     | nan      | nan       | nan        | nan        | nan        | nan       | nan      | nan        | nan       | nan           | nan         | nan         |  nan        | nan        |
| SoilTemp | detailed     | nan      | nan       | nan        | nan        | nan        | nan       | nan      | nan        | nan       | nan           | nan         | nan         |  nan        | nan        |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![SUEWS_US-Minneapolis2_subset_SWup_v0-9.png](SUEWS_US-Minneapolis2_subset_SWup_v0-9.png)](SUEWS_US-Minneapolis2_subset_SWup_v0-9.png)

### out of range: baseline

 - SUEWS TairSurf max value of 348.7702 is greater than expected 333.0 [K]
 - SUEWS Qle max value of 734.3457 is greater than expected 700.0 [W/m2]

### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

