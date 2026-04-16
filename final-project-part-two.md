| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Wireframes/storyboards
After experimenting with Tableau, RawGraphs, and Excel, I ultimately created my final visualizations in Excel. 

In part 1, I came up with several ideas, including a dual-line chart displaying grocery CPI on line 1 and gas CPI on line 2, compared side by side with a line chart displaying the presidential approval ratings. The Y-Axis would have been CPI Index / Approval %, and the X-Axis would have been the same across each year (from 2000 to 2026).

<img width="597" height="431" alt="image" src="https://github.com/user-attachments/assets/ef72d4a1-62fd-4c00-ad67-2f790a2973aa" />

Ultimately, after trying several things, I found that overlaying CPI and approval ratings using a dual-axis chart (with CPI on one axis and approval rating on the other) significantly and unexpectedly improved the readability of the chart, which helped me to see a potential relationship between gas prices and approval ratings (and notably, no correlation between food costs and approval ratings, which was a surprise to me).

From there, I made the decision to separate the food and gas CPI into two distinct charts rather than keeping them together. This allowed for clearer comparisons and made the relationships easier to interpret.

<img width="1086" height="618" alt="image" src="https://github.com/user-attachments/assets/1a170880-fe34-439d-b30d-b27a20d4a8f3" />

<img width="1101" height="432" alt="image" src="https://github.com/user-attachments/assets/a58586bf-5686-4718-9162-003cf781d4dd" />

One of the most surprising insights from this process was the difference in impact between the two variables. Grocery CPI appeared to have little to no clear relationship with presidential approval ratings, while gas CPI showed a much stronger and more noticeable correlation. 

Showing these charts side by side made this contrast more apparent than when they were overlaid in a single chart.

Here is my proposed (very rough) draft of how my story can go. I hope to use minimal text:

<img width="548" height="792" alt="image" src="https://github.com/user-attachments/assets/5c04c07f-85bf-43b2-8c72-355ccfc4b7e7" />


# User research 

## Target audience
My target audience is policymakers, politicians, and any individuals who are involved in public policy. I was interested in working on this project specifically because I often hear discussions about “the economy” in the media, but this often feels vague and even abstract compared to the very tangible economic conditions the average American experiences on a day-to-day basis. 

To ground this analysis in something very visible to the average American, I focused on gas and grocery prices as representative indicators of economic pressure. Specifically, I am using the "Consumer Price Index for All Urban Consumers: Food at Home in U.S. City Average" and the "Consumer Price Index for All Urban Consumers: Gasoline (All Types) in U.S. City Average." These costs are highly visible, fluctuate regularly, and impact nearly all Americans, making them strong proxies for how individuals perceive the state of the economy. I then paired these indicators with the presidential approval rating by month.

## Interview script & findings

For this project, I was fortunate enough to get support from other Heinz College students who were kind enough to look at my data visualizations and give me feedback. 

The goal of my interview was to figure out how I could make my chart as simple as possible (at this point, I had not yet thought of how my narrative would flow and only had visualizations to share). Because of this, I focused specifically on getting to a place where the average person could look at my chart and understand it without any additional context.

Some of the questions I asked included: 

- What works?

        - Clear that you're comparing economic indicators to approval
        - Fairly easy to understand for the most part
        - Timeline is consistent across both charts + splitting gas and food helps a lot
        - Lines overlap surprisingly well with dual axis

- What doesn't work/what would you change?

        - Like that it’s monthly, but I wish it was less messy
        - Hard to immediately understand what CPI means
        - Not clear what specifically I’m supposed to be looking for (correlation? trend? causation?)
        - Feels like I need a more specific takeaway
  
- What questions do you have?
  
        - Why does gas seem more connected?
        - Is this adjusted for inflation or already built into CPI?
        - Should I be comparing slopes or just general direction?

- What was your eye drawn to first?

        - Gas spikes
        - Sharp drops in approval
        - The crossing/movement of the lines (trying to see if they move together)
        - Less drawn to the food chart



Across my interviewees, several consistent themes emerged:

        - Participants understood the general purpose of the visualization
        - Participants were confused by CPI and thus what the numbers on the Y-Axis meant
        - Participants liked the detail of having the chart display monthly intervals on the X-Axis but felt that it made the chart more visually overwhelming
        - Participants wanted a clearer takeaway or conclusion

# Identified changes for Part III

In part three, some of the changes I plan to implement include:

        - To address confusion around CPI → I will simplify and clearly explain what CPI represents
        - To address lack of clarity in what the takeaway should be → I will improve the chart titles 
        - To address cluttered visuals on the X-Axis → I will reduce labels to yearly markers and add the president names
        - To address the lack of context for other factors that took place in the US → I will add annotations for big events that caused inflation spikes
        - To improve readability → I will pick consistent colors (red for the presidential approval rating, orange for gas, green for food)
        - I may also add a chart comparing the presidential approval rating to the GDP and will continue to improve my narrative overall

## References
“Consumer Price Index for All Urban Consumers: Food at Home in U.S. City Average.” FRED, 11 Mar. 2026, fred.stlouisfed.org/series/CUSR0000SAF11.

“Consumer Price Index for All Urban Consumers: Gasoline (All Types) in U.S. City Average.” FRED, 11 Mar. 2026, fred.stlouisfed.org/series/CUSR0000SETB01.

“Presidential Job Approval Center.” Gallup.Com, Gallup, 17 June 2023, news.gallup.com/interactives/507569/presidential-job-approval-center.aspx.

## AI acknowledgements
I used AI tools (specifically ChatGPT) to assist with technical parts of this project, including cleaning and structuring my datasets as well as troubleshooting issues and navigating Excel and Tableau.
