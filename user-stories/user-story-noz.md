- [ ] Accepted use-case
- [ ] Primary use-case
- [ ] Good example for website

A local newspaper wants to generate a continuous plot of emissions data for
several substances in a given location. For example, the NOZ might want to
include a plot of the amount of SO² in Osnabrück. This image is supposed to be
updated on a regular basis.

To achieve this, it needs to be easy to request sensor data for a single
location and a single substance over time.



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
