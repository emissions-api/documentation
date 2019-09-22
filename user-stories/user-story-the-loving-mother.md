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

Aggregated values for specific sub-areas of an area.

### Data

-     provide aggregated data for a set of areas, once
- requires sensor data and positions

### Delivery

Good:

- RESTful API
- format should be easy to process
- delivery in real-time (<1s waiting)
- define a polygon to get results

Would still work:

- RESTful API
- format should be easy to process
- delivery in reasonable time (≤5min waiting)
- define a rectangle
