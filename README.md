# Medicare Advantage Welfare Project

These files present some of the code I used in a project to look at Racial and Ethnic Differences in the value of supplemental benefits in Medicare Advantage (draft forthcoming). Here is the description of the files:

1. `creating_data_dictionary`: Requires `individual_data_2019.dta` and `plan_data_2019.dta.` Builds a data dictionary with keys for the county_year with both individual level data, and plan level data for different county_years that I will use in my estimation process. As `individual_data_2019.dta` is based on the Medicare Current Beneficiary Survey (MCBS), a restricted dataset, and `plan_data_2019.dta` is restricted to counties in the MCBS, I am not allowed to provide the data. I also save the county_years in my data

2. `model_estimation_code`: Builds and estimates a share-constrained Maximum Likelihood Estimator. Requires an initial parameter guess and the data dictionary made in `creating_data_dictionary`


