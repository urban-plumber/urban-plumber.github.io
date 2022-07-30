# AU-Preston: TEB-READING

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Error metrics

| flux   | experiment   |       MAE |        MBE |        nSD |          R |        5th |      95th |      cRMSE |       AMBE |       1-nSD |          1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|-----------:|-----------:|-----------:|-----------:|----------:|-----------:|-----------:|------------:|-------------:|------------:|------------:|------------:|
| SWup   | baseline     |  15.9144  | -15.8887   |   0.693654 |   0.992093 |   0.63626  |  45.5636  |   0.323755 |  15.8887   |   0.306346  |   0.00790699 |   0.11558   |    0.238862 |   0.082293  |
| SWup   | detailed     |   4.09664 |  -2.35438  |   0.974257 |   0.99346  |   0.296749 |   3.2086  |   0.115782 |   2.35438  |   0.0257427 |   0.00653979 |   0.0685448 |    0.152968 |   0.0635286 |
| LWup   | baseline     |  17.1893  |  16.9646   |   1.33577  |   0.974485 |   5.33704  |  52.3766  |   0.425333 |  16.9646   |   0.335771  |   0.0255154  |   0.153448  |    0.201476 |   0.115673  |
| LWup   | detailed     |  12.3431  |   8.09146  |   1.24521  |   0.974491 |   1.24396  |  34.2622  |   0.351648 |   8.09146  |   0.24521   |   0.025509   |   0.128881  |    0.189967 |   0.0850568 |
| Qle    | baseline     |  24.8176  |  -0.714673 |   0.831185 |   0.629313 |  15.4177   |   1.98678 |   0.802943 |   0.714673 |   0.168815  |   0.370687   |   0.172637  |    0.281655 |   0.273801  |
| Qle    | detailed     |  27.7175  |   4.71376  |   1.0879   |   0.642651 |  12.3769   |  39.1248  |   0.886143 |   4.71376  |   0.0879021 |   0.357349   |   0.0328044 |    0.60439  |   0.288584  |
| Qh     | baseline     |  63.5022  |  62.3803   |   1.25532  |   0.932777 |  48.0554   | 128.776   |   0.483696 |  62.3803   |   0.255322  |   0.0672228  |   0.0339352 |    0.208254 |   0.518785  |
| Qh     | detailed     |  35.7733  |  32.2249   |   1.21041  |   0.940548 |  28.3986   |  93.9568  |   0.433814 |  32.2249   |   0.21041   |   0.0594519  |   0.0379373 |    0.282003 |   0.281112  |
| Qtau   | baseline     | nan       | nan        | nan        | nan        | nan        | nan       | nan        | nan        | nan         | nan          | nan         |  nan        | nan         |
| Qtau   | detailed     | nan       | nan        | nan        | nan        | nan        | nan       | nan        | nan        | nan         | nan          | nan         |  nan        | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="datasheet"></a>Datasheet
[![TEB-READING_AU-Preston_Datasheet.png](TEB-READING_AU-Preston_Datasheet.png)](TEB-READING_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![TEB-READING_AU-Preston_Distributions.png](TEB-READING_AU-Preston_Distributions.png)](TEB-READING_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![TEB-READING_AU-Preston_closure_baseline.png](TEB-READING_AU-Preston_closure_baseline.png)](TEB-READING_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![TEB-READING_AU-Preston_closure_detailed.png](TEB-READING_AU-Preston_closure_detailed.png)](TEB-READING_AU-Preston_closure_detailed.png)

### <a name="subset_lwup"></a>subset_LWup
[![TEB-READING_AU-Preston_subset_LWup.png](TEB-READING_AU-Preston_subset_LWup.png)](TEB-READING_AU-Preston_subset_LWup.png)

### <a name="subset_qh"></a>subset_Qh
[![TEB-READING_AU-Preston_subset_Qh.png](TEB-READING_AU-Preston_subset_Qh.png)](TEB-READING_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![TEB-READING_AU-Preston_subset_Qle.png](TEB-READING_AU-Preston_subset_Qle.png)](TEB-READING_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![TEB-READING_AU-Preston_subset_SWup.png](TEB-READING_AU-Preston_subset_SWup.png)](TEB-READING_AU-Preston_subset_SWup.png)

### out of range: baseline


### out of range: detailed

 - TEB-READING EvapF max value of 1.5953 is greater than expected 1.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

