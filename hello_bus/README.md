# Hello Bus - It's a simple app that tells you, when the next bus is coming! Simple for admins to setup a schedule and brand as theirs. Targeted for small bus companies everywhere. :)

## Goals

An ios and android mobile app built on react native, web based admin. 

--- 

### User 

- The app is to provide an estimate of the next bus to your location with a simple focused interface. This will also have access to the overall daily / weekly schedule.

---

### Admin

- Admins can set routes for bus on a map.
  -  google maps or open maps see image below (I belive google maps charges nowadays)

- set a weekly scheldule of how often the busses run
  - weekly schedule of what time busses start and what time they end each day.
  - if at different times of the day the busses have more frequency. For example between 0600-0900 they run every 10mins vs. every 15mins. 

- simple login system
  - just admin of website can do anything 
    - any other users needed?
  - create a driver who is a user 
- simple branding for a specific instance of the app. Would be nice if the user who wants to use our app could brand it as theirs. For example Sansiri is our bus it would be nice if they could download the app and click on an option for perhaps country / city / company. For us it would be thailand/bangkok/sansiri/thebase. Boom you have your specific bus route with all related info.
---
# Deliverables
## User
- application should provide a visual map of where the buses are and give an estimate when the next bus is arriving to your closest stop.
- will be a simple application that takes current route and scheldule information
- nice to have, if driver has a smart phone to update the location more accuratly with traffic
- could collect this information and save to db to predict times more accuratly
- should have a way to brand for private bus comapnies and routes and allow users to set what bus companies and route they want to see.

## future goals of user side
- Can make a simple driver side of the app to enter actual time arrived at a stop, this can be added to a database to keep track of acutall times delays on average over time to predict a more accurate time of arrival.
  * this would need in the admin side some way to add drivers (they would need a smart phone) So that they can enter their actuall time at stop x. perhaps a simple button for the driver that says I arrived at stop 'A' or something.
- smart phone using driver's phone and gps intergration? It becomes a grab / uber like app
- advertising 


---
## Admin side 
- web based admin site
- allow admins to edit the routes use map drawing features
- add drivers (if we predict with simple actuall arrival time or more advancded with drivers smart phone gps)

# Dependancies
React Native
using max's tutorials 


# Design
Figma