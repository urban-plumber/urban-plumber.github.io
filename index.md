---
title: Home
---

**How have new developments in urban climate models affected performance over the last 10 years, and how do different modelling approaches compare across a range of urban conditions?**

We invite you to help answer these questions by participating in the Urban-PLUMBER project - a multi-site urban model evaluation project, starting in May 2020 and running for 12 months.

![](/img/schematic_v2.png)

## Who should get involved?
Both modellers and those with urban flux tower observations are invited to participate.

**Modelling participants:** Urban climate models that simulate neighbourhood-scale radiant and turbulent fluxes representative of above roof height exchange can participate. Both specialised urban land surface models (LSM) and LSM without an explicit urban representation (e.g. vegetation-focussed models) are of interest. LSM will be run offline (i.e. uncoupled to an atmospheric model) at a range of sites. Those who provide model outputs will be invited as authors on relevant papers.

**Flux tower data participants:** Local-scale urban flux tower observations will be used to both drive models and evaluate outputs. Meteorological information (air temperature, pressure, humidity, precipitation) as well as downwelling short and longwave fluxes will be provided to participants. Evaluation data (turbulent and upwelling radiant fluxes) will be used by the core team to evaluate model output, but will not be distributed to modelling participants.  Those who provide observational data will be invited as authors on relevant papers.

## What are the key science questions?
1. How have new developments affected model performance since PILPS-Urban? 
2. Where do different modelling approaches excel across increasingly urbanised sites?
3. How does more detailed morphology information affect model performance? 
4. Are models utilising available meteorological information effectively?

## Key outputs
We expect at least two papers from this project:
1. How developments have affected urban model performance since the last major comparison at a single site. 
2. How different models perform at different points along the urban/vegetation fraction continuum. 

Analysis will draw on methods of other recent LSM evaluation projects like PILPS-Urban (Grimmond et al. 2011), PLUMBER (Best et al., 2015) and SUBLIME (Steeneveld et al., 2017).

## Resources to make participation simpler
Often the most time-consuming aspects of evaluation projects is getting inputs and outputs in complying form. We offer the following to streamline this process:
1. **Input forcing available in either netCDF or text format:** Two equivalent metrological forcing files will be provided: text and netCDF. The text file is formatted per the PILPS-Urban project, while the netCDF file is formatted per the PLUMBER project.
2. **Example scripts available to convert output data into complying netCDF:** We require output to be in a standard netCDF form to allow evaluation. As some groups may not have used netCDF, we will provide a Python script to translate model output (in text form, for example) to a complying netCDF file with appropriate metadata.
3. **Example scripts available to automate model configuration in the multi-site phase:**  To speed up application to ~20 sites and reduce inconsistencies of how site information is used, we encourage participants to use a script which reads the provided standard site data information table and writes model configuration files. We will provide an example script that does this, and provide help if required.
4. **Immediate feedback provided on output to help identify issues:** Through an online portal model output can be checked for compliance, basic performance analysed, and immediate feedback provided. This allows participants to spot obvious errors (e.g. mislabelled or wrongly-signed variables) and resubmit if required.
This project is challenging as it will include about 20 sites, and will include a wide variety of models with different standards. We hope the above steps make participation simpler, and that you will join us to help push forward the latest in urban land surface modelling.

## What to do to get involved
Email [met-urban-plumber@reading.ac.uk](mailto:met-urban-plumber@reading.ac.uk) to register your interest, either as a modeller or by providing flux tower data. We can then provide you with full instructions for participation.

## Acknowledgments
We gratefully acknowledge those who have supported this project, provided valuable feedback, and offered observational datasets including Gab Abramowitz, Andrew Coutts, Helen Ward, Aristofanis Tsiringakis, Gert-Jan Steeneveld, Denise Hertwig, Natalie Theeuwes, Martin De Kauwe and Andrew Pitman.

## References
1. Best, M. J., Abramowitz, G., Johnson, H. R., Pitman, A. J., Balsamo, G., Boone, A., Cuntz, M., Decharme, B., Dirmeyer, P. A., Dong, J., Ek, M., Guo, Z., Haverd, V., van den Hurk, B. J. J., Nearing, G. S., Pak, B., Peters-Lidard, C., Santanello, J. A., Stevens, L. and Vuichard, N.: The Plumbing of Land Surface Models: Benchmarking Model Performance, J. Hydrometeor, 16(3), 1425–1442, doi:10.1175/JHM-D-14-0158.1, 2015.
2. Grimmond, C. S. B., Blackett, M., Best, M. J., Barlow, J., Baik, J.-J., Belcher, S. E., Bohnenstengel, S. I., Calmet, I., Chen, F., Dandou, A., Fortuniak, K., Gouvea, M. L., Hamdi, R., Hendry, M., Kawai, T., Kawamoto, Y., Kondo, H., Krayenhoff, E. S., Lee, S.-H. and Loridan, T.: The International Urban Energy Balance Models Comparison Project: First Results from Phase 1, Journal of Applied Meteorology & Climatology, 49(6), 1268–1292, doi:10.1175/2010JAMC2354.1, 2010.
3. Grimmond, C. S. B., Blackett, M., Best, M. J., Baik, J.-J., Belcher, S. E., Beringer, J., Bohnenstengel, S. I., Calmet, I., Chen, F., Coutts, A., Dandou, A., Fortuniak, K., Gouvea, M. L., Hamdi, R., Hendry, M., Kanda, M., Kawai, T., Kawamoto, Y., Kondo, H., Krayenhoff, E. S., Lee, S.-H., Loridan, T., Martilli, A., Masson, V., Miao, S., Oleson, K., Ooka, R., Pigeon, G., Porson, A., Ryu, Y.-H., Salamanca, F., Steeneveld, G. j., Tombrou, M., Voogt, J. A., Young, D. T. and Zhang, N.: Initial results from Phase 2 of the international urban energy balance model comparison, International Journal of Climatology, 31(2), 244–272, doi:10.1002/joc.2227, 2011.
4. Steeneveld, G., Tsiringakis, A., Barlow, J., Bohnenstengel, S., Grimmond, S., Halios, C., van Haren, R., Kotthaus, S., Masson, V., van den Oord, G. and others: Single-column urban boundary layer inter-comparison modelling experiment (SUBLIME): Call for participation, Urban Climate News: Quarterly Newsletter of the IAUC, 66, 21–26, 2017.


