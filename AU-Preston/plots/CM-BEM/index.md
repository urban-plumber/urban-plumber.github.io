# AU-Preston: CM-BEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CM-BEM_AU-Preston_baseline_attrs.md)
- [Detailed](CM-BEM_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |       MBE |        nSD |          R |      5th |     95th |     RMSE |      cRMSE |      AMBE |        1-nSD |         1-R |   nSkewness |   nKurtosis |    Overlap |
|:-------|:-------------|----------:|----------:|-----------:|-----------:|---------:|---------:|---------:|-----------:|----------:|-------------:|------------:|------------:|------------:|-----------:|
| SWup   | baseline     |   9.51008 |   5.86564 |   1.0072   |   0.962798 |   0.066  |   3.0329 |  14.0415 |   0.273846 |   5.86564 |   0.00719905 |   0.037202  |   0.406995  |   0.738212  |   0.103003 |
| SWup   | detailed     |   5.98651 |   3.05791 |   0.973795 |   0.975901 |   0.0015 |   2.7545 |  10.6164 |   0.218226 |   3.05791 |   0.0262053  |   0.0240994 |   0.230374  |   0.313159  |   0.082209 |
| LWup   | baseline     |  13.4912  |   2.27203 |   1.33286  |   0.961304 |  11.5732 |  41.2543 |  19.5648 |   0.462544 |   2.27203 |   0.332858   |   0.038696  |   0.103952  |   0.049322  |   0.137424 |
| LWup   | detailed     |  12.4184  |   3.20522 |   1.28194  |   0.962799 |   7.4947 |  36.593  |  17.8582 |   0.418171 |   3.20522 |   0.281937   |   0.0372007 |   0.0712734 |   0.120897  |   0.120413 |
| Qle    | baseline     |  27.3048  | -14.1111  |   0.666985 |   0.604318 |   4.0793 |  29.7439 |  43.9462 |   0.799204 |  14.1111  |   0.333015   |   0.395682  |   0.21214   |   0.212338  |   0.231791 |
| Qle    | detailed     |  24.2048  |  -3.05408 |   0.845057 |   0.64985  |   7.7186 |   2.1925 |  40.9792 |   0.784729 |   3.05408 |   0.154943   |   0.35015   |   0.085972  |   0.410943  |   0.140804 |
| Qh     | baseline     |  33.7031  |  17.6874  |   0.838817 |   0.895228 |  30.8993 |  20.7711 |  44.9464 |   0.449165 |  17.6874  |   0.161183   |   0.104772  |   0.0592006 |   0.169129  |   0.355317 |
| Qh     | detailed     |  32.198   |   6.47866 |   0.752938 |   0.883006 |  22.1534 |  48.0141 |  45.2711 |   0.48705  |   6.47866 |   0.247062   |   0.116994  |   0.0381615 |   0.0512858 |   0.343346 |
| Qtau   | baseline     | nan       | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan          | nan         | nan         | nan         | nan        |
| Qtau   | detailed     | nan       | nan       | nan        | nan        | nan      | nan      | nan      | nan        | nan       | nan          | nan         | nan         | nan         | nan        |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![CM-BEM_AU-Preston_Datasheet.png](CM-BEM_AU-Preston_Datasheet.png)](CM-BEM_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![CM-BEM_AU-Preston_Distributions.png](CM-BEM_AU-Preston_Distributions.png)](CM-BEM_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![CM-BEM_AU-Preston_closure_baseline.png](CM-BEM_AU-Preston_closure_baseline.png)](CM-BEM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![CM-BEM_AU-Preston_closure_detailed.png](CM-BEM_AU-Preston_closure_detailed.png)](CM-BEM_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![CM-BEM_AU-Preston_subset_LWup.png](CM-BEM_AU-Preston_subset_LWup.png)](CM-BEM_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![CM-BEM_AU-Preston_subset_Qh.png](CM-BEM_AU-Preston_subset_Qh.png)](CM-BEM_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![CM-BEM_AU-Preston_subset_Qle.png](CM-BEM_AU-Preston_subset_Qle.png)](CM-BEM_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![CM-BEM_AU-Preston_subset_SWup.png](CM-BEM_AU-Preston_subset_SWup.png)](CM-BEM_AU-Preston_subset_SWup.png)

### out of range: baseline

 - CM-BEM SWnet min value of -0.3225 is less than expected 0.0 [W/m2]
 - CM-BEM Qanth_Qle min value of -1.9800 is less than expected 0.0 [W/m2]
 - CM-BEM EvapF max value of 16.8784 is greater than expected 1.0 [1]
 - CM-BEM EvapF min value of -17.9642 is less than expected 0.0 [1]

### out of range: detailed

 - CM-BEM SWnet min value of -0.2861 is less than expected 0.0 [W/m2]
 - CM-BEM Qanth_Qle min value of -0.5000 is less than expected 0.0 [W/m2]
 - CM-BEM EvapF max value of 193.4554 is greater than expected 1.0 [1]
 - CM-BEM EvapF min value of -39.6275 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

