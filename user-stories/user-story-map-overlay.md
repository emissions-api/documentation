- [ ] Accepted use-case
- [ ] Primary use-case
- [ ] Good example for website

A user wants to display the air pollution of his hometown to raise awareness of increasing pollution levels.
Therefor he wants to have an image of his area with satellite or map view as background image and display the pollution data as an overlay with explanation of the colors in that picture. 
The user needs an API to get the image of a selected area (selected by coordinates or shape file) with the option to select the desired background image (satellite or map view).



Technical Requirements
----------------------

### Goal

Create Images merged from pollution data and selectable background.

### Data

- provide images from the selected area
- requires positions

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

