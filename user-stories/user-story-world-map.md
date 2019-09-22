- [ ] Accepted use-case
- [ ] Primary use-case
- [ ] Good example for website

To make their data seen and experienced by more unexperienced users the ESA wants to create a fully covered world map of the latest recorded sensor values.

They need an API which can give them the latest recorded data point for every point on the world.

The data should handle overlapping values well and every data point should contain a timestamp.



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
