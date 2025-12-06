| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# The final data story
> **[Building a Bike System for All of Pittsburgh](https://preview.shorthand.com/SEqXeLaH05TDWIP1/responsive/desktop)**

The final story examines equity in Pittsburgh's POGOH bike-share system through 2025 ridership data. By analyzing 506,034 trips across 60 stations, the story reveals stark disparities in access and usage: 64.1% of all trips originate in Oakland, where universities provide free membership, while underserved neighborhoods like Homewood and Hazelwood see minimal ridership despite having stations. The story concludes with three concrete recommendations for expanding bike-share as equitable transportation infrastructure.

# Changes made since Part II

The transition from Part II to the final deliverable involved significant refinements based on user research feedback and deeper data exploration that emerged during the final analysis.

**Sharpening the equity focus**

Part II's wireframes presented bike-share equity as a general access issue. The final story narrows this to a more specific, actionable question: *Is POGOH a city-wide transportation system, or effectively a university amenity?* This reframing came directly from the data—when I calculated that 64.1% of trips originate in Oakland, it became impossible to ignore. User research participants responded strongly to this concrete statistic, so I moved it to the very top of the story and made it the organizing principle for the entire narrative.

**Leading with impact, not setup**

Following feedback that the guiding question appeared too late in Part II, the final version leads immediately with scale and impact: "506,034 trips in 2025" appears as the first major callout. This grounds the story in real achievement before pivoting to inequity. The structure now follows: celebrate success → reveal concentration → examine barriers → propose solutions. This creates a more balanced tone that acknowledges POGOH's genuine accomplishments while still making the case for equity improvements.

**Adding the membership analysis**

The member vs. casual rider breakdown was not a major component of Part II but became central to the final story. User research revealed that participants didn't initially understand *why* Oakland dominated ridership. Adding the membership analysis (97% members in Oakland vs. 59-63% at stations without institutional backing) provided the explanatory mechanism: free access drives adoption. This insight directly informed the final recommendations around subsidized membership expansion.

**Simplifying the visualization strategy**

Part II included a scatterplot comparing car-free households to station access, which all three user research participants found difficult to interpret. I removed this entirely from the final story and replaced it with simpler, more direct visualizations:

- **Member vs. Casual charts** that show the university effect clearly
- **Time-of-day patterns** that distinguish commuter from leisure usage
- **Seasonal trends** that reveal the September surge when students return
- **A simple table** of underutilized stations with concrete ridership numbers

Each visualization now has a single, clear job: show one specific inequity or opportunity.

**Creating an implementation framework**

Part II ended with general recommendations. The final story provides a concrete implementation framework with timelines, lead agencies, and success metrics. For example:
- Station Activation: 12-18 months, led by DOMI + POGOH, measured by 50% ridership increase
- Subsidized Access: 6-12 months, led by POGOH + Partners, measured by 1,000 new subsidized memberships
- Connector Corridors: 2-3 years, led by DOMI + Planning, measured by new cross-neighborhood trip flows

This shift from "what should happen" to "how it could happen" directly addresses user feedback requesting more actionability.

**Incorporating seasonal and temporal insights**

The final story includes two entirely new sections that weren't in Part II: time-of-day patterns and seasonal analysis. These emerged from deeper exploration of the trip data and add important nuance to the equity story. The finding that winter ridership remains strong (16,000 trips in January) counters the narrative that Pittsburgh's weather makes bike-share impractical. The September surge (101,000 trips) shows what's possible when access barriers are removed. These insights strengthen the case for year-round investment in underserved areas.

## The audience

The primary audience is **city transportation planners and POGOH system operators**—the decision-makers who control station placement, partnership development, and resource allocation. Secondary audiences include **mobility advocates** and **community organizations** in underserved neighborhoods who can use this data to advocate for equitable access.

User research validated this focus. My three interviewees (a public policy student, a design student interested in civic tech, and a Pittsburgh transit user) all confirmed that the story works best when it assumes:
- Familiarity with Pittsburgh's neighborhoods and their characteristics
- Interest in equity frameworks and transportation justice
- Desire for actionable, data-driven recommendations rather than abstract advocacy

**Specific adjustments for this audience:**

**Professional tone and data transparency:** The final story cites specific data sources, provides exact trip counts (not just percentages), and acknowledges limitations (e.g., lack of direct rider demographic data). Planners and operators need to trust the analysis before they'll act on recommendations.

**Neighborhood-level specificity:** Rather than speaking generally about "underserved areas," the story names specific stations and neighborhoods: Bennett Street in Homewood (177 rides), Second Avenue in Hazelwood (243 rides). This granularity helps planners immediately identify priority areas.

**Actionable metrics:** Every recommendation includes measurable outcomes. "Expand access" becomes "1,000 new subsidized memberships in 6-12 months." This speaks directly to how planning and operations teams actually work—with timelines, targets, and accountability.

**Balance of appreciation and critique:** The story celebrates POGOH's achievements (half a million trips, year-round viability, institutional partnerships) while identifying gaps. This approach assumes the audience wants to improve an existing success, not defend against attacks. User research confirmed this tone landed well—participants described it as "constructive" rather than "critical."

## Final design decisions

**Visual hierarchy and progressive disclosure**

The Shorthand format allowed me to use scrolling to create progressive disclosure: readers encounter one insight at a time rather than seeing all data at once. The story moves from:
1. System-wide success (506,034 trips)
2. Geographic concentration (64.1% in Oakland)
3. Membership disparities (97% vs. 59-63%)
4. Specific failing stations (11 stations <1,000 trips)
5. Temporal patterns (commuter vs. leisure, seasonal)
6. Concrete recommendations

This structure builds the equity case incrementally, preventing reader overwhelm while maintaining momentum.

**Embedded Tableau visualizations**

I embedded three interactive Tableau charts directly in Shorthand:
- **Member vs. Casual by Neighborhood** (two variations showing different cuts of the data)
- **Time-of-day patterns** showing dual peaks for members, afternoon peak for casuals
- **Seasonal ridership** showing the dramatic September surge

These remain interactive—readers can hover for exact values—but I also added text callouts directly in Shorthand that highlight the key takeaways. This serves both engaged readers who want to explore and skimmers who just need the headline finding.

**Strategic use of statistics as visual elements**

Rather than burying key numbers in paragraphs, I pulled critical statistics into large-format callouts:
- "64.1% of all trips start in Oakland"
- "97% membership rate in Oakland"
- "0.42% of trips from East End"

These create visual rhythm and allow readers to grasp the scale of disparities at a glance. User research participants specifically mentioned these callouts as effective attention-grabbers.

**Photography for humanization**

Following user feedback that Part II felt "too technical," I incorporated four photographs of POGOH bikes and riders (sourced from Unsplash with proper attribution). These images don't carry data but provide visual breaks and remind readers that we're discussing real people's mobility needs, not abstract planning exercises.

**Color palette discipline**

I used Pittsburgh's colors (yellow and black for bikes and stations, blue for data visualizations) to maintain visual consistency between the story and the actual system. This subtle choice reinforces that the analysis is *about POGOH specifically* rather than bike-share in general.

**Table format for underutilized stations**

Rather than trying to visualize the 11 lowest-performing stations on a chart, I presented them as a simple table with three columns: Station name, Rides, and Neighborhood. This format is more scannable and makes it easier for planners to literally copy the list into planning documents.

## References

All data sources and tools are fully documented in the Bibliography section of the Shorthand story. Primary sources include:

- **POGOH Bike Share Trip Data (January–November 2025):** Western Pennsylvania Regional Data Center. https://data.wprdc.org/dataset/healthyride-trip-data
- **U.S. Census Bureau American Community Survey (2018-2022 5-year estimates):** Used for demographic context where referenced. https://data.census.gov
- **Pittsburgh Neighborhoods Boundaries:** City of Pittsburgh Department of City Planning via WPRDC. https://data.wprdc.org/dataset/neighborhoods2

**Visualization tools:**
- Tableau Public for all interactive charts
- Python/pandas for data processing and analysis (aggregating trips by neighborhood, station, time period)

**Images:**
All photographs are sourced from Unsplash and credited to photographer. These are used under Unsplash's free license for editorial and commercial use.

The GitHub repository for this project contains the processed datasets, Python analysis scripts, and links to all Tableau workbooks for full reproducibility.

## AI acknowledgements

I used Claude as an AI assistant for specific tasks in this project:

1. **Refining narrative transitions:** When writing the Shorthand story itself, I used Claude to help smooth transitions between sections and to identify where my explanations were unclear or overly technical.

2. **Creating the implementation framework table:** I described my recommendations verbally and asked Claude to help structure them into the timeline/lead agency/metrics format. I verified that all details were accurate and added the specific metrics myself.

All data analysis, visualization creation, user research, and substantive content decisions were my own work. I conducted the actual interviews, processed all trip data in Python, created all Tableau visualizations, and made all strategic choices about what to include or exclude from the story.

# Final thoughts

The most important lesson from this project: **specificity drives action**. My initial instinct was to speak broadly about "equity" and "access," but what actually moved user research participants—and what will move planners—are concrete statements like "11 stations logged fewer than 1,000 trips" and "Oakland has 97% membership while Station Square has 59%."

**What worked:**

The seasonal analysis was the unexpected highlight. I initially included it as supplementary context, but it became one of the story's strongest arguments: 16,000 trips in January proves year-round viability; 101,000 trips in September shows what's possible with the right access model. These findings directly counter common objections to bike-share expansion.

The implementation framework table was invaluable for grounding recommendations in reality. Rather than just saying "expand subsidized access," providing a 6-12 month timeline and a "1,000 new memberships" target makes the recommendation feel achievable rather than aspirational.

**What I would improve with more time:**

**Direct cost analysis:** Several people asked about membership pricing and whether cost is truly the barrier in underserved neighborhoods. I didn't have good data on pricing tiers, discount programs, or what portion of potential riders find $100/year affordable vs. prohibitive. Adding this dimension would strengthen the subsidized access recommendation.

**Station-level environmental factors:** Why do some stations fail while others succeed? I identified 11 underperforming stations but could only speculate about causes (visibility, safety perception, competing transportation, proximity to jobs/services). Site visits and environmental audits would provide actionable improvement strategies beyond "do more outreach."

**User demographic data:** I'm inferring equity gaps based on neighborhood characteristics, but POGOH doesn't publish rider demographic data. If that data exists (even in aggregate), incorporating it would transform this from a "station access" story to a "who actually rides" story.

**What I'm most proud of:**

The story makes a clear, actionable case without demonizing anyone. POGOH has genuine achievements—half a million trips is remarkable. The university partnerships are a success story, not a failure. The issue isn't that Oakland gets good service; it's that other neighborhoods don't. This framing opens the door for constructive partnership between advocates, planners, and operators rather than creating adversarial dynamics.

The recommendation to "activate underperforming stations before relocating them" reflects real-world planning constraints. You can't just move infrastructure without community buy-in, and announcing that a station "failed" damages trust. The 12-18 month intervention-then-evaluate approach respects both the need for change and the complexity of implementation.

Ultimately, this project demonstrated that good data storytelling for decision-makers requires not just good data and good visualizations, but a clear theory of change: what specific action should happen, who should do it, when, and how will we know if it worked? That's the standard I tried to meet.
