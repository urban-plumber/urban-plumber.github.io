# SG-TelokKurau: TERRA_4.11

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TERRA_4.11_SG-TelokKurau_baseline_attrs.md)
- [Detailed](TERRA_4.11_SG-TelokKurau_detailed_attrs.md)

### Error metrics

| flux     | experiment   |       MAE |       MBE |        nSD |          R |        5th |      95th |      RMSE |      cRMSE |      AMBE |       1-nSD |          1-R |   nSkewness |   nKurtosis |    Overlap |
|:---------|:-------------|----------:|----------:|-----------:|-----------:|-----------:|----------:|----------:|-----------:|----------:|------------:|-------------:|------------:|------------:|-----------:|
| SWup     | baseline     |  28.7188  | -28.7177  |   0.56691  |   0.992164 |   2.34155  |  61.6455  |  35.1292  |   0.443229 |  28.7177  |   0.43309   |   0.0078359  |   0.169678  |   0.0672279 |   0.143143 |
| SWup     | detailed     |   4.33211 |  -1.03708 |   1.02584  |   0.992164 |   1.72185  |   2.63991 |   5.99719 |   0.1294   |   1.03708 |   0.0258374 |   0.00783595 |   0.169675  |   0.0672283 |   0.091703 |
| LWup     | baseline     |  30.3728  | -30.341   |   0.869038 |   0.845481 |  32.2687   |  41.6655  |  32.5468  |   0.534525 |  30.341   |   0.130962  |   0.154519   |   0.572013  |   2.93772   |   0.608143 |
| LWup     | detailed     |  18.1803  |  17.4144  |   1.8957   |   0.969436 |   0.124001 |  57.9767  |  27.3683  |   0.958209 |  17.4144  |   0.895704  |   0.0305638  |   0.0616736 |   1.2904    |   0.119942 |
| Qle      | baseline     |  23.4224  | -14.4426  |   0.593258 |   0.611102 |   2.8363   |  57.6363  |  39.4815  |   0.791753 |  14.4426  |   0.406742  |   0.388898   |   0.3427    |   0.984433  |   0.372733 |
| Qle      | detailed     |  22.2738  | -15.5069  |   0.567589 |   0.646407 |   2.86654  |  57.0221  |  38.8296  |   0.767053 |  15.5069  |   0.432411  |   0.353593   |   0.177476  |   0.329178  |   0.280488 |
| Qh       | baseline     | 187.071   | 187.071   |   1.57772  |   0.909743 | 116.994    | 283.449   | 199.227   |   0.78649  | 187.071   |   0.577724  |   0.0902568  |   0.283718  |   0.941564  |   0.744188 |
| Qh       | detailed     |  32.0026  |  25.5713  |   1.12184  |   0.925523 |  14.5574   |  47.587   |  45.1129  |   0.426556 |  25.5713  |   0.121845  |   0.0744772  |   0.0879921 |   0.382424  |   0.396231 |
| Qtau     | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan          | nan         | nan         | nan        |
| Qtau     | detailed     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan          | nan         | nan         | nan        |
| TairSurf | baseline     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan          | nan         | nan         | nan        |
| TairSurf | detailed     | nan       | nan       | nan        | nan        | nan        | nan       | nan       | nan        | nan       | nan         | nan          | nan         | nan         | nan        |
| SoilTemp | baseline     |   2.24566 |  -1.49077 |   1.42737  |   0.921046 |   2.66232  |   1.1754  |   2.59242 |   0.638781 |   1.49077 |   0.427373  |   0.0789541  |   0.141075  |   1.17889   |   0.457796 |
| SoilTemp | detailed     |   2.70103 |  -2.5851  |   1.14585  |   0.914994 |   3.11765  |   2.05189 |   3.01079 |   0.464847 |   2.5851  |   0.145854  |   0.0850061  |   0.300257  |   1.71234   |   0.476441 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TERRA_4.11_SG-TelokKurau_subset_SWup_v0-9.png](TERRA_4.11_SG-TelokKurau_subset_SWup_v0-9.png)](TERRA_4.11_SG-TelokKurau_subset_SWup_v0-9.png)

### out of range: baseline

 - TERRA_4.11 SWup min value of -0.0018 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Qh max value of 681.5639 is greater than expected 600.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.1084 is less than expected 0.0 [1]

### out of range: detailed

 - TERRA_4.11 SWup min value of -0.0003 is less than expected 0.0 [W/m2]
 - TERRA_4.11 Albedo min value of -0.0182 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

