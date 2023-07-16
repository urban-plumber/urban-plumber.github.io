# GR-HECKOR: UCLEM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](UCLEM_GR-HECKOR_baseline_attrs.md)
- [Detailed](UCLEM_GR-HECKOR_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |        MBE |      nSD |        R |       5th |       95th |      RMSE |    cRMSE |      AMBE |     1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|-----------:|---------:|---------:|----------:|-----------:|----------:|---------:|----------:|----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     | 22.4051   | -22.4035   | 0.788385 | 0.990766 |  3.15094  |  48.6493   | 26.9325   | 0.243599 | 22.4035   | 0.211615  | 0.00923395 |   0.300168  |   0.172568  |  0.13027  |
| SWup   | detailed     |  8.73732  |  -8.25634  | 0.974775 | 0.992791 |  2.84854  |  12.6225   | 11.1124   | 0.121206 |  8.25634  | 0.0252252 | 0.00720913 |   0.0121459 |   0.110615  |  0.107141 |
| LWup   | baseline     | 38.5812   |  38.4028   | 1.65513  | 0.963928 |  7.62121  | 103.593    | 50.198    | 0.740676 | 38.4028   | 0.655124  | 0.0360723  |   0.826032  |   0.727597  |  0.174649 |
| LWup   | detailed     | 29.3348   |  25.683    | 1.67111  | 0.946807 |  1.32369  |  93.3251   | 43.0843   | 0.792572 | 25.683    | 0.671107  | 0.0531926  |   0.999944  |   0.77069   |  0.114337 |
| Qle    | baseline     | 26.3781   | -17.8906   | 0.928144 | 0.130281 |  3.30603  |  59.6695   | 48.4972   | 1.27264  | 17.8906   | 0.0718557 | 0.869719   |   6.30203   |  42.41      |  0.548418 |
| Qle    | detailed     | 24.8418   | -15.4997   | 1.02462  | 0.179198 |  2.82313  |  61.5203   | 48.4892   | 1.29716  | 15.4997   | 0.0246196 | 0.820802   |   6.07403   |  36.4426    |  0.400167 |
| Qh     | baseline     | 26.1254   |   5.29566  | 0.958956 | 0.930041 | 18.1694   |  10.3324   | 39.3776   | 0.368591 |  5.29566  | 0.0410437 | 0.0699588  |   0.101987  |   0.332635  |  0.211636 |
| Qh     | detailed     | 30.0862   |  15.8489   | 1.06213  | 0.928364 | 22.6928   |  43.9342   | 44.7195   | 0.395012 | 15.8489   | 0.062134  | 0.071636   |   0.0714273 |   0.0213034 |  0.295307 |
| Qtau   | baseline     |  0.207871 |  -0.198058 | 0.510167 | 0.86074  |  0.012804 |   0.617923 |  0.330231 | 0.618085 |  0.198058 | 0.489834  | 0.13926    |   0.94384   |   8.08663   |  0.225611 |
| Qtau   | detailed     |  0.314773 |  -0.312818 | 0.303785 | 0.784736 |  0.021204 |   0.901423 |  0.458644 | 0.78454  |  0.312818 | 0.696215  | 0.215264   |   3.97843   |  54.1675    |  0.417368 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![UCLEM_GR-HECKOR_subset_SWup_v0-9.png](UCLEM_GR-HECKOR_subset_SWup_v0-9.png)](UCLEM_GR-HECKOR_subset_SWup_v0-9.png)

### out of range: baseline

 - UCLEM Qstor min value of -1061.3257 is less than expected -800.0 [W/m2]
 - UCLEM Qle max value of 1570.7566 is greater than expected 700.0 [W/m2]

### out of range: detailed

 - UCLEM Qstor min value of -900.1288 is less than expected -800.0 [W/m2]
 - UCLEM Qle max value of 1577.7567 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

