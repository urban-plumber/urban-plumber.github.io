# US-Minneapolis2: TEB-CNRM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TEB-CNRM_US-Minneapolis2_baseline_attrs.md)
- [Detailed](TEB-CNRM_US-Minneapolis2_detailed_attrs.md)

### Error metrics

| flux     | experiment   |        MAE |         MBE |      nSD |        R |         5th |       95th |      RMSE |    cRMSE |       AMBE |      1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:---------|:-------------|-----------:|------------:|---------:|---------:|------------:|-----------:|----------:|---------:|-----------:|-----------:|-----------:|------------:|------------:|----------:|
| SWup     | baseline     | 43.3129    | -42.5484    | 0.487686 | 0.836114 |  2.35767    | 164.285    | 75.9656   | 0.649858 | 42.5484    | 0.512314   | 0.163886   |  0.623439   |   1.09073   | 0.181725  |
| SWup     | detailed     | 39.6217    | -38.1119    | 0.522816 | 0.838221 |  2.33825    | 153.848    | 71.9323   | 0.629973 | 38.1119    | 0.477184   | 0.161779   |  0.630246   |   1.09268   | 0.153813  |
| LWup     | baseline     |  9.35156   |   7.37694   | 0.997567 | 0.991433 | 12.9341     |   9.4888   | 12.0123   | 0.130757 |  7.37694   | 0.00243409 | 0.00856653 |  0.29332    |   0.111836  | 0.0750637 |
| LWup     | detailed     |  7.85806   |   1.60194   | 0.949096 | 0.989747 | 10.3584     |   5.31291  | 10.8857   | 0.148506 |  1.60194   | 0.0509049  | 0.0102533  |  0.00443421 |   0.288277  | 0.0644998 |
| Qle      | baseline     | 28.1003    |  -0.629127  | 1.00812  | 0.759907 |  3.39643    |   6.15191  | 53.6457   | 0.695811 |  0.629127  | 0.00812411 | 0.240093   |  0.021401   |   0.108061  | 0.130979  |
| Qle      | detailed     | 33.4518    |   1.62816   | 1.25632  | 0.685524 |  2.71748    |  20.2248   | 71.3393   | 0.925129 |  1.62816   | 0.256319   | 0.314476   |  0.518754   |   1.76764   | 0.217957  |
| Qh       | baseline     | 40.3288    |  29.3082    | 1.39807  | 0.810536 |  9.01391    |  87.0588   | 60.2099   | 0.829594 | 29.3082    | 0.398068   | 0.189464   |  0.270602   |   0.151778  | 0.194847  |
| Qh       | detailed     | 42.5853    |  20.8059    | 1.63709  | 0.738491 | 16.3771     |  66.5675   | 74.2015   | 1.12344  | 20.8059    | 0.637094   | 0.261509   |  0.388785   |   1.91325   | 0.234732  |
| Qg       | baseline     | 33.917     |  -0.642849  | 1.58193  | 0.729691 | 39.4873     |  33.3865   | 48.7912   | 1.09264  |  0.642849  | 0.581921   | 0.270309   |  0.549901   |   0.876855  | 0.320472  |
| Qg       | detailed     | 41.7503    |   0.373665  | 1.75993  | 0.536908 | 32.7856     |  45.453    | 66.3414   | 1.48577  |  0.373665  | 0.759918   | 0.463092   |  0.0395304  |   0.504126  | 0.271057  |
| Qtau     | baseline     |  0.0943351 |  -0.0240332 | 0.748546 | 0.859368 |  0.0181745  |   0.167603 |  0.143243 | 0.523228 |  0.0240332 | 0.251455   | 0.140632   |  0.128789   |   0.270651  | 0.143411  |
| Qtau     | detailed     |  0.121721  |   0.0822214 | 1.23791  | 0.89322  |  0.00678858 |   0.181277 |  0.173607 | 0.566539 |  0.0822214 | 0.237904   | 0.10678    |  0.0451738  |   0.0835019 | 0.152745  |
| SoilTemp | baseline     |  4.80614   |  -2.70976   | 1.27017  | 0.92564  | 10.3949     |   2.64784  |  6.04387  | 0.511753 |  2.70976   | 0.270172   | 0.07436    |  4.41773    |   0.499925  | 0.240176  |
| SoilTemp | detailed     |  5.29813   |  -3.07736   | 1.29948  | 0.917006 | 10.9599     |   2.9412   |  6.59569  | 0.55262  |  3.07736   | 0.299486   | 0.0829939  |  3.66076    |   0.46605   | 0.240334  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TEB-CNRM_US-Minneapolis2_subset_SWup_v0-9.png](TEB-CNRM_US-Minneapolis2_subset_SWup_v0-9.png)](TEB-CNRM_US-Minneapolis2_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - TEB-CNRM Qh max value of 909.4695 is greater than expected 600.0 [W/m2]
 - TEB-CNRM Qh min value of -765.7489 is less than expected -600.0 [W/m2]
 - TEB-CNRM Qle max value of 1235.4586 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

