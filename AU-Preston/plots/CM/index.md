# AU-Preston: CM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |      MAE |        MBE |        nSD |          R |    5th |   95th |      cRMSE |       AMBE |      1-nSD |          1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|---------:|-----------:|-----------:|-----------:|-------:|-------:|-----------:|-----------:|-----------:|-------------:|------------:|------------:|------------:|
| SWup   | baseline     |  30.3112 | -30.3112   |   0.450598 |   0.99671  |   1.17 |  80.12 |   0.552094 |  30.3112   |   0.549402 |   0.00329004 |   0.0118031 |   0.0199789 |   0.117089  |
| SWup   | detailed     |  10.9462 | -10.9384   |   0.809875 |   0.99671  |   0.76 |  27.58 |   0.203658 |  10.9384   |   0.190125 |   0.00329009 |   0.0117964 |   0.0199631 |   0.0760676 |
| LWup   | baseline     |  16.7231 |  14.4722   |   1.34857  |   0.953377 |   4.76 |  55.47 |   0.497243 |  14.4722   |   0.348569 |   0.0466234  |   0.172409  |   0.0824588 |   0.0885482 |
| LWup   | detailed     |  19.2497 |  17.1675   |   1.51054  |   0.956917 |   2.42 |  75.2  |   0.625148 |  17.1675   |   0.510541 |   0.0430832  |   0.262653  |   0.390757  |   0.0818837 |
| Qle    | baseline     |  25.4946 | -10.3061   |   0.588147 |   0.58959  |   8.08 |  40.94 |   0.807704 |  10.3061   |   0.411853 |   0.41041    |   0.0159798 |   0.465612  |   0.194154  |
| Qle    | detailed     |  25.929  | -11.5732   |   0.603494 |   0.529955 |  12.11 |  42.23 |   0.851208 |  11.5732   |   0.396506 |   0.470045   |   0.265955  |   0.130912  |   0.290491  |
| Qh     | baseline     |  32.185  |   4.21072  |   0.697652 |   0.882921 |  32.77 |  56.1  |   0.504753 |   4.21072  |   0.302348 |   0.117079   |   0.0147222 |   0.106703  |   0.330265  |
| Qh     | detailed     |  27.7335 |   0.412447 |   0.734795 |   0.901571 |  29.74 |  52.93 |   0.463664 |   0.412447 |   0.265205 |   0.0984292  |   0.0710226 |   0.119719  |   0.240415  |
| Qtau   | baseline     | nan      | nan        | nan        | nan        | nan    | nan    | nan        | nan        | nan        | nan          | nan         | nan         | nan         |
| Qtau   | detailed     | nan      | nan        | nan        | nan        | nan    | nan    | nan        | nan        | nan        | nan          | nan         | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![CM_AU-Preston_Datasheet.png](CM_AU-Preston_Datasheet.png)](CM_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![CM_AU-Preston_Distributions.png](CM_AU-Preston_Distributions.png)](CM_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![CM_AU-Preston_closure_baseline.png](CM_AU-Preston_closure_baseline.png)](CM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![CM_AU-Preston_closure_detailed.png](CM_AU-Preston_closure_detailed.png)](CM_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![CM_AU-Preston_subset_LWup.png](CM_AU-Preston_subset_LWup.png)](CM_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![CM_AU-Preston_subset_Qh.png](CM_AU-Preston_subset_Qh.png)](CM_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![CM_AU-Preston_subset_Qle.png](CM_AU-Preston_subset_Qle.png)](CM_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![CM_AU-Preston_subset_SWup.png](CM_AU-Preston_subset_SWup.png)](CM_AU-Preston_subset_SWup.png)

### out of range: baseline

 - CM Qg max value of 513.7900 is greater than expected 500.0 [W/m2]
 - CM EvapF max value of 5.8462 is greater than expected 1.0 [1]
 - CM EvapF min value of -9.1905 is less than expected 0.0 [1]

### out of range: detailed

 - CM EvapF max value of 39.9310 is greater than expected 1.0 [1]
 - CM EvapF min value of -9.3846 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

