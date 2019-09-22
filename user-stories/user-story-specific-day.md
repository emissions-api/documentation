- [ ] Accepted use-case
- [ ] Primary use-case
- [ ] Good example for website

Someone wants to get sensor data for an area at an specific date in the past.

He needs sensor data for one value at an specific day in the past for a certain area.

The data is aggregatet for that one day.



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
