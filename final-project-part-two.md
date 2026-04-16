| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Wireframes/storyboards
> Using your sketches developed last week, further develop your story outline and relevant components visually through the use of wireframing / storyboards. Using your outline as a guide, include high-fidelity, individual draft data visualizations of the critical elements of your story you want to share with your reader. Note: You can build these elements out directly in Shorthand this week if you wish.  Reminder: this template is intended to help, but it doesn't substitute for reading through the full homework assignment!  The assignment page on Canvas includes many important details for completing Part II of the final project. 

After experimenting with Tableau, RawGraphs, and Excel, I ultimately created my final visualizations in Excel. 

In part 1, I came up with several ideas, including a dual-line chart displaying grocery CPI on line 1 and gas CPI on line 2, compared side by side with a line chart displaying the presidential approval ratings. The Y-Axis would have been CPI Index / Approval %, and the X-Axis would have been the same across each year (from 2000 to 2026).

<img width="597" height="431" alt="image" src="https://github.com/user-attachments/assets/ef72d4a1-62fd-4c00-ad67-2f790a2973aa" />

Ultimately, after trying several things, I found that overlaying CPI and approval ratings using a dual-axis chart (with CPI on one axis and approval rating on the other) significantly improved the readability and helped me to see a clear correlation between gas prices and approval rating (and notably, no correlation between food costs and approval ratings, which was a surprise to me).

From there, I made the decision to separate the food and gas CPI into two distinct graphs rather than keeping them together. This allowed for clearer comparisons and made the relationships easier to interpret.

<img width="1086" height="618" alt="image" src="https://github.com/user-attachments/assets/1a170880-fe34-439d-b30d-b27a20d4a8f3" />

<img width="1101" height="432" alt="image" src="https://github.com/user-attachments/assets/a58586bf-5686-4718-9162-003cf781d4dd" />

One of the most surprising insights from this process was the difference in impact between the two variables. Grocery CPI appeared to have little to no clear relationship with presidential approval ratings, while gas CPI showed a much stronger and more noticeable correlation. 

Showing these graphs side by side made this contrast more apparent than when they were overlaid in a single chart.


# User research 

## Target audience
My target audience is policymakers, politicians, and any individuals who are involved in public policy. I was interested in working on this project specifically because I often hear discussions about “the economy” in the media, but this often feels vague and even abstract compared to the very tangible economic conditions the average American experiences on a day-to-day basis. 

To ground this analysis in something very visible to the average American, I focused on gas and grocery prices as representative indicators of economic pressure. Specifically, I am using the "Consumer Price Index for All Urban Consumers: Food at Home in U.S. City Average" and the "Consumer Price Index for All Urban Consumers: Gasoline (All Types) in U.S. City Average." These costs are highly visible, fluctuate regularly, and impact nearly all Americans, making them strong proxies for how individuals perceive the state of the economy. I then paired these indicators with the presidential approval rating by month.

## Interview script

For this project, I was fortunate enough to get support from another Heinz College student. 

The goal of my interview was to figure out how I could make my graph as simple as possible. Specifically, I was hoping to get to a place where the average person could look at my graph and understand it without any additional context.

Some of the questions I asked included: 
- 


## Interview findings
> Detail the findings from your interviews.  Do not include PII.  Capture specific insights where possible.

Text here!

| Questions               | Interview 1 (briefly describe) | Interview 2 | Interview 3 |
|-------------------------|--------------------------------|-------------|-------------|
| Question you asked here | Insightful feedback            |             |             |
|                         |                                |             |             |
|                         |                                |             |             |


# Identified changes for Part III

In part three, some of the changes I plan to implement include:
- Adding president names to the X-Axis
- Cleaning up the X-Axis so it is less overwhelming
- Picking consistent colors (red for the presidential approval rating, orange for gas, green for food)
- Adding a graph comparing the presidential approval rating to the GDP
- Finding a way to communicate the meaning of CPI / Consumer Price Index more cleanly
- Improving the titles of the charts
- Consider finding a way to visualize significant events such as the 2008 financial crisis and the COVID-19 pandemic (maybe annotations?)

## References
“Consumer Price Index for All Urban Consumers: Food at Home in U.S. City Average.” FRED, 11 Mar. 2026, fred.stlouisfed.org/series/CUSR0000SAF11.

“Consumer Price Index for All Urban Consumers: Gasoline (All Types) in U.S. City Average.” FRED, 11 Mar. 2026, fred.stlouisfed.org/series/CUSR0000SETB01.

“Presidential Job Approval Center.” Gallup.Com, Gallup, 17 June 2023, news.gallup.com/interactives/507569/presidential-job-approval-center.aspx.

## AI acknowledgements
I used AI to help me navigate Tableau and Excel to create my data visualizations.
