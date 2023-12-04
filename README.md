# UMass GeoGuessr
UMass GeoGuessr is a web-based game built with [Flutter](https://docs.flutter.dev/) and [Dart](https://dart.dev/) in which players can test their knowledge of the UMass Amherst campus.  It was built as a part of HackUMass XI, a popular 36-hour hackathon, and it won ["Best Use of Google Cloud"](https://devpost.com/software/umass-geoguesser) for our use of the [Google Maps API](https://developers.google.com/maps).

## Gameplay and Scoring
Players are shown a series of photographs that were taken on campus and have to plot a marker on the map to make a guess of where they think the photo was taken.
Guesses are scored by considering their distance from the target location which is revealed along with the distance after the player makes their guess.
The team utilized the Google Maps API to display the map, allow for map control, plot markers, and get the latitude and longitude coordinates of the guess and target locations.

## Screenshots
### Map Page
![map page](https://github.com/johncle/umass-geoguessr/assets/110953303/d4e6731e-6457-4bd1-be2b-79609efbb542)
### Guess Popup
![guess popup](https://github.com/johncle/umass-geoguessr/assets/110953303/3aef3e48-373d-4cea-aa00-4f481a7abf43)

## Inspiration
We were inspired by GeoGuessr, an online game in which players are put into a random location on Google Street View and are tasked with trying to plot their location on a map as accurately as possible.  We figured that a UMass equivalent, in which players are given photos of locations around campus, would be fun for students to try.
