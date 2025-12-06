| [home page](https://github.com/Ajaitly7/Aarushi-Portfolio/blob/main/README.md) |  | [critique by design](https://github.com/Ajaitly7/Aarushi-Portfolio/blob/main/critique-by-design.md) | [final project I](https://github.com/Ajaitly7/Aarushi-Portfolio/blob/main/final-project-part-one.md) | [final project II](https://github.com/Ajaitly7/Aarushi-Portfolio/blob/main/final-project-part-two.md) | [final project III](https://github.com/Ajaitly7/Aarushi-Portfolio/blob/main/final-project-part-three.md) |

# Wireframes / storyboards
>Shorthand Link: https://preview.shorthand.com/N1zti9c6aZMBOPpw

# User research 

## Target audience

The **primary audience** for this story is:

- **City staff and transportation planners** (e.g., Department of Mobility & Infrastructure, POGOH staff) who are directly involved in decisions about station placement.
- **Transportation and mobility advocates** who care about equitable access to low-cost, low-emission transportation.

To approximate this audience for user research, I selected interviewees who share at least some relevant characteristics:

1. A graduate student in **public policy / urban studies** who has experience thinking about equity and transportation trade-offs.
2. A student in **design / HCI** with an interest in civic design and data visualization (to comment on clarity and usability).
3. A **Pittsburgh resident** who regularly uses transit (buses/Light Rail) but does *not* currently use bike-share, to provide a “smart layperson” perspective.

These three participants are not decision-makers themselves, but together they represent:
- domain awareness (policy and mobility equity),  
- visual design sensibilities, and  
- a local resident perspective.

My goal was to understand whether the **story arc, visuals, and call to action** make sense to people who are similar to the intended audience and to identify points where the story is confusing, overwhelming, or insufficiently actionable.

---

## Interview script

>**Research Goals**

The user research aimed to answer these questions:

I structured my user research around three main goals:

1. **Narrative clarity:**  
   Do readers quickly understand what the story is about, why it matters, and who it’s for?
2. **Visual comprehension:**  
   Are the key charts/maps easy to interpret, and do they support the main points without overwhelming the reader?
3. **Actionability:**  
   Does the final section make it clear what a planner or advocate could actually *do* with this information?

### Goals and questions

| Goal | Questions to Ask |
|------|------------------|
| Understand overall narrative clarity | 1. After skimming the first 1–2 sections, in your own words, what do you think this story is about?<br>2. Who do you think this story is *for*?<br>3. At what point does the main question or purpose become clear to you? |
| Test comprehension of key visuals (maps/charts) | 4. Looking at this map, what is the first thing you notice?<br>5. What do the colors and symbols mean to you? Can you explain them without looking at the legend?<br>6. Is there any chart or visual that you find confusing or hard to interpret? Why? |
| Evaluate actionability and emotional impact | 7. After seeing the “priority areas” section, do you feel like you know what the recommended actions are?<br>8. If you were a planner, what decision could you make using this story?<br>9. Is there any information you wish you had but don’t see here?<br>10. How does this story make you feel about bike-share in Pittsburgh (if at all)? |



## Interview findings

- Walked the participant through the **wireframes/storyboards** (either shared as static images or as a draft Shorthand page).
- Asked them to **“think out loud”** when reacting to the visuals.
- Took notes on:
  - moments of confusion,  
  - points where they leaned in or got excited, and  
  - specific language they used to describe what they saw.

### High-level observations

- **Overall narrative landed well.** All three participants understood that the story is about **equity in access to bike-share** and that it is aimed at **decision-makers** rather than tourists or casual riders.
- **The main question could be surfaced earlier.** Two participants said they only fully understood the “add 10 stations” frame midway through the story and suggested bringing that question into the opening section more prominently.
- **Maps were the most compelling, but also the most cognitively heavy.**  
  - Everyone liked the **station + income map**, but one person struggled to juggle station symbol size, color shading, and neighborhood labels at once.  
  - They recommended simplifying the legend and highlighting fewer key annotations.
- **Scatterplot needed more scaffolding.** All three could eventually interpret the scatterplot, but two described it as “the hardest chart” and suggested adding a plain-language caption or even replacing it with a simpler grouped bar chart.
- **Priority list at the end was appreciated.** The “top 10 candidate areas” concept resonated: one participant said, “This is where it gets really actionable.” They wanted slightly more explanation of *how* the score was calculated.

### Question-by-question summary

| Questions               | Interview 1 (policy student)                  | Interview 2 (design student)                      | Interview 3 (resident)                                  |
|-------------------------|----------------------------------------------|--------------------------------------------------|---------------------------------------------------------|
| 1–3. What is this about / who is it for / when does it become clear? | “It’s about whether bike-share is equitable, and it feels aimed at planners or advocates.” The purpose became clear by the **second section**. | “I like that it’s clearly about equity, not just ridership. I’d move the ‘If you could add 10 stations…’ line higher up.” | “I thought at first it was just about bike-share popularity, but by the map section I understood it was about fair access.” |
| 4–5. First impressions of the map, colors, symbols | Map is “strong and intuitive overall,” but suggested clearer label for low vs. high income in the legend. | Found the color scale and station circles visually appealing but wanted **fewer overlapping labels**; suggested adding short text callouts. | Understood dots = stations and colors = something about neighborhoods; needed to look at legend twice to recall what darker shading meant. |
| 6. Confusing visuals | Scatterplot was “a bit technical” and required explanation; suggested adding takeaway text over/under the chart. | Felt the scatterplot was “doing a lot,” and recommended either simplifying or adding a “this is what to look at” annotation. | Found the time series easy; scatterplot was “the one where I’d probably skip if I was in a hurry.” |
| 7–8. Do you know what actions are recommended? | “Yes, I can see that you’re pointing to specific neighborhoods as high priority. I’d like one or two sentences on how you score them.” | Appreciated the priority list; suggested turning it into a visually ranked list with icons/badges like “Top 3 priority corridors.” | “I get that some neighborhoods should get stations next. It might help to say what the city could *actually* do next—like ‘run a pilot here.’” |
| 9–10. Missing info / feelings | Wanted a brief mention of limitations (e.g., lack of direct rider demographic data). | Suggested showing at least one photo or visual element to humanize the story (e.g., a person using a bike-share station). | Said the story made them feel like “bike-share could be more fair,” and was curious if cost/price was part of the story as well. |

---


# Identified changes for Part III

Based on the interviews, I synthesized a set of concrete design changes to implement for Part III.

| Research synthesis                       | Anticipated changes for Part III                                                |
|------------------------------------------|---------------------------------------------------------------------------------|
| The main guiding question (“If you could add 10 stations…”) was compelling but appeared too far down the page for two interviewees. | Move the guiding question into the **very first screen** of the story, directly under the title, and repeat a shorter version in a sidebar or sticky header. |
| Maps were engaging, but some participants struggled to interpret the legend and multiple encodings (color + size + labels). | Simplify map encodings by: (1) using a clearer two- or three-step color scale, (2) reducing station size variation, and (3) using fewer labeled neighborhoods plus 2–3 text callouts that explicitly explain what is important. |
| Scatterplot was the most cognitively demanding visual, with risk of being skipped or misunderstood. | Add a **plain-language caption** above the scatterplot that states the takeaway in one sentence (“Neighborhoods with high car-free households but no stations appear in this quadrant”). Consider simplifying axes labels and possibly creating a **second, simpler chart** as an alternative (e.g., grouped bar chart of trips per capita by neighborhood category). |
| Priority ranking of neighborhoods was appreciated but needed more transparency. | Add a short, visual explanation of the **priority score formula**, such as a 3–4 bullet list with small icons (“+1: high share of car-free households,” etc.). Include a brief note about limitations. |
| One participant requested a bit more “human context” to avoid feeling like a purely technical / GIS project. | Incorporate **one or two photographs or illustrations** of people using bike-share in Pittsburgh and a short quote-style callout (e.g., hypothetical planner voice or advocate voice) to humanize the story without shifting focus away from the data. |
| People wanted explicit suggestions about what a planner could do next. | Expand the final section into a clearer **call-to-action list**, such as: “Pilot 2–3 new stations in these neighborhoods,” “Pair station expansion with bus/bike infrastructure improvements,” etc. |

> ...include any final thoughts you have here. 

Overall, the user research confirmed that the **core framing and audience choice are working**: readers understand this as an equity-focused story for planners. The main improvements I need to make for Part III are about:

- **Surfacing the main question earlier,**
- **Reducing cognitive load** in a few complex visuals (especially the scatterplot and map legends), and
- Making the **recommendations more explicit and visually obvious** at the end.

I will use these findings as a checklist when refining my Shorthand layout, editing text, and polishing my Tableau dashboards for the final submission.


## References
- Western Pennsylvania Regional Data Center – Healthy Ride / POGOH trip and station datasets.  
- U.S. Census Bureau – American Community Survey (ACS) data for neighborhood-level demographics.  
- POGOH (Pittsburgh’s bike-share system) website and public data documentation.

## AI References:

I used an AI assistant (ChatGPT, GPT-5.1 Thinking) to:

- Help translate my Part I outline into a more detailed storyboard and Shorthand structure.  
- Draft an initial version of my user research protocol (research questions and script) and findings summary.  

I conducted the **actual user interviews** myself and synthesized their feedback into the design changes listed above. I reviewed and edited all AI-generated text to ensure that it reflects my own project, data, and design decisions.


