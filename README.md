# Analysis of Crime and AIRBNB Prices in New York City

In this project, I combined two independent datasets related to crime and AIRBNB rentals in New York City. The goal of the analysis was to investigate whether higher AIRBNB rental prices contribute to safer neighborhoods, or if they are associated with fewer crimes. Surprisingly, the results showed that higher prices don't necessarily mean a safer area. Instead, the more bustling and popular a district, the higher the AIRBNB prices and the greater the number of crimes, likely due to increased human traffic.

## Key Insights
One of the most striking findings was the variable **'Host Identity Verified'** in the AIRBNB dataset. Unverified hosts were linked to higher rates of prostitution-related crimes. It turns out that in New York City, unverified AIRBNB listings are often used not just for short-term rentals, but also for illicit activities such as trafficking and other crimes.

## Techniques Applied
The analysis applied advanced **ETL (Extract, Transform, Load)** processes to clean and merge the data, focusing on geographical districts by creating a custom grid of small rectangles on the map, linking AIRBNB listings with potential nearby crimes based on longitude and latitude. Data was further visualized and analyzed to derive actionable insights regarding the relationship between crime rates and rental pricing in New York City.

Using powerful data transformation tools, including **Python**, **SQL**, and **Power BI**, I was able to examine patterns in neighborhood safety, uncover how unverified listings contribute to criminal activity, and explore how human traffic density influences both crime rates and rental prices.

![](https://github.com/AdixPlaysGames/Crime-and-AIRBNB-in-New-York/main/Visual/architecture.png)

Overall, the project demonstrates how data analytics can shed light on complex urban issues, providing valuable insights for decision-makers and the general public alike.
