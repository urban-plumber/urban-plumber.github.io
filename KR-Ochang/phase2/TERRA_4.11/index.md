# KR-Ochang: TERRA_4.11

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TERRA_4.11_KR-Ochang_baseline_attrs.md)
- [Detailed](TERRA_4.11_KR-Ochang_detailed_attrs.md)

### Error metrics

| flux   | experiment   |      MAE |        MBE |      nSD |        R |      5th |      95th |    RMSE |    cRMSE |      AMBE |     1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|---------:|-----------:|---------:|---------:|---------:|----------:|--------:|---------:|----------:|----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     | 15.9804  | -15.9438   | 0.656912 | 0.946112 |  1.89951 | 41.4754   | 26.2916 | 0.434176 | 15.9438   | 0.343089  | 0.053888   |   0.557338  |   1.22232   | 0.108509  |
| SWup   | detailed     |  6.60975 |  -3.09657  | 0.879363 | 0.947027 |  1.70624 |  8.60301  | 16.1036 | 0.328205 |  3.09657  | 0.120639  | 0.0529732  |   0.559764  |   1.22394   | 0.090162  |
| LWup   | baseline     | 15.9591  | -14.8034   | 1.03775  | 0.975613 | 20.9527  | 15.2757   | 20.7021 | 0.228124 | 14.8034   | 0.0377441 | 0.0243874  |   0.0578998 |   0.0554592 | 0.0870745 |
| LWup   | detailed     | 11.181   |  10.7124   | 1.11361  | 0.990911 |  3.75919 | 30.6856   | 15.7533 | 0.18207  | 10.7124   | 0.113606  | 0.00908888 |   3.3778    |   0.289476  | 0.0699435 |
| Qle    | baseline     | 22.5206  |  -0.596966 | 0.956831 | 0.736656 |  3.40968 |  0.711624 | 39.3567 | 0.711207 |  0.596966 | 0.0431694 | 0.263344   |   0.271502  |   0.735048  | 0.219584  |
| Qle    | detailed     | 23.2891  |  -1.08102  | 0.963744 | 0.718521 |  3.33189 |  0.236069 | 40.8196 | 0.737469 |  1.08102  | 0.0362572 | 0.281479   |   0.254667  |   0.70101   | 0.2956    |
| Qh     | baseline     | 50.1926  |  48.4018   | 1.18841  | 0.898007 | 35.1784  | 75.9124   | 59.9519 | 0.527181 | 48.4018   | 0.188413  | 0.101993   |   0.140786  |   0.39996   | 0.609336  |
| Qh     | detailed     | 25.396   |  19.3913   | 1.16146  | 0.897266 | 18.0735  | 47.3789   | 39.5984 | 0.5145   | 19.3913   | 0.161457  | 0.102734   |   0.0731858 |   0.279043  | 0.435188  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TERRA_4.11_KR-Ochang_subset_SWup_v0-9.png](TERRA_4.11_KR-Ochang_subset_SWup_v0-9.png)](TERRA_4.11_KR-Ochang_subset_SWup_v0-9.png)

### out of range: baseline

 - TERRA_4.11 SWup min value of -0.0016 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.1025 is less than expected 0.0 [1]

### out of range: detailed

 - TERRA_4.11 SWup min value of -0.0008 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.0526 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

