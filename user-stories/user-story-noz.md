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

Single aggregated value over specific time of a very small area.

### Data

- provide an aggregated data point of a specific time of a very small area
- requires sensor data and positions
- input is only a single coordinate

### Delivery

Good:

- RESTful API
- format should be easy to process
- delivery in real-time (<1s waiting)
- aggregated daily

Would still work:

- RESTful API
- format should be easy to process
- delivery in reasonable time (≤5min waiting)
- aggregated monthly
