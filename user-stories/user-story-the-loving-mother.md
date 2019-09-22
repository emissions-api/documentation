- [ ] Accepted use-case
- [ ] Primary use-cas
- [ ] Good example use-case

A little girl got a lung disease. 
In search of a cause for this the mother wants to check the air pollution level of her district in the past.

To achieve this, the user needs an API to get the historical data of the desired time frame.
An indicator of when the levels are toxic or unhealthy would be helpful.


Technical Requirements
----------------------

### Goal

Aggregated values over specific time duration (could be in the past) of a coordinate. 

### Data

- provide an aggregated data of a specific time of a coordinate
- requires sensor data
- input is only a single coordinate

### Delivery

Good:

- RESTful API
- format should be easy to process
- delivery in real-time (<1s waiting)

Would still work:

- RESTful API
- format should be easy to process
- delivery in reasonable time (≤5min waiting)
