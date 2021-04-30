---
layout: essay
type: essay
title: Appreciating Design Patterns
# All dates must be YYYY-MM-DD format!
date: 2021-04-29
labels:
  - Design Patters
  - Bowfolios
---
## Design Patterns

Despite having just learned this term, “Design Patterns” in terms of programming, a mere hour ago, I apparently have been using and implementing many types of it for years! It’s nice to finally put a name to it. Design patterns are typical solutions use to solve problems that occur over and over again. Like a blueprint to every specific programming design problem ever to occur. Akin to how there are different types of sewing patterns to different types of dresses or different blueprints of bridges depending on use and functionality. Software programmers has curated and organized a different set of design patterns for every coders coding problem. How convenient! But I have to say, I’m glad I was able to sink my teeth into actually using it before learning what it is. Because if you haven’t done an ounce of programming your whole life, the following section will just go in your ear and out the other.

## Prototype

The first design pattern is what I’m most familiar with and will always have a special space in my heart because it is the simplest and the first pattern introduced to me when learning how to code. The Prototype, also known as the “Clone”, but which I prefer calling “The Cookie-Cutter Method”. This pattern was designed for the purpose of cloning objects determined by a prototypical instance. It’s a simple and direct approach of copying objects. In JavaScript, or specifically on a project I just recently worked on using JavaScript, I made a class UserCard to produce card objects using Semantic React over and over to showcase user data in our Profiles collection database. Same UI object, just filled with different user data.

## Observer

The Observer design pattern is where there is a subject that maintains a list of dependents or subscribers which notifies them automatically of any changes. Similar to when you are subscribed to a mailing list for a particular pair of pants you have an eye out for the longest time and you are waiting for it to be restocked. The subject, i.e. the online store notifies you, the subscriber, once they are in stock. In the similar project I mentioned, this design pattern was implemented to our Profiles collection, the collection is published to invoke subscription to observers and under the UI section of the app there is a method to subscribe to the collection in order to access and display the data in the collection. Meteor’s “Reactivity” is a version of this pattern, where once any of the data in a collection is edited, there is a method that runs and reactively updates the data displayed.




