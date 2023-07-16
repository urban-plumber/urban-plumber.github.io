# US-Minneapolis1: TEB-SPARTCS

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](TEB-SPARTCS_US-Minneapolis1_baseline_attrs.md)
- [Detailed](TEB-SPARTCS_US-Minneapolis1_detailed_attrs.md)

### Error metrics

| flux     | experiment   |       MAE |        MBE |      nSD |        R |        5th |       95th |      RMSE |    cRMSE |      AMBE |     1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:---------|:-------------|----------:|-----------:|---------:|---------:|-----------:|-----------:|----------:|---------:|----------:|----------:|-----------:|------------:|------------:|----------:|
| SWup     | baseline     | 47.4187   | -47.012    | 0.46998  | 0.922977 |  2.36649   | 176.249    | 74.3203   | 0.594408 | 47.012    | 0.530021  | 0.0770234  |   0.427022  |  0.751977   | 0.231371  |
| SWup     | detailed     | 40.6044   | -39.8514   | 0.551649 | 0.956025 |  2.31085   | 147.973    | 62.6757   | 0.499536 | 39.8514   | 0.448352  | 0.0439747  |   0.256687  |  0.43371    | 0.213137  |
| LWup     | baseline     | 11.2013   |   8.92508  | 1.09591  | 0.992251 |  0.906934  |  23.7954   | 14.7406   | 0.161808 |  8.92508  | 0.0959058 | 0.00774863 |   0.0884135 |  0.0907469  | 0.0788239 |
| LWup     | detailed     | 10.5806   |   5.9627   | 1.07235  | 0.988467 |  2.17806   |  10.7857   | 13.896    | 0.17312  |  5.9627   | 0.0723497 | 0.0115334  |   0.361789  |  0.40634    | 0.0850596 |
| Qle      | baseline     | 19.6397   |   0.253535 | 0.885924 | 0.735119 |  4.35262   |  10.2393   | 38.5742   | 0.694509 |  0.253535 | 0.114076  | 0.264881   |   0.0119884 |  0.206565   | 0.119736  |
| Qle      | detailed     | 26.9175   |   3.00241  | 1.26285  | 0.592174 |  9.14141   |   2.28914  | 58.306    | 1.0484   |  3.00241  | 0.262853  | 0.407826   |   0.777526  |  2.47986    | 0.110875  |
| Qh       | baseline     | 51.6922   |  46.6906   | 1.16354  | 0.879839 | 27.1463    |  74.1728   | 65.8978   | 0.553505 | 46.6906   | 0.163536  | 0.120161   |   0.0278777 |  0.00700393 | 0.325038  |
| Qh       | detailed     | 34.1525   |  18.4504   | 1.06479  | 0.848725 | 19.502     |  20.7869   | 51.4194   | 0.571269 | 18.4504   | 0.064787  | 0.151275   |   0.0263084 |  1.04085    | 0.24836   |
| Qg       | baseline     | 34.2162   |  -1.23517  | 1.63564  | 0.767396 | 38.9316    |  42.9557   | 48.2083   | 1.07933  |  1.23517  | 0.635627  | 0.232604   |   0.48858   |  0.898157   | 0.330288  |
| Qg       | detailed     | 35.938    |  -0.082526 | 1.6746   | 0.709474 | 27.6831    |  54.1691   | 53.3589   | 1.19503  |  0.082526 | 0.674584  | 0.290526   |   0.0394906 |  0.0504265  | 0.2782    |
| Qtau     | baseline     |  0.128625 |   0.100641 | 1.16384  | 0.868713 |  0.049856  |   0.188999 |  0.16732  | 0.576574 |  0.100641 | 0.163838  | 0.131287   |   0.0827151 |  0.276962   | 0.185812  |
| Qtau     | detailed     |  0.152536 |   0.130401 | 1.43761  | 0.882291 |  0.0138865 |   0.347096 |  0.213277 | 0.72797  |  0.130401 | 0.437607  | 0.117709   |   0.0947901 |  0.277285   | 0.179641  |
| SoilTemp | baseline     |  4.5381   |  -2.50814  | 1.27341  | 0.931493 | 10.5508    |   2.37887  |  5.83656  | 0.499229 |  2.50814  | 0.273415  | 0.0685072  |   5.71202   |  0.476226   | 0.231675  |
| SoilTemp | detailed     |  5.06097  |  -3.26688  | 1.28382  | 0.929215 | 10.9319    |   2.10373  |  6.31697  | 0.512155 |  3.26688  | 0.283821  | 0.0707851  |   4.01789   |  0.437127   | 0.234318  |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![TEB-SPARTCS_US-Minneapolis1_subset_SWup_v0-9.png](TEB-SPARTCS_US-Minneapolis1_subset_SWup_v0-9.png)](TEB-SPARTCS_US-Minneapolis1_subset_SWup_v0-9.png)

### out of range: baseline


### out of range: detailed

 - TEB-SPARTCS Qh max value of 681.7767 is greater than expected 600.0 [W/m2]
 - TEB-SPARTCS Qh min value of -646.5537 is less than expected -600.0 [W/m2]
 - TEB-SPARTCS Qle max value of 1075.3821 is greater than expected 700.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

