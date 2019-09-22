- [ ] Accepted use-case
- [ ] Primary use-case
- [ ] Good example for website

Interested in metrics about the climate-change, a web developer wants to create
a map of Germany overlaid by a visual representation of average monthly
emissions.

To achieve this goal he needs an API with fast access to average monthly
emission data in a format which can be used to easily generate a map overlay
using JavaScript.

The data should generate a continuous map. Locations for data from multiple
month should be identical. It should be easy to select a given area for which
the data is provided. For a given substance, it is sufficient that the data
contain locations associated with a single value representing the amount of
substance.



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
