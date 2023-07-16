# UK-Swindon: SNUUCM

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](SNUUCM_UK-Swindon_baseline_attrs.md)
- [Detailed](SNUUCM_UK-Swindon_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |        MBE |        nSD |          R |        5th |       95th |      RMSE |      cRMSE |       AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|-----------:|-----------:|-----------:|-----------:|-----------:|----------:|-----------:|-----------:|------------:|------------:|------------:|------------:|------------:|
| SWup   | baseline     |   3.29556 |   1.95331  |   1.03592  |   0.987674 |   0.786864 |   2.04289  |   5.27823 |   0.163795 |   1.95331  |   0.0359216 |   0.0123265 |    0.116325 |    0.523356 |   0.0876161 |
| SWup   | detailed     |   2.93863 |   1.52317  |   1.02591  |   0.989155 |   0.792895 |   1.45157  |   4.78164 |   0.151404 |   1.52317  |   0.0259145 |   0.0108448 |    0.111031 |    0.509798 |   0.0829295 |
| LWup   | baseline     |  15.4807  | -13.5006   |   1.23232  |   0.987263 |  19.8951   |   6.93842  |  16.8727  |   0.292173 |  13.5006   |   0.232318  |   0.0127372 |    0.671694 |    3.13696  |   0.225819  |
| LWup   | detailed     |  16.6973  |  -8.05332  |   1.44058  |   0.973346 |  20.939    |  30.4229   |  19.7455  |   0.520483 |   8.05332  |   0.440575  |   0.0266541 |    1.11752  |    6.87778  |   0.227266  |
| Qle    | baseline     |  13.1928  |   0.168074 |   1.20738  |   0.884766 |   1.84003  |  24.8577   |  22.87    |   0.566806 |   0.168074 |   0.207381  |   0.115234  |    0.177658 |    0.324593 |   0.202121  |
| Qle    | detailed     |  13.9677  |  -5.16312  |   1.06142  |   0.846099 |   2.06068  |   0.161697 |  23.7625  |   0.574871 |   5.16312  |   0.0614163 |   0.153901  |    0.441097 |    1.36448  |   0.239452  |
| Qh     | baseline     |  14.2831  |   5.46881  |   0.944856 |   0.950423 |  13.8942   |   2.57066  |  19.763   |   0.311011 |   5.46881  |   0.0551443 |   0.0495774 |    0.105594 |    0.193068 |   0.170321  |
| Qh     | detailed     |  15.9822  |   8.144    |   0.92338  |   0.944405 |  19.7789   |   1.72308  |  21.7036  |   0.329457 |   8.144    |   0.0766202 |   0.0555952 |    0.144984 |    0.291126 |   0.238727  |
| Qtau   | baseline     | nan       | nan        | nan        | nan        | nan        | nan        | nan       | nan        | nan        | nan         | nan         |  nan        |  nan        | nan         |
| Qtau   | detailed     | nan       | nan        | nan        | nan        | nan        | nan        | nan       | nan        | nan        | nan         | nan         |  nan        |  nan        | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![SNUUCM_UK-Swindon_subset_SWup_v0-9.png](SNUUCM_UK-Swindon_subset_SWup_v0-9.png)](SNUUCM_UK-Swindon_subset_SWup_v0-9.png)

### out of range: baseline

 - SNUUCM Qstor min value of -4363.0371 is less than expected -800.0 [W/m2]
 - SNUUCM Qle max value of 4302.1919 is greater than expected 700.0 [W/m2]

### out of range: detailed



[Link to variable definitions](../modelattrs/variable_definitions.md)

