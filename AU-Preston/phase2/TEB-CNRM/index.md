# AU-Preston: TEB-CNRM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TEB-CNRM_AU-Preston_baseline_attrs.md)
- [Detailed](TEB-CNRM_AU-Preston_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |       MBE |      nSD |        R |        5th |       95th |      RMSE |     cRMSE |      AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|----------:|----------:|---------:|---------:|-----------:|-----------:|----------:|----------:|----------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  9.0815   | -9.00273  | 0.840886 | 0.995355 |  1.25155   |  23.2281   | 12.368    | 0.182015  |  9.00273  | 0.159114   | 0.00464519 |   0.0127625 |  0.00126913 | 0.086866  |
| SWup   | detailed     |  3.46693  | -0.546618 | 0.994327 | 0.995109 |  1.17464   |   1.09873  |  4.63488  | 0.0987843 |  0.546618 | 0.00567254 | 0.00489082 |   0.0311837 |  0.0395779  | 0.0766235 |
| LWup   | baseline     | 18.3787   | 10.7917   | 1.47709  | 0.964233 |  9.73604   |  60.2732   | 26.5541   | 0.577304  | 10.7917   | 0.477092   | 0.0357668  |   0.130058  |  0.131567   | 0.123226  |
| LWup   | detailed     |  8.79775  |  8.32421  | 1.03864  | 0.989246 |  5.31643   |  11.9534   | 10.554    | 0.154376  |  8.32421  | 0.0386407  | 0.0107538  |   0.027228  |  0.0981651  | 0.107154  |
| Qle    | baseline     | 26.1692   | -9.94136  | 0.722816 | 0.48581  |  9.73616   |  36.7253   | 45.3175   | 0.905627  |  9.94136  | 0.277184   | 0.51419    |   0.762098  |  1.30783    | 0.256777  |
| Qle    | detailed     | 24.881    | -1.01894  | 0.838222 | 0.578203 | 10.0547    |  14.8469   | 41.819    | 0.856324  |  1.01894  | 0.161779   | 0.421797   |   0.366892  |  0.302614   | 0.176943  |
| Qh     | baseline     | 38.7462   | 35.0111   | 1.34729  | 0.946304 | 22.4095    | 125.021    | 58.8233   | 0.515069  | 35.0111   | 0.347289   | 0.0536956  |   0.0454149 |  0.0224455  | 0.309209  |
| Qh     | detailed     | 24.7498   | 11.2412   | 1.08613  | 0.934503 |  7.13761   |  34.9402   | 37.2443   | 0.386905  | 11.2412   | 0.0861333  | 0.0654968  |   0.0802159 |  0.167782   | 0.161566  |
| Qtau   | baseline     |  0.200032 |  0.175646 | 1.30904  | 0.870187 |  0.0301379 |   0.350656 |  0.269372 | 0.659827  |  0.175646 | 0.309045   | 0.129813   |   0.196664  |  0.345921   | 0.235491  |
| Qtau   | detailed     |  0.404304 |  0.394175 | 1.95188  | 0.831895 |  0.038601  |   0.969105 |  0.552313 | 1.24993   |  0.394175 | 0.951885   | 0.168105   |   0.257015  |  0.473187   | 0.355465  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TEB-CNRM_AU-Preston_subset_SWup_v0-9.png](TEB-CNRM_AU-Preston_subset_SWup_v0-9.png)](TEB-CNRM_AU-Preston_subset_SWup_v0-9.png)

### out of range: baseline

 - TEB-CNRM Qh max value of 607.6433 is greater than expected 600.0 [W/m2]

### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

