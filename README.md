# Tableau Project | British Airways Dashboard
## Link to Tableau Dashboard:
https://public.tableau.com/app/profile/ruchi.asthana/viz/BritishAirwaysDashboard_RuchiA/Dashboard1
## About the Project:
* In this project, we build an **interactive** Tableau dashboard that tracks passenger ratings and reviews of British Airways.
* Data Overview:
  * We connect to two .csv files (_ba_reviews_ and _Countries_).
  * _ba_reviews_: Each row of the table is a review with fields like 'Place' (where the review took place) and important Rating metrics.
  * _Countries_: Has 'Country', 'Code', 'Continent' and 'Region' fields.
  * Edit Relationship by matching fields: Place = Country (specifically to be able to use filters like 'Continent').
* The dashboard has a _'Pick a Metric'_ single-select list having custom rating categories:
  * Overall Rating
  * Cabin Staff Service
  * Entertainment
  * Food
  * Ground Service
  * Seat Comfort
  * Value
* The end-user of this dashboard can select a specific metric that they would like to see with a single click.
* So, users can toggle between average overall ratings or food ratings or entertainment ratings very easily.
* The project has four main visuals that are incorporated into the dashboard:
  * A Map visual that shows Average ratings and number of reviews by Country.
  * A Line chart that shows Average ratings by Month.
  * Average ratings and number of reviews by Aircraft (Dual bar chart)
  * A summary section that shows the overall average of each rating category.
* The dashboard has Advanced Filters to focus on specific information:
  * Timeline filter (Month of Date)
  * Seat Type
  * Traveller Type
  * Aircraft
  * Continent
* Each of the visuals are _dynamic filters_ themselves wherein users can click within the visuals on a single data point (for example, a specific country on the map visual) to further filter down the data.
## Some Insights:
* The countries with the highest ratings (7 and above) have less than 5 reviews.
* United Kingdom is the largest customer base with the highest reviews (849) followed by the United States (128).
* A350 is the highest rated Aircraft (overall).
* A350 is the most popular choice for Business Class while Boeing 777-300 has highest ratings for Economy Class.
* The Airline scores lowest ratings in Entertainment across all Seat Types with the lowest being 0.5 for Economy Class.
* No particular Aircraft stands out in Cabin Staff Service.
* Cabin Staff Service ratings remain consistent across all Traveller and Seat Types.
* The ratings have sharp dips in 2020 and 2021 owing to the Covid-19 period.
