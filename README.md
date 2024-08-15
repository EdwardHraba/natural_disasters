# Natural Disasters in America

## Motivation:

During my service in the Marine Corps, I was part of a unit dedicated to providing aid to countries struck by natural disasters. This experience, combined with having family across the United States who have personally faced the devastation of wildfires, tornadoes, and hurricanes, has profoundly impacted me. Witnessing the extensive financial and emotional toll of these disasters has fueled my desire to better understand their occurrence and impact within the United States. This project aims to analyze the frequency and distribution of natural disasters, examine their effects on population, and compare the incidence of these disasters with insurance rates across different states.

## Questions:

* What is the most common type of natural disaster in America? 
    
* States with frequent disasters: How do the insurance rates look in these states compared to the lower risk states? 
    
* How do natural disasters affect population? 
    
* Are there any high risk locations that have not been hit with a disaster for a significant amount of time? Are there any time patterns that can indicate when a disaster will hit?

## Normalizing Data:

The dataset I selected includes records of natural disasters dating back to the 1940s. For the purposes of this analysis, I have focused on the period from 2000 to 2024. This timeframe was chosen to provide a more relevant and recent perspective on natural disasters, enabling a clearer examination of contemporary trends and impacts. By concentrating on these more recent years, the analysis aims to deliver insights that reflect current patterns and challenges associated with natural disasters

## Problems Encountered:

In working with the FEMA dataset, one issue I encountered was with the incidentType and declarationTitle columns. The incidentType column categorized the type of natural disaster, while the declarationTitle column contained descriptive names of the disasters. The challenge arose because the declarationTitle column often included multiple types of disasters within a single entry, such as tornadoes and floods, which were not always individually classified. This inconsistency required additional processing to ensure that each disaster type was accurately classified and associated with the correct disaster number for precise analysis

## Technologies Used:

- Python - to clean and explore the dataset
- Powerpoint - for introduction and outro of project
- Powerbi - for interactive visuals in the powerpoint

## Data Sources:
FEMA for natural disasters : 
- Link : https://www.fema.gov/disaster/declarations

census data 
- link: https://data.census.gov/table

bankrate.com for home insurance rates : 
- link : https://www.bankrate.com/insurance/homeowners-insurance/states/#home-insurance-rates-by-state

Insurance.com for home insurance rates: 
- link :https://www.insurance.com/home-and-renters-insurance/home-insurance-basics/average-homeowners-insurance-rates-by-state#:~:text=higher%20when%20included.-,States%20with%20the%20highest%20home%20insurance%20rates,increase%20in%20home%20insurance%20costs
    
## links to Dashboards Used in Presentation
* first dashboard
- disaster type/state disasters:     https://app.powerbi.com/groups/me/reports/61769356-71e9-40c2-89d5-2d0b6521c4f2/4ffcd3d35ccb530ff169?experience=power-bi
* second dashboard
- disaster per 1000 sq miles:        https://app.powerbi.com/groups/me/reports/61769356-71e9-40c2-89d5-2d0b6521c4f2/cafcd88ce195b1ed8040?experience=power-bi
* third dashboard
- popualtion high risk states:       https://app.powerbi.com/groups/me/reports/61769356-71e9-40c2-89d5-2d0b6521c4f2/6a0ea195379da6292641?experience=power-bi
* fourth dashboard
- state risk types days since last:  https://app.powerbi.com/groups/me/reports/61769356-71e9-40c2-89d5-2d0b6521c4f2/826a05938cd37c351d92?experience=power-bi
* fifth dashboard
- insurance rates:                   https://app.powerbi.com/groups/me/reports/61769356-71e9-40c2-89d5-2d0b6521c4f2/3d3fafb0a28bc7ad5f63?experience=power-bi
* sixth dashboard
- disasters over time:               https://app.powerbi.com/groups/me/reports/61769356-71e9-40c2-89d5-2d0b6521c4f2/914460b129f83e49d4da?experience=power-bi
