# airline_data_challenge
Problem Statement
You are working for an airline company looking to enter the United States domestic market.
Specifically, the company has decided to start with 5 round trip routes between medium and
large US airports. An example of a round trip route is the combination of JFK to ORD and ORD
to JFK. The airline company has to acquire 5 new airplanes (one per round trip route) and the
upfront cost for each airplane is $90 million. The company’s motto is “On time, for you”
, so punctuality is a big part of its brand image.
You have been tasked with analyzing 1Q2019 data to identify:
1. The 10 busiest round trip routes in terms of number of round trip flights in the quarter.
Exclude canceled flights when performing the calculation.
2. The 10 most profitable round trip routes (without considering the upfront airplane cost) in
the quarter. Along with the profit, show total revenue, total cost, summary values of
other key components and total round trip flights in the quarter for the top 10 most
profitable routes. Exclude canceled flights from these calculations.
3. The 5 round trip routes that you recommend to invest in based on any factors that you
choose.
4. 5. The number of round trip flights it will take to breakeven on the upfront airplane cost for
each of the 5 round trip routes that you recommend. Print key summary components for
these routes.
Key Performance Indicators (KPI’s) that you recommend tracking in the future to
measure the success of the round trip routes that you recommend.
Link to metadata and datasets:
https://github.com/CapitalOneRecruiting/DA-Airline-Data-Challenge

Here is background information on the three datasets that you will analyze:
1. Flights dataset: Contains data about available routes from origin to destination. For
occupancy, use the data provided in this dataset.
2. Tickets dataset: Ticket prices data (sample data only as the data is huge). Consider
only round trips in your analysis.
3. Airport Codes dataset: Identifies whether an airport is considered medium or large
sized. Consider only medium and large airports in your analysis.

You can make the following assumptions:
● Each airplane is dedicated to one round trip route between the 2 airports
● Costs:
○ Fuel, Oil, Maintenance, Crew - $8 per mile total
○ Depreciation, Insurance, Other - $1.18 per mile total
○ Airport operational costs for the right to use the airports and related services are
fixed at $5,000 for medium airports and $10,000 for large airports. There is one
charge for each airport where a flight lands. Thus, a round trip flight has a total of
two airport charges.
○ For each individual departure, the first 15 minutes of delays are free, otherwise
each minute costs the airline $75 in added operational costs.
○ For each individual arrival, the first 15 minutes of delays are free, otherwise each
minute costs the airline $75 in added operational costs.
● Revenue:
○ Each plane can accommodate up to 200 passengers and each flight has an
associated occupancy rate provided in the Flights data set. Do not use the
Tickets data set to determine occupancy.
○ Baggage fee is $35 for each checked bag per flight. We expect 50% of
passengers to check an average of 1 bag per flight. The fee is charged
separately for each leg of a round trip flight, thus 50% of passengers will be
charged a total of $70 in baggage fees for a round trip flight.
○ Disregard seasonal effects on ticket prices (i.e. ticket prices are the same in April
as they are on Memorial Day or in December)
