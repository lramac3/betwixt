![build](https://img.shields.io/badge/build-passing-brightgreen.svg) ![npm](https://img.shields.io/badge/npm-v6.4.1-blue.svg)

# Betwixt

Betwixt is a map tool for calculating convenient meeting locations between friends. It is written in React and implements Google Maps API.

Finding a place to hang out can be difficult. Meeting up with friends who are all an hour car ride away from each other is almost impossible. Betwixt makes it easy to decide where to gather by using location methods, transit preferences, and simple math to determine which location makes the most sense for a group of spread out friends.

[View Betwixt Live][live]

[live]: https://betwixt-gt.herokuapp.com/

![Screen Shot 2019-10-08 at 1 27 48 PM](https://user-images.githubusercontent.com/28829258/66418148-76ac0d80-e9cf-11e9-88e0-59aa726d9fe0.png)

## Features

All features in Betwixt are centered around the main map. 

### Midpoint

The first feature of Betwixt is finding the exact geographical midpoint between several locations. By calculating the latitude and longitude of all entered locations, Midpoint calculates the mathematical average of both and reveals the exact center.

![Screen Shot 2019-10-07 at 5 56 58 PM](https://user-images.githubusercontent.com/28829258/66351867-6b53d600-e92c-11e9-8198-2182d8bac3a5.png)

### Location Based Search

Once the user has a central location established, this feature will reveal all nearby establishments (bar, restaurant, etc) that fit the users criteria. 
![Screen Shot 2019-10-07 at 5 57 34 PM](https://user-images.githubusercontent.com/28829258/66351873-6ee75d00-e92c-11e9-9dc0-519c1dc0f5ea.png)

### Chat
Users can interact with each other by signing in using their google or facebook account to decide on the place and day to meet
![Screen Shot 2019-10-08 at 1 18 33 PM](https://user-images.githubusercontent.com/28829258/66417735-a3abf080-e9ce-11e9-988d-ad64e4357c34.png)

### Weather

If groups of friends are looking to congregate at one of the friend's current location, they can check the current weather 
![Screen Shot 2019-10-08 at 1 20 45 PM](https://user-images.githubusercontent.com/28829258/66417736-a3abf080-e9ce-11e9-8b55-7c2848b3e0b8.png)

## Upcoming Features

The following is a collection of features that are yet to be implemented, but will be soon.

## Autocomplete location
Users will be able to autocomplete the location as they start typing the address using Google Maps API.



