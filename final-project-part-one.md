| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Outline
For my final project in Telling Stories With Data, I want to explore the relationship between the changes in the everyday cost of living (through the changes in the average annual price of gas and the changes in the annual average grocery cost) and public sentiment toward the U.S. President over time. The cost of groceries and gas will be measured using the Consumer Price Index for food at home and the Consumer Price Index for gasoline (all types) over the past 26 years (2000-2026). Instead of trying to prove a direct cause-and-effect relationship, this project will focus on identifying whether there are any patterns or moments when shifts in grocery/gas prices align directly with changes in approval ratings.

I wanted to do this project specifically because I hear constant discussions about the economy in very vague terms on the news, but I wanted to understand how tangible, everyday economic experiences like gas and groceries are shaping how the average American feels about their leadership. Grocery and gas prices are useful for this because they are highly visible and affect nearly everyone on a regular basis. By visualizing these trends together, I hope to create a clearer picture of how economic pressure influences public sentiment. 

I expect that through this project, I will find that when the cost of everyday essentials like groceries or gas prices rise, public sentiment toward the sitting president often declines. My primary audience is politicians who may be overly focused on broad economic indicators of how the country is doing which may be at odds with the lived experiences of everyday Americans. My secondary audience is a general audience.

## Initial sketches
For my project, I have four initial thoughts for the types of graphics I could create to display this data clearly. I will be choosing a combination of these (and likely more). These include: 

1) A dual-line chart to show grocery CPI on line 1 and gas CPI on line 2, compared side by side with a line chart displaying the presidential approval ratings. The Y-Axis will be CPI Index / Approval %, and the X-Axis will be the same across each year (from 2000 to 2026).

<img width="488" height="362" alt="image" src="https://github.com/user-attachments/assets/16101ba7-8566-451a-b3ad-ae4ca8272237" />

2) A bar chart that shows year-over-year change in grocery/gas prices and approval ratings.

<img width="445" height="281" alt="image" src="https://github.com/user-attachments/assets/579569bd-72cf-4165-a88d-bb6d8ef23134" />

3) A scatterplot with the cost of living (CPI) on the X-axis and the approval rating on the Y-axis (I will do one for groceries and one for gas prices).

<img width="455" height="278" alt="image" src="https://github.com/user-attachments/assets/2b4a0586-0f29-4ebc-b45a-6fe68dfe8b83" />

4) And finally, I would like to create some kind of visual that adds additional context for moments like the 2008 recession, COVID in 2020, etc...


# The data

For my data on average annual grocery prices, I will download the monthly "Consumer Price Index for All Urban Consumers: Food at Home in U.S. City Average"  via FRED (Federal Reserve Economic Data) and calculate the annual averages in Tableau. I originally hoped to find a breakdown of the average annual cost of groceries for a household in the United States, but realized this data would be too complex. Because of this, I will use the CPI instead.

https://fred.stlouisfed.org/series/CUSR0000SAF11

<img width="1632" height="657" alt="image" src="https://github.com/user-attachments/assets/e7ae07ea-3b32-4eef-a669-c81c77030caf" />

For my data on annual gas prices, I looked to the U.S. Bureau of Labor Statistics via FRED's "Consumer Price Index for All Urban Consumers: Gasoline (All Types) in U.S. City Average." I had initially investigated other sources like data from the U.S. Energy Information Administration, but chose to stick with a more comparable data set to my grocery costs.

https://fred.stlouisfed.org/series/CUSR0000SETB01

<img width="1640" height="663" alt="image" src="https://github.com/user-attachments/assets/ff07a2da-4469-428b-8eb9-836f04532da9" />

Finally, for the presidential approval ratings, I will pull the yearly averages for each president from Gallup.

https://news.gallup.com/interactives/507569/presidential-job-approval-center.aspx

<img width="1535" height="482" alt="image" src="https://github.com/user-attachments/assets/b150e327-9522-4ee7-bfe0-4dba3e2dc554" />

# Method and medium

For my final project, I intend to use Tableau for my data visualizations. My goal is that my graphics will be able to tell a story if seen without any additional context about my project.

## References

“Consumer Price Index for All Urban Consumers: Food at Home in U.S. City Average.” FRED, 11 Mar. 2026, fred.stlouisfed.org/series/CUSR0000SAF11. 

“Consumer Price Index for All Urban Consumers: Gasoline (All Types) in U.S. City Average.” FRED, 11 Mar. 2026, fred.stlouisfed.org/series/CUSR0000SETB01. 

“Presidential Job Approval Center.” Gallup.Com, Gallup, 17 June 2023, news.gallup.com/interactives/507569/presidential-job-approval-center.aspx. 
