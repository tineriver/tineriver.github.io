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

<img src="https://github.com/tineriver/tineriver.github.io/blob/master/images/designpattern.png?raw=true" width="900">

Despite having just learned this term, “Design Patterns” in terms of programming a mere hour ago, I apparently have been using and implementing many types of it for years! It’s nice to finally put a name on it. Design patterns are typical solutions use to solve problems that occur over and over again. Like a blueprint to every specific programming design problems ever to occur. Akin to how there are different types of sewing patterns to different types of dresses or different blueprints of bridges depending on use and functionality. Software programmers has curated and organized a different set of design patterns for every coders coding problem. How convenient! But I have to say, I’m glad I was able to sink my teeth into actually using it before learning what it is. Because if you haven’t done an ounce of programming your whole life, the following section will just go in your ear and out the other.

## Prototype

The first design pattern is what I’m most familiar with and will always have a special place in my heart, because it is the simplest and the first pattern introduced to me when learning how to code. The Prototype, also known as the “Clone”, but which I prefer calling “The Cookie-Cutter Method”. This pattern was designed for the purpose of cloning objects determined by a prototypical instance. It’s a simple and direct approach of copying objects. In JavaScript, or specifically on a project I just recently worked on using JavaScript, I made a class UserCard to produce card objects using Semantic React over and over to showcase user data in our Profiles collection database. Same UI object, just filled with different user data.

## Observer

The Observer design pattern is where there is a subject that maintains a list of dependents or subscribers which notifies them automatically of any changes. Similar to when you are subscribed to a mailing list for a particular pair of pants you have an eye out for the longest time and you are waiting for it to be restocked. The subject, i.e. the online store notifies you, the subscriber, once they are in stock. In the similar project I mentioned, this design pattern was implemented to our Profiles collection, the collection is published to invoke subscription to observers and under the UI section of the app there is a method to subscribe to the collection in order to access and display the data in the collection. Meteor’s “Reactivity” is a version of this pattern, where once any of the data in a collection is edited, there is a method that runs and reactively updates the data displayed. The observer design pattern makes reactivity of websites possible, the instant refresher is something you just can’t go without in today’s modern software designing.

## Singleton

The most widely used pattern design and which I’ve recently came to know, the singleton is a design pattern that provides a global variable which ensures that limits creation of a class to one object. This ensures that there is only one instance of a class which is needed to coordinate actions across this system. This design pattern is implemented while designing our Profiles and Vendors collections in our project. It would be a problem if there was more than one of the same vendor existing in our system, how would our users differentiate which data is the current one from the other. And how would vendors pick which data to edit? The singleton solution solves this problem.

## Factory

The factory design, like its name, does exactly what a factory does. Produces goods, or in the case of software development, objects, without exposing underlying logic. Basically, it provides an interface for creating objects but allows this object to be altered. Like how a fashion house can make both ready to wear clothes for regular fashionistas and haute couture clothes for rich fashion collectors. In programming this is done by calling a factory method instead of a constructor. In Bowfolios, we used the define function, and this allows us to create objects in our collections with less stringent rules.

## Patterns a Plenty

What I have gathered before you are just but the tip of the iceberg, like how there are a variety of patterns in sewing design, blueprints on bridges, houses and boats, etc. There are still plenty of design patterns to learn from. If you are like me, an avid collector of tools. Which I might or might not use in the future, but just feels the absolute need to collect them just in case. I found a [really nifty site](https://refactoring.guru/) for your perusing pleasure. Enjoy!





