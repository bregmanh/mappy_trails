# Mappy Trails (Full Stack Web App)
--from the brains of Hannah Bregman, Bryan Gomes, and Charlie Hayes, in conjunction with Lighthouse Labs--

Full stack website built with Node.js, Express, PostgreSQL in the back-end, and HTML, CSS, JavaScript, JQuery for the front-end.

## User Stories and Theme

Mappy Trails. Modeled after the treasure maps of old and leveraging the full power of Google Maps' API, our full-featured, multi-page app allows users to create personalized maps with personalized points in four categories: drinks, foods, cafes, and arts. Not feeling too creative today? You can still favorite maps from other users to save them for later, or use them to inspire your own new trail through your hometown or current haunt. 

## Functionality

- Users can see a list of the available maps
- Users can view a map
- A map can contain many points
- Each point can have: a title, description, and image
- Authenticated users can create maps
- Authenticated users can modify maps (add, edit, remove points)
- Users can favourite a map
- Users have profiles, indicating their favourite maps and maps they've contributed to

## Dependencies

- Body-Parser: 1.19.0,
- Cookie-Session: 1.4.0,
- Ejs: 2.6.2,
- Express: 4.17.1,
- PG: 6.4.2,
- PG-Native: 3.0.0

## APIs

- Google Maps JavaScript API
- Google Maps Geocoding API

## Final Product
A quick overview of some of the functionality of the website is illustrated in the following animation.
!["Overview"](https://github.com/senhorgomes/mappy_trails/blob/master/docs/overview-my-maps.gif?raw=true)

## Getting Started
- Install all dependencies (using the `npm install` command).
- Run the local server using the `npm run local` command in your terminal of choice.
- Direct your browser to http://localhost/8080
- Use PSQL to initialize schema for the databases, and, optionally, the seed files for some starter maps, users, and points, in the Greater Toronto Area.
- Enjoy the site.
