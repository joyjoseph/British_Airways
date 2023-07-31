# Predictive modeling of customer bookings

---

We will use various packages for data manipulation, feature engineering and machine learning.

## Data Description

The Customer Booking dataset contains lots of features listed below:

- `num_passengers` = number of passengers travelling
- `sales_channel` = sales channel booking was made on
- `trip_type` = trip Type (Round Trip, One Way, Circle Trip)
- `purchase_lead` = number of days between travel date and booking date
- `length_of_stay` = number of days spent at destination
- `flight_hour` = hour of flight departure
- `flight_day` = day of week of flight departure
- `route` = origin -> destination flight route
- `booking_origin` = country from where booking was made
- `wants_extra_baggage` = if the customer wanted extra baggage in the booking
- `wants_preferred_seat` = if the customer wanted a preferred seat in the booking
- `wants_in_flight_meals` = if the customer wanted in-flight meals in the booking
- `flight_duration` = total duration of flight (in hours)
- `booking_complete` = flag indicating if the customer completed the booking

### Explore and prepare the dataset

We would explore the data in order to better understand what we have and the statistical properties of the dataset.

## Train a machine learning model

We will train a machine learning model to be able to predict the target outcome, which is a customer making a booking. For this task, we would use a RandomForest algorithm that easily allows you to output information about how each variable within the model contributes to its predictive power. 

## Evaluate model and present findings

After training the model, we would evaluate how well it performed by conducting cross-validation and outputting appropriate evaluation metrics. Furthermore, we would create a visualisation to interpret how each variable contributed to the model. And summarise findings in a single slide to be sent to your manager.
