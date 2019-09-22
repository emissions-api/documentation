- [ ] Accepted use-case
- [ ] Primary use-case
- [ ] Good example for website

To make their data seen and experienced by more unexperienced users the ESA wants to create a fully covered world map of the latest recorded sensor values.

They need an API which can give them the latest recorded data point for every point on the world.

The data should handle overlapping values well and every data point should contain a timestamp.



Technical Requirements
----------------------

### Goal

Latest values of the entire world with timestamps

### Data

- provide latest values of a rastered world with timestamps
- requires sensor data, positions and timestamps

### Delivery

Good:

- RESTful API
- format should be easy to process
- delivery in real-time (<1s waiting)
- scalable grid

Would still work:

- RESTful API
- format should be easy to process
- delivery in reasonable time (≤5min waiting)
- fixed grid
