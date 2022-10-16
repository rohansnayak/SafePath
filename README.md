# SafePath
Safety isn't expensive, it's priceless. 
Safe Path is the world's first solution for university students to be alert of safety incidents near them and select a better route to travel.

## Inspiration
We were inspired by the UT Alert System that every student is signed up for but does not use. We believe the ability to map the incident data onto a map and generate an interactive view for users to look at before walking outside would be a great way to increase the safety around campus.

## What it does
Safe Path is the world's first system for university students to determine the safest way for them to travel around campus and around the surrounding city. This is done by using the universities crime data and mapping it out for students to view. By placing this data on a map students are able view the safest parts of the city and decide where to go.

## How we built it
For the front end we used HTML and CSS to create the user experience for the users to scroll around the map and view the mapped incidents. For the backend, we used Python to scrape the UT crime-feed website and place the date, location, and incident details into MongoDB. We were then able to use the database to map the points onto the Google Maps API. To display places of interest to make it easier for the user to determine where they are, we used the Google Places API to plot these interest points on the Map.

## Challenges we ran into
One of the biggest challenges that we ran into was the implementation of the Google Maps and Google Places API. From generating an API key to use we ran into issues, but through relentlessly trying we were able to successfully generate an interactive map where the user is able to zoom in and out as well as move side to side.

## Accomplishments that we're proud of
Implementing the two Google APIs was very challenging, especially after trying to plot the points on the map by converting a traditional address to latitude and longitude coordinates. From start to finish we are proud of our ability to adapt to difficulties in order to provide the best possible app for our users.

## What we learned
Coming into HackTX both of us had little to no experience with these two Google APIs as well as automating the process for generating the latitude and longitude coordinates based on a google map location given to use by the UT-Crime Feed.

## What's next for Safe Path
We are in the process of creating an iOS application that will make the data more accessible for users and university students. One notable improvement that we have in mind is to create a route generation system for the user to enter their desired destination and for Safe Path to generate a path that the user shall take. It would do this by quantifying the various available routes by time, distance, and safety and then using an algorithm to decide the optimal route.
