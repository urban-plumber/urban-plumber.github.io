# JP-Yoyogi: CM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](CM_JP-Yoyogi_baseline_attrs.md)
- [Detailed](CM_JP-Yoyogi_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |       MBE |       nSD |          R |       5th |    95th |     RMSE |      cRMSE |      AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |    Overlap |
|:-------|:-------------|---------:|----------:|----------:|-----------:|----------:|--------:|---------:|-----------:|----------:|------------:|------------:|------------:|------------:|-----------:|
| SWup   | baseline     | nan      | nan       | nan       | nan        | nan       | nan     | nan      | nan        | nan       | nan         | nan         |  nan        |  nan        | nan        |
| SWup   | detailed     | 259.674  | 259.669   |   7.83825 |   0.965256 |   5.94867 | 714.223 | 346.317  |   6.87796  | 259.669   |   6.83824   |   0.0347444 |    0.212102 |    0.310036 |   0.428574 |
| LWup   | baseline     | nan      | nan       | nan       | nan        | nan       | nan     | nan      | nan        | nan       | nan         | nan         |  nan        |  nan        | nan        |
| LWup   | detailed     |  53.738  | -53.7358  |   1.20298 |   0.838449 |  80.266   |  51.173 |  63.1706 |   0.655657 |  53.7358  |   0.202977  |   0.161551  |    1.86609  |    0.497548 |   0.317961 |
| Qle    | baseline     | nan      | nan       | nan       | nan        | nan       | nan     | nan      | nan        | nan       | nan         | nan         |  nan        |  nan        | nan        |
| Qle    | detailed     |  24.9627 |   5.01544 |   1.06599 |   0.57356  |   5.16981 |  10.62  |  36.8032 |   0.955779 |   5.01544 |   0.0659854 |   0.42644   |    0.366835 |    0.562629 |   0.192113 |
| Qh     | baseline     | nan      | nan       | nan       | nan        | nan       | nan     | nan      | nan        | nan       | nan         | nan         |  nan        |  nan        | nan        |
| Qh     | detailed     |  35.1803 |  11.1181  |   1.29856 |   0.810213 |   5.0366  |  57.991 |  51.5994 |   0.762913 |  11.1181  |   0.298558  |   0.189787  |    0.131275 |    0.233941 |   0.181342 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![CM_JP-Yoyogi_subset_SWup_v0-9.png](CM_JP-Yoyogi_subset_SWup_v0-9.png)](CM_JP-Yoyogi_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - CM SWnet min value of -0.0050 is less than expected 0.0 [W/m2]
 - CM Albedo max value of 1.0001 is greater than expected 1.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

