# Data Visualization 

Data Visualization Project | NOVA IMS

Authors: Beatriz Andrade, Gonçalo Coutinho, Mariana Lavinha, Mariana Rodrigues

## Project Link

Here is the link to access our dashboard: https://public.tableau.com/app/profile/mariana.lavinha/viz/DV_DASHBOARD/Dashboard3?publish=yes 

## Project Context

This project was created in accordance with the evaluation requirements for the Data Visualization course, which is a requirement for the Master in Data Science and Advanced Analytics program.

The idea came up after a few hours of research in a Lego set guide and because it has a lot of LEGO articles, we downloaded the dataset locally. 
A visualization tool was created to analyze the evolution of the toy industry and demonstrate how visualization concepts and techniques can be used to transform data into an interactive representation that provides insight into the significant changes that have occurred in the world of Lego over the years. In the context of Data Visualization course, this project aims to present in an organised and funny way, a LEGO interaction Dashboard that shows and brings some evolutions and curiosities over the years. The project was implemented in Tableau and the idea in our Dashboard is to allow the users to selecta certain timeline and their favourite Set.

### Questions of interest

1. How was the evolution of sets and themes over the past 30 years?
2. Are lego sets becoming more and more expensive?
3. What about the evolution of the number of pieces and their price?
4. Top 5 Record-breaking sets by piece count
5. What words do most often come up in set names?

## Dataset Description

The dataset used during the visualisation about Lego was obtained from the Brickset website (https://brickset.com/). This data had to undergo some necessary data cleaning in order to be useful for our visualisation.

| Variable | Type | Description |
| --- | --- | --- |
| Number | Object | Set number ID |
| Theme | Object | Theme Name |
| Subtheme | Object | Subtheme Name |
| Year | Int64 | Year when the set was launched |
| Set_name | Object | Set Name  |
| Minifigs | Float64 | How many minifigures the set has |
| Pieces | Float64 | How many pieces the set has in total |
| Price | Float64 | Price per set without the inflation effect and retail price |
| Value_new | Float64 | Current price of the set (in new conditions) |
| Value_used | Float64 | Price of a set second hand, after devaluation |
| Launch_date | Datetime64 | Represents the date of the first commercial sale |
| Eol_date | Datetime64 | "End-of-life" (eol) represents the final stage of a set's existence |
| Category | Object | If a record is a set or minifigure |
| Price_unadjusted | Float64 | Target price before inflation adjustment |
| Value_change_per | Float64 | The change of a value between the retail price and the current price as a "new set" |

## Data & Methods

Growing up with Lego, we believe that approaching it from a Data Science perspective adds an extra layer of fascination. In order to ensure that all the information was accessible and easy to understand, we decided to create a dashboard that only by looking at it, the user could recognise it was about Lego, so we decided to apply their color scheme throughout the project.

Also, in order not to overcomplicate the dashboard and hinder the audience visualization we included 5 graphical representations, as our overview Tab. Regarding the first chart, using a scatterplot, we can analyze the evolution of the number of sets, as well as the number of themes by using different circle sizes for this second feature.  

Since 2014 the average price per set has been increasing exponentially. In conclusion, both show a positive trend. While the number of themes has more than doubled since 1991, the total number of sets has grown by just under 6 times.

The pieces chart, shows the evolution of pieces' number and price. The conclusion is that  the number of pieces per set is increasing, while the average price per piece is decreasing. To kill some curiosities that arose during the research and development of the work, we decided to know what were the top 5 record-breaking set by piece count and we conclude that The World Map is the largest set of all time, with 11.695 pieces. We also can see in the pie chart, that "pack" is the most frequent word in set names.

Furthermore, some details that conveyed information about each set of Lego, were created for the user to be able to select the Set Name and be able to see what theme it belongs to, the launch year, its number of pieces and minifigures, the price and the percentage change since the set was discontinued
