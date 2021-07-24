# Overview
As many statistics shown, a country's GDP directly related to its waste generation. Getting inspired from that, I want to create a model for waste prediction based on GDP. In this project, **linear regression** and **KNN regression** are the two models selected and **MAE** will be the standard for comparing accuracy.
# Data Source
- [World Bank Data Catalog (Waste)](https://datacatalog.worldbank.org/dataset/what-waste-global-database/resource/de74cc68-e796-4e42-9793-f140719c91ac#{view-graph:{graphOptions:{hooks:{processOffset:{},bindEvents:{}}}},graphOptions:{hooks:{processOffset:{},bindEvents:{}}},view-grid:{hiddenColumns:[!composition_food_organic_waste_percent,!composition_glass_percent,!composition_metal_percent,!composition_other_percent,!composition_paper_cardboard_percent,!composition_plastic_percent,!composition_rubber_leather_percent,!composition_wood_percent,!composition_yard_garden_green_waste_percent,!other_information_information_system_for_solid_waste_management_na,!other_information_national_agency_to_enforce_solid_waste_laws_and_regulations_na,!other_information_national_law_governing_solid_waste_management_in_the_country_na,!other_information_ppp_rules_and_regulations_na,!other_information_summary_of_key_solid_waste_information_made_available_to_the_public_na,!population_population_of_people,!special_waste_agricultural_waste_tons_year,!special_waste_construction_and_demolition_waste_tons_year,!special_waste_e_waste_tons_year,!special_waste_hazardous_waste_tons_year,!special_waste_industrial_waste_tons_year,!special_waste_medical_waste_tons_year,!waste_collection_coverage_rural_percent_of_geographic_area,!waste_collection_coverage_rural_percent_of_households,!waste_collection_coverage_rural_percent_of_population,!waste_collection_coverage_rural_percent_of_waste,!waste_collection_coverage_total_percent_of_geographic_area,!waste_collection_coverage_total_percent_of_households,!waste_collection_coverage_total_percent_of_population,!waste_collection_coverage_total_percent_of_waste,!waste_collection_coverage_urban_percent_of_geographic_area,!waste_collection_coverage_urban_percent_of_households,!waste_collection_coverage_urban_percent_of_population,!waste_collection_coverage_urban_percent_of_waste,!waste_treatment_anaerobic_digestion_tons_year,!waste_treatment_compost_tons_year,!waste_treatment_controlled_landfill_tons_year,!waste_treatment_incineration_tons_year,!waste_treatment_landfill_unspecified_tons_year,!waste_treatment_open_dump_tons_year,!waste_treatment_other_tons_year,!waste_treatment_recycling_tons_year,!waste_treatment_sanitary_landfill_landfill_gas_system_tons_year,!waste_treatment_unaccounted_for_tons_year,!waste_treatment_uncollected_tons_year,!waste_treatment_waterways_marine_tons_year,!where_where_is_this_data_measured,!iso3c,!regionID],columnsWidth:[{column:!total_msw_total_msw_generated_tons_year,width:129},{column:!incomeID,width:238}]}})
- [World Bank Data (GDP)](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?end=2020&most_recent_value_desc=true&start=1960&view=chart)
# Project Outline
1. Data Cleaning

   Merge dataframe and visualizing
![1](https://github.com/lennylin1998/Waste-Prediction-Based-on-GDP/blob/main/graph%20images/newplot%20(5).png)
   Spot outliers and remove them
![3](https://github.com/lennylin1998/Waste-Prediction-Based-on-GDP/blob/main/graph%20images/newplot%20(4).png)
2. Model Building
  
   Train, test the models, and visualize them on the graph
![4](https://github.com/lennylin1998/Waste-Prediction-Based-on-GDP/blob/main/graph%20images/newplot%20(3).png)
3. Conclusion

   KNN would be a better model with a lower GDP, and linear regression would give a more accurate result with higher GDP. 
