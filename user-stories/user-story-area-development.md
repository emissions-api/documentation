- [ ] Accepted use-case
- [ ] Primary use-case
- [ ] Good example for website

Interested in metrics about the climate-change, a developer wants to know the development of an area, like Germany.
He wants to make a line or bar chart with the time on the X axis and one or multiple sensor data on the Y axis.

To achieve this goal he needs an API with fast access to the emission data aggregated over an area and time interval.
These data should be easily plot-able with JavaScript.

The data should generate single points aggregated over an area and time interval.
Locations for data from multiple time intervals should be identical.

Technical Requirements
----------------------

### Goal

Plot the overall emission development of an area over time

### Data

-     provide aggregated data for an requested area over time
- *or* provide single data points for an area over time
- requires only sensor data
- define a polygon to get results

### Delivery

Good:

- RESTful API
- format should be easy to process
- delivery in real-time (<1s waiting)
- define a rectangle

Would still work:

- RESTful API
- format should be easy to process
- delivery in reasonable time (≤5min waiting)
