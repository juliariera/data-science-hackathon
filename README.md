# Data Science Challenge JUMP2DIGITAL 2023

This repository contains the data science challenge for the 2023 JUMP2DIGITAL hackathon. 
Author: Júlia Riera


Introduction
------
In this project, we use data available in Open Data BCN, the Barcelona City Council's open data service. The main dataset with which we work in the project is the [rent dataset](https://opendata-ajuntament.barcelona.cat/data/es/dataset/est-mercat-immobiliari-lloguer-mitja-mensual/resource/0a71a12d-55fa-4a76-b816-4ee55f84d327) which is later merged with the [accidents dataset](https://opendata-ajuntament.barcelona.cat/data/ca/dataset/accidents_causa_conductor_gu_bcn/resource/1a05cdd4-4844-41a5-872d-a0824d11b517?inner_span=True). The rent dataset contains the rent price in the different neighborhoods in Barcelona. The accidents dataset contains information about accidents that occurred in Barcelona. Both datasets are from the year 2017.

In order to relate information, we merge both datasets using the rent dataset as the base one. Thus, from the accidents dataset, we extract the number of accidents per neighborhood (total, per cause, and per shift). 


Data preprocessing techniques
------
In order to have accurate data, we perform a missing values analysis and treatment. Moreover, we improve some feature representation and apply normalization to the merged dataset.


Results
------
With our analysis, we are able to see how prices and the number of accidents do have a lot of outliers and vary a lot among neighborhoods. Also, through PCA, we could see how the number of accidents that happen on the night shift is the feature with more variance. 


Conclusions
------
We can clearly observe the non-uniformity of the data. Prices and the number of accidents are really different from neighborhood to neighborhood, revealing how diverse Barcelona is and the big difference between neighborhoods. Also, we find no correlation between the price and the number of accidents meaning that the wealth of the neighborhood (which could mean more investment in mobility plans, for example) does not impact the number of accidents.
