Hi Kendry! Thanks for working on this project for our team.
As our newest traffic analyst at Fuerte, a Spanish Train company, you have been tasked with analyzing ridership patterns in the train system. Management wants us to produce summary reports on general ridership  that examine the volume of passengers, ticket prices paid, and length of trips taken by our customers. The primary focus is producing a webpage that gives customers a better idea of what the best travel times and fares are depending on their needs, which will reduce the amount of time our customer service agents spend explaining this information. For now, we'll focus on trips between Madrid and Barcelona, our busiest route. First, read in the data provided, train_ticket_data.csv. Check the column data types, and change them if needed. Then, create four columns and report on the percentage of missing values in each column, including the following:

arrival: add the duration column (in hours) to the departure column, 

departure_dayofweek: extract the day of week (as an integer or text) from departure.

departure_hour: extract the hour from departure.

vehicle_category: 'AVE' and 'AVE-TGV' should be classified as 'High-Speed'; the rest classified as 'Standard'.

Then, collect the following information for a report to management:

The average, minimum, and maximum prices and durations of trips (examine the rows where the minimum and maximum occur).

Whether or not prices for trains departing from Madrid are more expensive than those departing from Barcelona.

A dual axis line chart with the number of total daily riders as one line, and total daily revenue as the other.

A bar chart of average ridership by day of week and departure location to visualize whether more riders take the Madrid-Barcelona train or vice versa on a daily basis.

Build two bar charts (average price by vehicle_category and average duration by vehicle category) to help  customers get an idea of the tradeoffs in time and cost for high-speed vs. standard trains.

A heatmap of average price with day of week as columns and time of day as rows. Use this to determine which departure times and days should be avoided if customers are looking for a value. Export the table used to build the heatmap to a flat file format of your choice to serve as a prototype for our customer help page.