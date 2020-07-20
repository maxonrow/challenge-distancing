# Geolocation

## Problem Statement

- Due to COVID-19, New Norm applying to our daily lives. Without further burden to Healthcare frontliners and government, how can we make use of Geolocation Analytics to monitor and apply "Social Distancing" efficiently?

- Singapore and Australia are among the many governments that have already implemented contact tracing apps to stop the widespread of COVID-19. However, ethical dilemmas surround the nature of these apps that have resulted in people not using the app. How can we create a 'contact tracing' or 'social distancing' solution using blockchain technology that is quickly adopted by over 60% of a country's population in the event of a pandemic? Or better yet, that can be utilized worldwide?

## Example Solution

- An analytical model or solution that able to identify crowded places and predict any potential outbreak area.

- An analytical model or solution that able to monitor & alert of any lockdown violators.

## Running the Browser Examples

``` bash
cd face-api.js/examples/examples-browser
npm i
npm start
```

Browse to <http://localhost:3000/>.

### Euclidean Distance

``` javascript
// meant to be used for computing the euclidean distance between two face descriptors
const dist = faceapi.euclideanDistance([0, 0], [0, 10])
console.log(dist) // 10
```
