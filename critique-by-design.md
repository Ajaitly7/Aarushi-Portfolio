| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique and Redesign

## Step one: the visualization

## Selected Visualization  
**Railroad Infrastructure Quality – Country Rankings**  
Source: *MakeoverMonday (2022/W47)*  
Original Visualization:  
[TheGlobalEconomy.com – Railroad Infrastructure Quality Rankings](https://www.theglobaleconomy.com/rankings/railroad_quality/)

Why I Selected This Visualization:

I chose this visualization because it presents an interesting dataset about global infrastructure development, but the original bar chart format limits the viewer's ability to identify meaningful patterns and trends over time. The visualization shows only 2019 rankings, displaying the top 32 countries ranked by their railroad infrastructure quality scores on a scale from 1 (low) to 7 (high). While the bar chart effectively communicates the ranking order, it misses an opportunity to show the temporal dimension of the data specifically, how countries have improved or declined over the decade from 2009 to 2019.
As someone interested in policy analysis and infrastructure development, I was drawn to the potential of showing not just where countries stand, but how they've progressed. This seemed like an ideal candidate for redesign because the underlying dataset (sourced from the World Economic Forum) contains historical data that could reveal compelling stories about infrastructure investment and development trajectories. The original visualization also raised questions about regional patterns and whether certain geographic or economic clusters show similar infrastructure quality levels insights that could be made more apparent through alternative visualization approaches.


Original Visualization


 <img width="417" height="475" alt="image" src="https://github.com/user-attachments/assets/41cc4190-fb8c-4377-a8a5-64c29dd3ab0c" />

 
Figure 1: Original bar chart visualization from MakeoverMonday
 
 <img width="407" height="339" alt="image" src="https://github.com/user-attachments/assets/8c93502d-ef56-4361-b39f-60ce1139e5d7" />

Figure 2: Data tab


## Step two: the critique

I completed a comprehensive critique using Stephen Few's Data Visualization Effectiveness Profile. Below are my key findings:

<img width="409" height="565" alt="image" src="https://github.com/user-attachments/assets/55db28e7-0038-4d4d-a951-c9d238a6ef7b" />

<img width="411" height="555" alt="image" src="https://github.com/user-attachments/assets/1e62a014-c17a-4c6d-b2ba-faf1b6cc66b8" />

<img width="412" height="589" alt="image" src="https://github.com/user-attachments/assets/3484ad52-1033-4907-b024-6a9e4275c606" />


What Worked Well:
The original visualization successfully establishes a clear ranking hierarchy using a horizontal bar chart, which is an appropriate choice for comparing categorical data (countries) across a single quantitative measure.
The scale (1-7 points) is clearly labeled, and the visualization answers its primary question effectively: "Which countries have the highest quality railroad infrastructure in 2019?" The ranking format also makes it easy to identify leaders (Japan, Hong Kong, Switzerland) and compare their relative scores.

What Didn't Work Well:

The most significant limitation is the absence of temporal context. While the dataset includes data from 2009-2019, the visualization only shows a single year snapshot, missing the opportunity to illustrate which countries have made the most progress in infrastructure development over the decade. This is particularly problematic given that infrastructure development is inherently a long-term process where improvement trends are often more meaningful than static rankings.
The lack of geographic or regional grouping makes it difficult to identify patterns among similar economies or regions.
The visualization also suffers from limited interactivity and context. There's no information about what the scores measure, viewers must navigate to external documentation to understand that these represent expert assessments of railroad infrastructure efficiency, quality, and extent.

Finally, the sheer length of the bar chart (showing 32+ countries) makes it challenging to process the information efficiently, especially for countries in the middle range where differences become minimal and less meaningful.


## Step three: Sketch a solution

I developed potential redesign concepts

<img width="236" height="314" alt="image" src="https://github.com/user-attachments/assets/68571505-b1a9-4d8d-9224-53d1667fa507" />




## Step four: Test the solution

I conducted user testing with two peers from my program, sharing both wireframe sketches without extensive explanation to assess intuitiveness.

Feedback from Person 1 (Student, mid-20s):

Key Critique:

"Your chart is not clear. Don't use a scatter plot for countries as it's hard to understand which country without clicking on the dots."
Analysis: This feedback highlighted a critical usability issue with the scatter plot format. Person 1 found that the lack of direct country labels made the visualization difficult to interpret without hovering over individual data points. This suggested that while the scatter plot effectively showed patterns and trends at a macro level, it created friction for users wanting to quickly identify specific countries. The critique indicated a need for more prominent labeling of key countries or potentially adding an interactive legend that could highlight countries of interest.

Feedback from Person 2 (Student, MSPPM program):

Key Critique:

"You can divide the visualization into two in order to make it clearer. The timeline can be reduced to make it starker."
 
Analysis: Person 2 suggested separating the visualization into two distinct views to enhance clarity. They also recommended condensing the timeline to emphasize the magnitude of changes more dramatically. This feedback pointed toward creating separate visualizations for "improved" and "declined" countries or perhaps showing the 2009 and 2019 data in side-by-side comparisons. The suggestion to reduce the timeline implied that showing the full decade might dilute the impact a shorter, more recent time period might make improvements or declines appear more striking and actionable.

## Step five: build the solution

Using Tableau Public, I built the final redesigned visualization incorporating the user feedback and critique insights.
Final Design: Railroad Infrastructure Improvement Matrix Visualization 1: Geographic Distribution Map
I made a choropleth map showing railroad infrastructure quality using color intensity to indicate scores. This would reveal:
•	Geographic clusters of infrastructure quality
•	Regional patterns (e.g., European vs. Asian vs. other regions)
•	Visual identification of countries at a glance


[![Interactive Tableau Dashboard](https://public.tableau.com/static/images/As/Assignment3_17631523273990/Sheet1/1.png)](https://public.tableau.com/views/Assignment3_17631523273990/Sheet1)

https://public.tableau.com/views/Assignment3_17631523273990/Sheet1

I decided to develop both concepts in Tableau to test their effectiveness, I decided to create both scatter plot and the map to show a complete visualization

Visualization 2: Improvement Matrix (Scatter Plot)


[![Interactive Tableau Dashboard](https://public.tableau.com/static/images/As/Assignment3p2_17631530998880/Aarushiassignment3p2/1.png)](https://public.tableau.com/views/Assignment3p2_17631530998880/Aarushiassignment3p2)

https://public.tableau.com/views/Assignment3p2_17631530998880/Aarushiassignment3p2

This visualization is a scatter plot comparing 2009 scores (x-axis) against 2019 scores (y-axis), with reference lines showing the average values for each year. This approach would immediately visualize:

•	Countries that improved (orange points above the diagonal)
•	Countries that declined (red points below the diagonal)
•	High performers vs. emerging improvers (quadrant analysis)
•	Magnitude of change (distance from diagonal)

**Reflection and Key Insights**

This assignment reinforced several key principles about effective data visualization:
1.	While the original bar chart precisely showed rankings, it lacked the temporal context that makes the data meaningful. The improvement matrix sacrifices some precision in exact ranking positions but gains tremendously in showing the story of progress over time.
 
2.	The feedback from peers revealed blind spots in my design that I hadn't considered, particularly around labeling clarity and the need to guide viewers toward the key insight.
3.	By choosing a scatter plot over a bar chart, I fundamentally changed the story from "who ranks highest" to "who has improved most," demonstrating how format decisions encode meaning.

The redesigned visualization successfully transforms static country rankings into a dynamic narrative about global infrastructure progress, making it easier for viewers to understand not just where countries stand today, but how they got there









## AI acknowledgements

AI and Tool Usage Disclosure

Zoom Notetaker for User Feedback Documentation
During the user testing phase, I turned on Notetaker AI while my peers were critiquing my wireframe designs. This transcription tool captured their verbal feedback in real-time, which significantly reduced the time required to document their exact thoughts and allowed me to focus more on the conversation itself rather than frantically taking notes. After the sessions, I reviewed the Otter AI transcripts to extract the key feedback points and quotes included in this document.

AI and transcription tools were used solely for documentation and articulation purposes, not for generating creative ideas or analytical conclusions.


