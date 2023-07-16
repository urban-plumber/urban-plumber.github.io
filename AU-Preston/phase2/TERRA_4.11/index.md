# AU-Preston: TERRA_4.11

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TERRA_4.11_AU-Preston_baseline_attrs.md)
- [Detailed](TERRA_4.11_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |         MBE |        nSD |          R |        5th |      95th |      RMSE |       cRMSE |        AMBE |       1-nSD |          1-R |    nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|------------:|-----------:|-----------:|-----------:|----------:|----------:|------------:|------------:|------------:|-------------:|-------------:|------------:|------------:|
| SWup   | baseline     |  15.7443  | -15.7442    |   0.722008 |   0.996801 |   0.881603 |  40.3922  |  20.6317  |   0.286181  |  15.7442    |   0.277992  |   0.00319926 |   0.0137121  |   0.0254187 |   0.0860945 |
| SWup   | detailed     |   2.73804 |   0.0371685 |   1.01376  |   0.9968   |   0.534408 |   2.27944 |   3.80737 |   0.0817136 |   0.0371685 |   0.0137593 |   0.00319988 |   0.0136204  |   0.0253237 |   0.0631653 |
| LWup   | baseline     |  34.0394  | -33.4997    |   0.813448 |   0.843495 |  38.1527   |  60.6103  |  40.4156  |   0.537977  |  33.4997    |   0.186553  |   0.156505   |   0.667149   |   0.73637   |   0.294374  |
| LWup   | detailed     |   9.1883  |   7.67887   |   1.14287  |   0.986835 |   1.34209  |  23.4265  |  12.1723  |   0.224727  |   7.67887   |   0.142866  |   0.0131648  |   0.076382   |   0.171041  |   0.0831017 |
| Qle    | baseline     |  23.4714  | -14.6154    |   0.439876 |   0.650172 |  10.3908   |  65.3553  |  41.1698  |   0.788353  |  14.6154    |   0.560125  |   0.349828   |   0.00731007 |   0.412699  |   0.288816  |
| Qle    | detailed     |  23.454   | -15.0124    |   0.44615  |   0.637063 |  10.1975   |  64.2704  |  41.574   |   0.794103  |  15.0124    |   0.553851  |   0.362937   |   0.0271611  |   0.484478  |   0.30038   |
| Qh     | baseline     |  82.7653  |  82.3336    |   1.42893  |   0.932996 |  57.9849   | 183.722   |  99.7054  |   0.612759  |  82.3336    |   0.428934  |   0.0670042  |   0.0131459  |   0.0732479 |   0.592541  |
| Qh     | detailed     |  31.047   |  27.1652    |   1.32243  |   0.954186 |   9.15183  | 106.908   |  51.3235  |   0.474484  |  27.1652    |   0.322433  |   0.0458143  |   0.0288014  |   0.0428018 |   0.226493  |
| Qtau   | baseline     | nan       | nan         | nan        | nan        | nan        | nan       | nan       | nan         | nan         | nan         | nan          | nan          | nan         | nan         |
| Qtau   | detailed     | nan       | nan         | nan        | nan        | nan        | nan       | nan       | nan         | nan         | nan         | nan          | nan          | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TERRA_4.11_AU-Preston_subset_SWup_v0-9.png](TERRA_4.11_AU-Preston_subset_SWup_v0-9.png)](TERRA_4.11_AU-Preston_subset_SWup_v0-9.png)

### out of range: baseline

 - TERRA_4.11 Qh max value of 726.9598 is greater than expected 600.0 [W/m2]
 - TERRA_4.11 SWup min value of -0.0009 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.0503 is less than expected 0.0 [1]

### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

