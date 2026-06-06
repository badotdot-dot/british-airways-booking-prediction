# British Airways Customer Booking Prediction

## Objective
To analyze historical search data and identify the core variables that indicate whether a customer will finalize a flight booking.

## Methodology
Processed 50,000+ customer records and trained a Random Forest machine learning model in Python to evaluate the predictive power of customer trip parameters. 

## Key Findings
* **Timing is the strongest indicator:** The number of days between booking and travel (`purchase_lead`) and the planned `length_of_stay` carry the highest predictive weight.
* **Flight schedules matter:** Departure time (`flight_hour`) and `flight_day` heavily influence completion rates.
* **Add-ons do not drive the purchase:** Early selection of extra baggage or preferred seats has minimal impact on checkout completion.
