# UK-Swindon: ASLUMv3.1

**NOTE:** *Results presented here are highly dependent on how models are configured in this experiment and may be subject to variable output formatting errors. Results are not intended to indicate the quality of any individual model, but to help participants better understand and improve modelling approaches in different urban environments.*

### Submitted metadata

- [Baseline](ASLUMv3.1_UK-Swindon_baseline_attrs.md)
- [Detailed](ASLUMv3.1_UK-Swindon_detailed_attrs.md)

### Error metrics

| flux   | experiment   |       MAE |        MBE |        nSD |          R |        5th |      95th |      RMSE |      cRMSE |       AMBE |       1-nSD |         1-R |   nSkewness |   nKurtosis |     Overlap |
|:-------|:-------------|----------:|-----------:|-----------:|-----------:|-----------:|----------:|----------:|-----------:|-----------:|------------:|------------:|------------:|------------:|------------:|
| SWup   | baseline     |   4.02913 |   2.74876  |   1.01791  |   0.974795 |   0.370871 |   2.81384 |   7.33694 |   0.227232 |   2.74876  |   0.0179133 |   0.0252052 |   0.074809  |   0.196517  |   0.0844012 |
| SWup   | detailed     |   4.97162 |  -0.934053 |   0.903315 |   0.961379 |   0.46844  |   7.81798 |   8.47241 |   0.281285 |   0.934053 |   0.0966847 |   0.0386208 |   0.0880081 |   0.275117  |   0.082557  |
| LWup   | baseline     |  13.2085  |  11.6823   |   1.24663  |   0.980549 |   3.33993  |  29.1628  |  16.3597  |   0.330638 |  11.6823   |   0.246626  |   0.0194511 |   0.261708  |   0.598296  |   0.140241  |
| LWup   | detailed     |   8.19568 |   6.99623  |   1.16872  |   0.988044 |   1.04812  |  20.2692  |  10.7996  |   0.237515 |   6.99623  |   0.168722  |   0.0119556 |   0.309094  |   1.07628   |   0.088397  |
| Qle    | baseline     |  20.6886  |  13.0888   |   1.122    |   0.815254 |   5.75068  |  24.3488  |  29.5033  |   0.655327 |  13.0888   |   0.121999  |   0.184746  |   0.0688955 |   0.149675  |   0.251395  |
| Qle    | detailed     |  27.6505  |  24.3712   |   1.43214  |   0.845956 |   8.09888  |  64.6272  |  40.2028  |   0.79245  |  24.3712   |   0.432145  |   0.154044  |   0.0605758 |   0.0556843 |   0.321853  |
| Qh     | baseline     |  24.7881  |  12.5139   |   0.729454 |   0.892551 |  24.2837   |  29.2864  |  31.8438  |   0.479534 |  12.5139   |   0.270546  |   0.107449  |   0.209534  |   0.448871  |   0.336848  |
| Qh     | detailed     |  20.399   |  12.1399   |   0.857035 |   0.924259 |  17.1775   |  12.491   |  26.6021  |   0.38764  |  12.1399   |   0.142965  |   0.0757411 |   0.105375  |   0.222919  |   0.272863  |
| Qtau   | baseline     | nan       | nan        | nan        | nan        | nan        | nan       | nan       | nan        | nan        | nan         | nan         | nan         | nan         | nan         |
| Qtau   | detailed     | nan       | nan        | nan        | nan        | nan        | nan       | nan       | nan        | nan        | nan         | nan         | nan         | nan         | nan         |

 - MAE: mean absolute error (close to 0 is better)
 - MBE: mean bias error (close to 0 is better)
 - NSD: ratio of model to obs standard deviation (close to 1 is better)
 - R: Pearson's correlation (close to 1 is better)
 - all others: closer to 0 is better

[Link to variable definitions](../modelattrs/variable_definitions.md)

### <a name="subset_swup_v0-9"></a>subset_SWup_v0-9
[![ASLUMv3.1_UK-Swindon_subset_SWup_v0-9.png](ASLUMv3.1_UK-Swindon_subset_SWup_v0-9.png)](ASLUMv3.1_UK-Swindon_subset_SWup_v0-9.png)

### out of range: baseline

 - ASLUMv3.1 SWup min value of -20.5284 is less than expected 0.0 [W/m2]
 - ASLUMv3.1 alb min value of -0.0446 is less than expected 0.0 [1]
 - ASLUMv3.1 Albedo min value of -0.0446 is less than expected 0.0 [1]

### out of range: detailed

 - ASLUMv3.1 SWup min value of -29.0867 is less than expected 0.0 [W/m2]
 - ASLUMv3.1 alb min value of -0.0632 is less than expected 0.0 [1]
 - ASLUMv3.1 Albedo min value of -0.0632 is less than expected 0.0 [1]


[Link to variable definitions](../modelattrs/variable_definitions.md)

