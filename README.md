# Betwixt

Betwixt is a map tool for calculating convenient meeting locations between friends. It is written in React and implements Google Maps API.

Finding a place to hang out can be difficult. Meeting up with friends who are all an hour car ride away from each other is almost impossible. Betwixt makes it easy to decide where to gather by using location methods, transit preferences, and simple math to determine which location makes the most sense for a group of spread out friends.

[View Betwixt Live][live]

[live]: https://betwixt-gt.herokuapp.com/

## Features

All features in Betwixt are centered around the main map. Users can add several locations with tag names in the upper left hand corner and use the other features for calculating a number of interesting points of interest.

### Midpoint

The first feature of Betwixt is finding the exact geographical midpoint between several locations. By calculating the latitude and longitude of all entered locations, Midpoint calculates the mathematical average of both and reveals the exact center.

### Most Convenient

"Most Convenient" is for groups of friends looking to congregate at one of the friend's current location. This feature calculates the travel time for every possible trip (where origin and destination are two of the user added locations) and determines which of the locations should be the meeting place based on least total travel time. Total travel time for all the locations is represented by a percentage bar representing relative amount of time among the options. Through each of the options, users can select specific trips via origin and destination and view specific instructions below.

## Upcoming Features

The following is a collection of features that are yet to be implemented, but will be soon.

### Location Based Search

Once the user has a central location established by one of the other features, this feature will reveal all nearby establishments (bar, restaurant, etc) that fit the users criteria. Location based search will either be done with Google Maps API or I may decide to implement Yelp's.
