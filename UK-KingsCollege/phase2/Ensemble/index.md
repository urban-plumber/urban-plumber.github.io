# UK-KingsCollege: Ensemble

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](Ensemble_UK-KingsCollege_baseline_attrs.md)
- [Detailed](Ensemble_UK-KingsCollege_detailed_attrs.md)

### Error metrics

| flux   | experiment   |        MAE |         MBE |      nSD |        R |        5th |       95th |      RMSE |    cRMSE |       AMBE |     1-nSD |        1-R |   nSkewness |   nKurtosis |   Overlap |
|:-------|:-------------|-----------:|------------:|---------:|---------:|-----------:|-----------:|----------:|---------:|-----------:|----------:|-----------:|------------:|------------:|----------:|
| SWup   | baseline     |  6.8085    |   6.19188   | 1.24365  | 0.987131 |  0.471064  | 17.8765    |  9.44629  | 0.302278 |  6.19188   | 0.243644  | 0.0128691  |  0.0675069  |   0.388328  | 0.119137  |
| SWup   | detailed     |  2.98149   |   0.12263   | 0.968631 | 0.98515  |  0.454485  |  2.55151   |  4.07271  | 0.172489 |  0.12263   | 0.0313706 | 0.0148501  |  0.101967   |   0.572043  | 0.0919964 |
| LWup   | baseline     |  7.63021   |  -0.598307  | 1.20522  | 0.990329 | 10.0978    | 16.1995    |  9.72105  | 0.255785 |  0.598307  | 0.205216  | 0.00967149 |  0.0206738  |   0.267169  | 0.107267  |
| LWup   | detailed     |  7.48288   |  -1.10174   | 1.16853  | 0.986973 |  8.53529   | 12.3663    |  9.26758  | 0.242584 |  1.10174   | 0.168527  | 0.0130273  |  0.0537209  |   0.500953  | 0.105036  |
| Qle    | baseline     | 14.0036    |  -2.63731   | 0.868889 | 0.520488 |  8.91716   |  6.7457    | 20.0529   | 0.922212 |  2.63731   | 0.131111  | 0.479512   |  0.989352   |   1.30528   | 0.282579  |
| Qle    | detailed     | 14.643     |   0.663642  | 0.964842 | 0.509763 |  9.74993   |  4.85757   | 20.9896   | 0.973261 |  0.663642  | 0.0351584 | 0.490237   |  0.357941   |   0.0561539 | 0.249846  |
| Qh     | baseline     | 40.0227    | -33.1486    | 0.862702 | 0.801462 |  6.65362   | 36.8803    | 51.4962   | 0.601173 | 33.1486    | 0.1373    | 0.198538   |  0.448249   |   0.759049  | 0.378553  |
| Qh     | detailed     | 31.349     | -17.2517    | 0.899765 | 0.820222 |  5.45121   | 17.3925    | 41.6051   | 0.577548 | 17.2517    | 0.100237  | 0.179778   |  0.309536   |   0.352049  | 0.249508  |
| Qtau   | baseline     |  0.148924  |  -0.14324   | 0.568388 | 0.756251 |  0.0282679 |  0.315287  |  0.206961 | 0.680718 |  0.14324   | 0.431612  | 0.243749   |  0.00487105 |   0.109615  | 0.330286  |
| Qtau   | detailed     |  0.0983752 |  -0.0269397 | 0.880627 | 0.791355 |  0.00652   |  0.0647299 |  0.138235 | 0.61784  |  0.0269397 | 0.119374  | 0.208645   |  0.00614582 |   0.035066  | 0.0784328 |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### out of range: baseline


### out of range: detailed

 - Ensemble Qanth min value of -13.5436 is less than expected 0.0 [W/m2]


[Link to variable definitions](../modelattrs/variable_definitions.md)

