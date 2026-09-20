# worcestershire-road-safety-analysis
Visualisation project of Worcestershire Road Safety

Context & Problem: 

Although there are existing public resources for road safety data in a given area such as the UK government’s Think Map or Crash Map, I wanted to utilise Tableau’s tools to see if any more visually interesting stories could be told about road safety in my local area. In particular I wanted to see if a highly interactive dashboard could be created that helped to more clearly inform the user about key trends in terms of how incidents cluster on certain routes, roads, times of day, and whether speed or environmental conditions are factors in road accidents in Worcestershire.

Technical Methodology:

This project aimed to use the most up to date data from the Department for Transport’s STATS19 records for 2025. Future projects or iterations of this dashboard could make use of the last 5 years dataset that is also publicly available, which would also help to show trends over a longer time period, but it would need to adjust for methodology and category changes made since 2024. To extract just the data for Worcestershire, I filtered the data for the relevant local authority ONS codes in the spreadsheet. I then had to make use of Excel to use VLOOKUP/XLOOKUP logic to decode the numbers given by the DfT for incidents, types or road, environmental conditions, etc as well as joining cell data to generate road numbers. In Tableau, I also had to create additional calculated fields for the % killed or serious and dynamic filters for the top named route. I then structured the findings into a highly interactive dashboard in Tableau Public using spatial mapping and cross-filtering. 

I initially had a stacked bar chart of the environmental conditions for each collision included in the dashboard. This found that the overwhelming majority of incidents occurred in bright conditions and good weather. Including this chart with the others made the dashboard too cluttered and harder to read and take in the key findings. Therefore, I removed this from my draft dashboard and instead included the weather and lighting conditions in the tooltip that users find when they hover/select any incident from the collision map. I have published the stacked bar chart separately here: https://public.tableau.com/app/profile/phil.brack/viz/WorcestershireRoadSafety2025/Sheet4 


Key Findings: 

Over 34% of recorded collisions resulted in fatal or serious injuries.

Single carriageways were the most common location for collisions with the majority being in unclassified smaller roads.

Of named roads in the data, the A38 had the most collisions in 2025 (43).

Unsurprisingly, most collisions took place during weekday commuting hours, but this was not evenly distributed with the peak tending to be early evening Wednesday to Friday.

The highest proportion of incidents occurred on roads where the speed limit was 30mph or less (48%).

69% of incidents occurred in daylight when the weather was fine and clear.
