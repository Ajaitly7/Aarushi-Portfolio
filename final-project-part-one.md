| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |



# Outline
> Pittsburgh’s public bike-share system (formerly **Healthy Ride**, now **POGOH**) has expanded and rebranded since 2015, adding new stations and e-bikes across the city. At the same time, the system is often framed as a tool for “everyone” – residents, students, and visitors who want to take short trips around Pittsburgh. In practice, though, access to stations and patterns of usage may not be evenly distributed across neighborhoods or demographic groups. :contentReference[oaicite:0]{index=0}  

In this project, I want to tell a data-driven story about **who actually benefits from Pittsburgh’s bike-share system**. I will examine how station placement and ridership vary across neighborhoods with different income levels, racial compositions, and car ownership rates. The goal is not to criticize bike-share itself, but to highlight potential inequities in access and usage, and to help city staff, planners, and residents think about bike-share as part of a broader conversation about transportation equity.

The final story will combine maps, time series, and simple comparison charts to show:  
- where stations are located,  
- who lives near them, and  
- how ridership has changed over time.  

By the end, my audience should have a clear answer to the question: **“Is Pittsburgh’s bike-share system serving the neighborhoods that need affordable transportation the most?”** 
 


## Initial sketches

> Post images of your anticipated data visualizations (sketches are fine). They should mimic aspects of your outline, and include elements of your story.  
![IMG_4589](https://github.com/user-attachments/assets/74521aa2-a163-436f-a502-da55744c6f7e)
![IMG_4591](https://github.com/user-attachments/assets/2925a7fc-7bee-4aa0-972c-db28ad6aeabd)
![IMG_4590](https://github.com/user-attachments/assets/de74464b-004e-4c16-bc01-01df8c1a64a8)




# The data

> To tell this story, I need three main ingredients:

1. Bike-share station and trip data
- The Western Pennsylvania Regional Data Center publishes Healthy Ride / POGOH trip data and related system information. These quarterly datasets include trip start/end stations and timestamps, and can be aggregated to show ridership by station, neighborhood, and time. 

- I will use this data to calculate:
total trips per station / neighborhood per year,
peak usage times, and
simple indicators like “trips per resident” or “trips per station.”

2. Station locations and neighborhood boundaries

- Bike-share station locations (lat/long, name, capacity) are also available through WPRDC and/or via POGOH’s data links. 
- Pittsburgh neighborhood boundaries are published as an open dataset through the Western Pennsylvania Regional Data Center (Pittsburgh neighborhood polygons). I will use these shapes to assign stations and trips to neighborhoods and to drive the choropleth maps.

3. Neighborhood demographic and transportation characteristics

- I will use U.S. Census / American Community Survey (ACS) data (accessed via data.census.gov or a pre-processed neighborhood-level dataset) to obtain:

 - median household income,
 - poverty rate,
 - % of households without cars, and
 - population counts

These variables will be used to characterize neighborhoods and examine whether station placement aligns with higher transportation need.

All datasets I use will be either publicly available or shared via my GitHub repository (for pre-processed versions). In the final project, I will clearly cite all sources and briefly explain any processing steps (e.g., spatial joins, aggregation by year).

| Name | URL | Description |
|------|-----|-------------|
|  Healthy Ride / POGOH Trip Data    | https://data.wprdc.org/dataset/healthyride-trip-data    | Quarterly trip-level records for Pittsburgh’s bike-share system (trip start/end, membership type, timestamps). |
| POGOH Data & Documentation | https://pogoh.com/data/ | Entry point to public data and documentation for POGOH, including links to WPRDC datasets and system history. |
| Neighborhood Boundaries – City of Pittsburgh | https://catalog.data.gov/dataset/neighborhoods-57111/resource/ec6632fc-0255-4e89-91bd-3ba54669621d | Polygon shapefile/GeoJSON of Pittsburgh neighborhood boundaries used for mapping and spatial joins.|
| ACS Demographic Data | https://data.census.gov/| Census/ACS tables providing neighborhood-level demographics (income, poverty, car ownership) that I will join to neighborhood polygons.|
# Method and medium
> For the final project, I plan to build a web-based, scrollable story that combines narrative text with interactive visualizations:

-> Authoring platform / medium
I plan to use Shorthand (or a similar scrollytelling tool approved in class) to structure the narrative: sections, headers, and annotations. I will embed interactive Tableau visualizations (maps, time series, comparison charts) into the Shorthand story.

-> Tools and workflow

- Use Tableau to connect directly to CSVs (trip data, station locations, neighborhood attributes) and create:
- An interactive station + demographics map,
- time-series views of ridership by neighborhood or cluster, and
- comparison charts (bar charts, scatterplots).

-> Host any supporting datasets and documentation in my GitHub repo, with clear links and a short readme describing the data preparation steps.

The final deliverable will be a publicly accessible URL to my Shorthand story (or equivalent), plus a link to the supporting code/data in my GitHub portfolio

## References

- Western Pennsylvania Regional Data Center (WPRDC), Healthy Ride / POGOH bike-share datasets. 
- WPRDC Data
- POGOH – Pittsburgh’s bikeshare system, official website and data documentation. 
- U.S. Census Bureau, American Community Survey (ACS) – demographic and transportation access variables at neighborhood or tract level.
- Good Charts by Scott Berinato – especially Chapters 5–8 on story structure and narrative flow.

## AI acknowledgements

I used an AI assistant (ChatGPT, GPT-5.1 Thinking) to:

- help interpret the Part I assignment instructions and the provided markdown template, and
- draft an initial version of my project outline, data description, and method/medium sections.

I reviewed, edited, and customized all content to ensure it reflects my own topic choices, understanding, and plans for the final project.
