# AU-Preston: CM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CM_AU-Preston_baseline_attrs.md)
- [Detailed](CM_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |        MBE |        nSD |          R |       5th |      95th |     RMSE |      cRMSE |       AMBE |        1-nSD |          1-R |    nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|---------:|-----------:|-----------:|-----------:|----------:|----------:|---------:|-----------:|-----------:|-------------:|-------------:|-------------:|------------:|------------:|
| SWup   | G11          |  67.5679 |  67.4673   |   2.02646  |   0.962251 |   0.39    | 127.02    |  84.6629 |   1.09846  |  67.4673   |   1.02646    |   0.0377489  |   0.575878   |   1.03821   |   0.13028   |
| SWup   | baseline     |  30.4102 | -30.4102   |   0.450797 |   0.996799 |   1.2     |  80.09    |  39.8222 |   0.551824 |  30.4102   |   0.549203   |   0.0032014  |   0.0135154  |   0.0253066 |   0.117758  |
| SWup   | detailed     |  10.9761 | -10.9682   |   0.810233 |   0.996799 |   0.78    |  27.52    |  14.4823 |   0.202976 |  10.9682   |   0.189767   |   0.00320145 |   0.0135089  |   0.0252912 |   0.0766651 |
| LWup   | G11          |  14.608  |  -0.217586 |   1.32563  |   0.950789 |   8.07999 |  39.95    |  20.4323 |   0.486319 |   0.217586 |   0.325629   |   0.0492112  |   0.284506   |   0.568324  |   0.155855  |
| LWup   | baseline     |  16.721  |  14.4667   |   1.34897  |   0.953418 |   4.76999 |  55.58    |  25.4265 |   0.49745  |  14.4667   |   0.348971   |   0.0465821  |   0.173362   |   0.0817039 |   0.0884795 |
| LWup   | detailed     |  19.2499 |  17.1657   |   1.511    |   0.956958 |   2.40999 |  75.23    |  31.3983 |   0.62546  |  17.1657   |   0.511005   |   0.0430422  |   0.263551   |   0.390856  |   0.0817986 |
| Qle    | G11          |  20.4921 |  -2.99295  |   0.775288 |   0.702079 |  10.66    |   6.98    |  35.1093 |   0.715852 |   2.99295  |   0.224712   |   0.297921   |   0.20424    |   0.234606  |   0.224279  |
| Qle    | baseline     |  23.2871 |  -9.42689  |   0.622742 |   0.637099 |   6.4     |  34.99    |  38.8243 |   0.770916 |   9.42689  |   0.377258   |   0.362901   |   0.0645726  |   0.371246  |   0.195736  |
| Qle    | detailed     |  23.9806 | -11.3998   |   0.626056 |   0.559407 |  10.47    |  39.65    |  42.1947 |   0.831568 |  11.3998   |   0.373944   |   0.440593   |   0.386374   |   0.135349  |   0.299535  |
| Qh     | G11          |  22.4577 | -10.4779   |   1.00481  |   0.947156 |  10.06    |   6.51001 |  31.6562 |   0.325913 |  10.4779   |   0.00480634 |   0.0528442  |   0.0634966  |   0.214314  |   0.239077  |
| Qh     | baseline     |  31.1809 |   4.60491  |   0.696733 |   0.889874 |  32.91    |  57.86    |  45.6252 |   0.495406 |   4.60491  |   0.303267   |   0.110126   |   0.00324451 |   0.0772247 |   0.337787  |
| Qh     | detailed     |  26.6094 |   1.12192  |   0.740085 |   0.90744  |  29.83    |  52.93    |  41.4563 |   0.452284 |   1.12192  |   0.259915   |   0.0925603  |   0.0722762  |   0.107559  |   0.240403  |
| Qtau   | baseline     | nan      | nan        | nan        | nan        | nan       | nan       | nan      | nan        | nan        | nan          | nan          | nan          | nan         | nan         |
| Qtau   | detailed     | nan      | nan        | nan        | nan        | nan       | nan       | nan      | nan        | nan        | nan          | nan          | nan          | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="albedo"></a>Albedo
[![CM_AU-Preston_Albedo.png](CM_AU-Preston_Albedo.png)](CM_AU-Preston_Albedo.png)

### <a name="datasheet"></a>Datasheet
[![CM_AU-Preston_Datasheet.png](CM_AU-Preston_Datasheet.png)](CM_AU-Preston_Datasheet.png)

### <a name="distributions"></a>Distributions
[![CM_AU-Preston_Distributions.png](CM_AU-Preston_Distributions.png)](CM_AU-Preston_Distributions.png)

### <a name="closure_baseline"></a>closure_baseline
[![CM_AU-Preston_closure_baseline.png](CM_AU-Preston_closure_baseline.png)](CM_AU-Preston_closure_baseline.png)

### <a name="closure_detailed"></a>closure_detailed
[![CM_AU-Preston_closure_detailed.png](CM_AU-Preston_closure_detailed.png)](CM_AU-Preston_closure_detailed.png)

### <a name="subset_qh"></a>subset_Qh
[![CM_AU-Preston_subset_Qh.png](CM_AU-Preston_subset_Qh.png)](CM_AU-Preston_subset_Qh.png)

### <a name="subset_qle"></a>subset_Qle
[![CM_AU-Preston_subset_Qle.png](CM_AU-Preston_subset_Qle.png)](CM_AU-Preston_subset_Qle.png)

### <a name="subset_swup"></a>subset_SWup
[![CM_AU-Preston_subset_SWup.png](CM_AU-Preston_subset_SWup.png)](CM_AU-Preston_subset_SWup.png)

### out of range: baseline


### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

