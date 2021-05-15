---
layout: essay
type: essay
title: On-Campus Delivery Service
# All dates must be YYYY-MM-DD format!
date: 2021-03-30
labels:
  - Software Engineering
  - Meteor
---
## Learning A New Language : JavaScript

Collaborators: Johnny Ho, Justin Loi, Kristine Rivera, Sara Cheng


### Overview
*The Problem:*
UHM students and faculty members always have a ton of work to do. However, our bodily need to eat breaks our concentration. On top of that, their precious brain power is wasted trying to decide between the various food establishments and accounting for the wait-times. How can we minimize the required brain power to get food but still eat?

*The Solution:*
* The On-Campus Delivery Service (OCDS) allows users to login on the app and pick:
  * Their location on campus
  * The time they want the delivery (ex: ASAP, 1pm, etc…)
  * The food around campus that they want delivered
    * Menu options depending on the restaurant
  * If there are couriers available at certain times
* Note: Students can also use their Manoa One Card if applicable

### Approach
Similar to BiteSquad and Uber Eats, except for the following:
* Buyer and sellers must be a UH student or faculty member.

*Roles:* There are at least three roles in this system: users, vendors and administrators. Users are able to buy food items and set up the time and place of the delivery. Vendors are able to advertise food items on an online store, and administrators are special users who have the ability to monitor the behaviors of users in the system.

*Categories:* Users are able to indicate their food preferences on their profile which will help the app to recommend certain food items.

*Reviews:* Users are able to provide feedback about the services rendered.

Some possible mockup pages include:
* Landing Page
* User Home Page
* Vendor Home Page
* Admin Home Page
* User Profile page
* Vendor Profile Page
* Available locations & their menus
* Delivery page
* Food Available ASAP page
* Foods available today and are other people’s favorite page

### Use case ideas
* New user goes to landing page, logs in, gets user home page, sets up profile.
* New vendor goes to landing page, logs in, gets vendor home page, sets up an online store.
* User goes to landing page, logs in, looks for food to buy.
* Vendor goes to landing page, logs in, looks for orders pending, accepts purchase, updates acceptance of purchase, updates food items to be delivered.
* Administrator goes to landing page, logs in, gets admin home page, edits site.
 
### Beyond the basics
* Notify student when delivery is close
* Allow students to rate the delivery person and the place they ordered from
* Allow users to rate and review food items
* Integrated map functionality for vendors to get to users
