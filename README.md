# quick_commerce_order_delivery_assigment_optimisation
This project was carried as part of the Optimization course being taught at Jio Institute, Navi Mumbai.

A quick commerce company needs to solve the challenge of assigning the right delivery executives to the right orders so that

- Delivery is completed within the promised time to the customer
- Delivery cost is minimized for the company

Assumption made:

cost_per_km = 2             # Cost per kilometer
speed_km_per_min = 0.5      # Speed of travel in km/min
wait_time_cost = 1          # Cost per min


Data is provided in two files

-	Sample Orders that consists of details of the store location, customer location, order amount, order packing time, delivery time promise made to the customer in minutes

-	Sample delivery executives that includes details of the delivery executives, their location when free from current order and time to get free from current order in minutes

Solver used:

Google OR Tools pywraplp
