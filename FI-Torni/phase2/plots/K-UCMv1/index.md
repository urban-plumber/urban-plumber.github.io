# FI-Torni: K-UCMv1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](K-UCMv1_FI-Torni_baseline_attrs.md)
- [Detailed](K-UCMv1_FI-Torni_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |      MBE |        nSD |          R |       5th |     95th |     RMSE |      cRMSE |     AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |    Overlap |
|:-------|:-------------|---------:|---------:|-----------:|-----------:|----------:|---------:|---------:|-----------:|---------:|------------:|------------:|------------:|------------:|-----------:|
| SWup   | baseline     | nan      | nan      | nan        | nan        | nan       | nan      | nan      | nan        | nan      | nan         | nan         | nan         |  nan        | nan        |
| SWup   | detailed     |  12.4606 | -11.7988 |   0.639093 |   0.935482 |   0.8806  |  26.8459 |  17.2833 |   0.461216 |  11.7988 |   0.360906  |   0.064518  |   0.387654  |    0.33417  |   0.168596 |
| LWup   | baseline     | nan      | nan      | nan        | nan        | nan       | nan      | nan      | nan        | nan      | nan         | nan         | nan         |  nan        | nan        |
| LWup   | detailed     |  11.4993 |  10.9875 |   1.08217  |   0.989058 |   5.74772 |  16.1572 |  13.9196 |   0.174454 |  10.9875 |   0.0821726 |   0.0109417 |   0.0112462 |    0.422087 |   0.120588 |
| Qle    | baseline     | nan      | nan      | nan        | nan        | nan       | nan      | nan      | nan        | nan      | nan         | nan         | nan         |  nan        | nan        |
| Qle    | detailed     |  16.1741 | -10.2268 |   0.409978 |   0.553194 |   6.671   |  37.1341 |  28.624  |   0.845274 |  10.2268 |   0.590022  |   0.446806  |   0.181962  |    0.501934 |   0.393703 |
| Qh     | baseline     | nan      | nan      | nan        | nan        | nan       | nan      | nan      | nan        | nan      | nan         | nan         | nan         |  nan        | nan        |
| Qh     | detailed     |  43.3828 | -30.021  |   0.901871 |   0.729255 |  24.7893  |  35.0702 |  58.198  |   0.705679 |  30.021  |   0.0981307 |   0.270745  |   0.261521  |    2.22842  |   0.289242 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![K-UCMv1_FI-Torni_subset_SWup_v0-9.png](K-UCMv1_FI-Torni_subset_SWup_v0-9.png)](K-UCMv1_FI-Torni_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - K-UCMv1 Qstor min value of -1658.2291 is less than expected -800.0 [W/m2]
 - K-UCMv1 Qh max value of 1389.1405 is greater than expected 600.0 [W/m2]
 - K-UCMv1 SWnet min value of -0.9085 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

