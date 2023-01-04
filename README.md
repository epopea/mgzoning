# Dataset for the Socioclimatic Profiles for the State of Minas Gerais

Dataset used to create socioclimatic zones for the State of Minas Gerais

The dataset is comprised of publicly avaiable data, compiled and wrangled as the basis for our Latent Class models. The following variables are present in the dataset:

* <tt>codigo</tt>: IBGE municipality code (7 digits)
* <tt>municipio</tt>: Municipality name
* <tt>inund</tt>: Number of floods
* <tt>enx</tt>: Number of flash floods
* <tt>seca</tt>: Number of droughts
* <tt>prcptot</tt>: Annual total precipitation in wet days (RR>=1mm)
* <tt>sdii</tt>: Annual total precipitation divided by the number of wet days (defined as precipitation >= 1.0mm) in the year
* <tt>rx1day</tt>: Monthly maximum 1-day precipitation
* <tt>rx5day</tt>: Monthly maximum 5-days precipitation
* <tt>r95ptot</tt>: Annual total precipitation when RR>95th percentile
* <tt>r99ptot</tt>: Annual total precipitation when RR>99th percentile
* <tt>r20mm</tt>: Annual count of days when precipitation >=20mm
* <tt>cdd</tt>: Maximum number of consecutive days with RR<1mm
* <tt>cwd</tt>: Maximum number of consecutive days with RR>=1mm
* <tt>Altitude</tt>: Number of meters above the sea level
* <tt>IDHM</tt>: Average achievement in key dimensions of human development: a long and healthy life, being knowledgeable and have a decent standard of living
* <tt>Gini</tt>: Gini coefficient
* <tt>porurb</tt>: Percentage of urban population
* <tt>Lixo</tt>: Percentage of households with inadequate solid waste collection
* <tt>Agua_Esgoto</tt>: Percentage of households with inadequate water supply or sewage
* <tt>Parede</tt>: Percentage of households with walls built of poor-quality materials
