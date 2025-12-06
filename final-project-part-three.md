| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# The final data story
> **[View the final story on Shorthand](https://preview.shorthand.com/N1zti9c6aZMBOPpw)**

The final data story examines equity in Pittsburgh's POGOH bike-share system by analyzing station placement, neighborhood demographics, and usage patterns. Through interactive maps and targeted analysis, it asks: *If you could add 10 new bike-share stations to Pittsburgh, where would you put them to best serve communities with the greatest transportation need?*

# Changes made since Part II

The user research conducted in Part II revealed several critical insights that shaped the final deliverable. While the core narrative about bike-share equity resonated with all three participants, they identified specific areas where the story could be clearer, more actionable, and more engaging.

**Bringing the central question forward**

The most significant structural change was moving the guiding question—"If you could add 10 stations, where would you put them?"—from the middle of the story to the very first screen. Two of three interviewees noted that this framing was compelling but appeared too late. In the final version, this question now appears directly under the opening title and is reinforced with a sticky sidebar element that keeps the audience focused on the actionable goal throughout the story.

**Simplifying visual complexity**

The interactive station map was the most engaging visual but also created cognitive load. Participants struggled to juggle color-coded income levels, station circle sizes, and neighborhood labels simultaneously. For the final version, I simplified the color scale to a clearer three-tier system (low/medium/high income neighborhoods), reduced variation in station marker sizes, and added three explicit text callouts that guide readers to the key insights rather than requiring them to decode the entire legend themselves.

The scatterplot comparing car-free households to station access proved to be the most challenging visual for all three participants. While they eventually understood it, two described it as "technical" and worried they might skip it entirely. I addressed this by adding a bold, plain-language caption above the chart that states the takeaway explicitly: *"High-need neighborhoods (top-left quadrant) have many car-free households but limited bike-share access."* I also created an alternative grouped bar chart as a simpler backup visualization showing trips per capita by neighborhood income category.

**Making recommendations actionable**

Participants appreciated the priority neighborhood ranking but wanted more transparency about how those priorities were determined. In the final story, I added a visual "scoring rubric" section that breaks down the priority formula using icons and short bullets (e.g., "+2 points: >15% car-free households," "+1 point: low median income," etc.). This makes the methodology visible without bogging down the narrative.

I also expanded the final call-to-action from a simple list into a concrete three-step roadmap for planners: (1) Pilot 2–3 stations in the highest-priority corridors, (2) Pair expansion with complementary infrastructure (bike lanes, bus connections), and (3) Monitor usage and adjust. This directly addresses the feedback that readers wanted to know "what a planner could actually do next."

**Adding human context**

One participant suggested that the story felt too technical and GIS-focused, noting that a photograph or quote would help readers connect with the real-world implications. I incorporated two photographs of people using POGOH bikes and added a brief hypothetical planner voice quote in the recommendations section: *"We can't solve transportation equity with bike-share alone, but we can make sure our investments reach the people who need them most."* This small addition humanized the story without diluting the data focus.

## The audience

The primary audience for this story is **city transportation planners and mobility advocates**—people who have direct or indirect influence over where new bike-share stations are placed and how the system is marketed. This includes staff at Pittsburgh's Department of Mobility & Infrastructure, POGOH system operators, and local advocacy groups focused on transportation equity and sustainable mobility.

I narrowed this focus through user research. My three interview participants were proxies for this audience: a public policy student familiar with equity frameworks, a design student with civic tech interests, and a Pittsburgh resident who relies on public transit but doesn't currently use bike-share. Their feedback confirmed that the story works best when it assumes some baseline knowledge of Pittsburgh's neighborhoods and transportation challenges, but doesn't require GIS or data analysis expertise.

**Specific adjustments for this audience:**

- **Assumed local context:** I refer to neighborhoods by name (Homewood, Hazelwood, East Liberty) without extensive background, trusting that planners and advocates are already familiar with these areas and their transportation challenges.
- **Focused on actionability over storytelling flair:** Rather than building dramatic tension or using emotional appeals, the narrative prioritizes clarity, evidence, and concrete next steps. Planners need to see *where* gaps exist and *why* those gaps matter—not be convinced that equity is important.
- **Used planning-relevant metrics:** Instead of focusing on total ridership or revenue, I emphasized metrics like "trips per capita," "% households without cars," and "station coverage radius"—measures that align with how mobility planners think about equitable service distribution.
- **Made data sources transparent:** This audience values data provenance. The final story includes clear citations for WPRDC datasets, Census/ACS tables, and any processing steps (spatial joins, aggregation methods). I also added a limitations note acknowledging that we don't have direct rider demographic data.

## Final design decisions

Several design decisions emerged through the iterative process of creating wireframes, testing with users, and refining visualizations in Tableau and Shorthand.

**Color choices:** I used a sequential color scheme (light to dark blue) for income levels, which tested well with participants as intuitive and accessible. For station markers, I initially used a red/green scheme to indicate "underserved" vs. "well-served" areas, but this created red/green colorblind issues. In the final version, I use a single color (orange) for all stations but vary opacity and add shape indicators for priority areas.

**Map interactivity vs. simplicity:** I experimented with fully interactive Tableau maps that allow users to hover over stations and see trip counts, but this slowed down the narrative flow. The final map balances interactivity (zoom/pan enabled) with guided annotations that direct attention to the most important patterns. I also created a static version with clear labels for readers who prefer a more traditional map experience.

**Typography and hierarchy:** Shorthand's default fonts worked well for body text, but I customized headers to be larger and bolder to create clearer section breaks. I also used pull quotes and sidebar text boxes to highlight key statistics (e.g., "Only 3 of Pittsburgh's 10 lowest-income neighborhoods have bike-share stations") so they stand out even for skimmers.

**Data visualization progression:** The story follows a "zoom out to zoom in" pattern: starting with a citywide overview map, moving to neighborhood-level comparisons, and ending with a specific list of priority expansion areas. This structure mirrors how planners often approach spatial analysis and helps readers build mental models progressively.

**Balancing data density:** One lesson from user research was that too many charts create fatigue, but too few make the argument feel weak. The final story includes four core visualizations (station map, income/access scatterplot, time series of ridership growth, priority neighborhood table) plus two simplified supporting charts. Each chart has a clear "job to do" in advancing the argument.

## References

All references and data sources are cited in detail on the final Shorthand story. Key sources include:

- **Western Pennsylvania Regional Data Center (WPRDC):** Healthy Ride/POGOH trip data (quarterly datasets 2015–2024), station location data, and Pittsburgh neighborhood boundaries (GeoJSON). Available at: https://data.wprdc.org/dataset/healthyride-trip-data
- **U.S. Census Bureau, American Community Survey (ACS) 2018–2022 5-year estimates:** Median household income, poverty rates, car ownership, and population by census tract and neighborhood. Available at: https://data.census.gov/
- **POGOH official documentation:** System history, station capacity, and operational notes. Available at: https://pogoh.com/data/
- **City of Pittsburgh Neighborhood Boundaries:** GeoJSON shapefile. Available at: https://catalog.data.gov/dataset/neighborhoods-57111

All datasets used are publicly available. Pre-processed aggregated data and spatial join outputs are available in my GitHub repository for transparency and reproducibility.

Image credits for photographs in the final Shorthand story are provided in the image captions and follow library guidelines for acceptable use. No copyrighted material was used without permission.

## AI acknowledgements

I used an AI assistant (Claude, Anthropic) to help with several specific tasks in completing Part III:

1. **Structuring the Part III markdown:** I provided the assignment requirements, my Parts I and II content, and the expected markdown template. The AI helped draft initial versions of the reflection sections, which I then heavily edited to reflect my actual design process and decisions.

2. **Drafting transition language:** For the Shorthand story itself, I used AI to generate a few transitional phrases between sections when I was struggling to connect ideas smoothly. I reviewed and rewrote these to match my voice.

3. **Synthesizing user feedback:** I shared my raw interview notes and asked the AI to help me organize them into the "changes made" section. I verified that the synthesis accurately reflected what participants said and added my own interpretations of what those changes meant for the design.

All substantive content decisions—what to include in the story, which visualizations to create, how to prioritize neighborhoods, and what recommendations to make—were my own. The AI was a drafting and organizational aid, not a decision-making tool.

# Final thoughts

This project taught me that **clarity and actionability matter more than visual sophistication** when your audience is decision-makers. My initial instinct was to create the most impressive, interactive visualizations possible, but user research showed me that simpler charts with stronger narratives actually communicate better.

The most challenging part was balancing comprehensiveness with focus. I had access to rich trip-level data spanning nearly a decade, and I wanted to explore temporal patterns, membership types, seasonal variation, and much more. But every additional analysis risked diluting the core equity question. Learning to cut interesting-but-tangential insights was harder than creating the visualizations themselves.

If I had more time, I would:

- **Incorporate actual rider demographic data** if it becomes available. Right now, I'm inferring need based on neighborhood characteristics, but direct data on who uses (or doesn't use) bike-share would strengthen the argument significantly.
- **Add a cost/affordability dimension:** Several people I spoke with casually mentioned that bike-share membership fees might be a barrier in low-income neighborhoods. I didn't have good data on pricing tiers or subsidy programs, but this would be a valuable addition.
- **Create a simple web tool** where planners could input their own priority weights (e.g., "weight car-free households 3x instead of 2x") and see how the neighborhood rankings change. This would make the story even more actionable.

What I'm most proud of is that this story doesn't just point out a problem—it offers a specific, data-driven path forward. Whether or not POGOH or the city uses this exact framework, the story models how equity analysis can be rigorous, transparent, and directly useful for decision-making.

