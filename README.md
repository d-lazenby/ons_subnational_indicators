# Investigating subnational indicators in the UK
These notebooks work with a dataset from the Office of National Statistics that outlines various subnational indicators for individual Local Authority Districts and Unitary Authorities (hereafter, districts). The dataset can be obtained [here](https://www.ons.gov.uk/peoplepopulationandcommunity/wellbeing/datasets/subnationalindicatorsdataset) and indicators of educational levels and access (e.g. proportion of children obtaining GCSE Maths and English, percentage of schools and nurseries rated good or outstanding by OFSTED, ...), health (e.g. average healthy life expectancy, percentage of the adult population that smokes, ...), wellness (e.g. levels of anxiety, feelings of satisfaction with life, ...), as well as median weekly income, gross value added per hour, and average travel time to work by car, public transport and bicycle.

I'm interested in general questions related to how indicative the average income of a district is of the levels of education, health, productivity and wellness within that district.

This is a work in progress at the moment containing:
- Import and concatentation of various datasheets to a single dataframe.
- Categorisation of districts based on weekly income.
- Initial exploration of health and education factors broken down by income; comparison of distributions with swarmplots and ECDFs. 
- Exploration of how health and education indicators are related to one another and income.
