- [ ] Accepted use-case
- [ ] Primary use-case
- [ ] Good example for website

A user wants to create a time laps of an area (e.g. his hometown) and wants to display the pollution of the air in the past till now.
Therefor he needs to generate pictures with the pollution data for different periods but with a common scale / color code.
The user needs an API to generate the pictures of the selected area with the option to select different time spans for the time lapse.


Technical Requirements
----------------------

### Goal

Variable duration aggregated values in a fixed grid for an area.

### Data

- provide variable duration aggregated data for an area
- requires sensor data and positions

### Delivery

Good:

- RESTful API
- (GEO)JSON
- format should be easy to process
- delivery in real-time (<1s waiting)
- define a polygon to get results

Would still work:

- RESTful API
- format should be easy to process
- delivery in reasonable time (≤5min waiting)
- define a rectangle
