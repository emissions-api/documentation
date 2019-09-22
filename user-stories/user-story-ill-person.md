- [ ] Accepted use-case
- [ ] Primary use-case
- [ ] Good example for website

Eine Person, die anfängt Lungenprobleme zu bekommen, überlegt, was er tun kann, um gegenmaßnahmen einleiten zu können. Ein sache die der Person einfallen könnte ist zu schauen, ob es Regionen gibt, die weniger dolle Probleme mit Luftverschmutzung haben.

Um dies zu Erreichen, würde er sich eine Map generieren, die über Deutschland verteilt mit einer Farbskala zeigt, welche Regionen weniger doll und welche doller belastet sind.
Anderenfalls könnte man auch eine Art Hitliste erzeugen, je nach eingegebener Region/Bundesstaat oder what ever, die zeigt, welcher Ort zum mindest in der Region am wenigsten Belastet ist.


Technical Requirements
----------------------

### Goal

Aggregated values for specific sub-areas of an area.

### Data

- provide aggregated data for a set of areas, once
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
