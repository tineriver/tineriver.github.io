---
layout: essay
type: essay
title: Coding Standard
# All dates must be YYYY-MM-DD format!
date: 2021-02-11
labels:
  - JavaScript
  - ESlint
  - Coding Standards
---

  
Communicating effectively is an artform, whether through an essay, a painting, a movie or even written in code. There’s nothing more satisfying than reading 
a piece of code and knowing exactly what the coder was trying to convey or to do with his/her algorithm. Contrariwise, anyone who’s ever worked in coding 
knows the feeling of frustration from not understanding a piece of bad coding. I know the feeling all too well while taking up my first computer science course, and I’m sure my fellow classmates had felt the same way about mines. This led me to feel quite apprehensive about working with other fellow humans. How are we to understand each other if we all write code differently. To my relief there is already an answer to this predicament, enter the coding standards.

### The Importance of Implementing to a Coding Standard

A coding standard is a collection of coding rules, guidelines and best practices. Ensuring a uniform look appearance in all codes written by different 
engineers. Not only does it improve readability, but it also detects and remove basic coding mistakes. There is always a tool to enforce a coding standard in 
every language, and I have learned that if I have to do one thing to ensure code quality, it is to enforce a coding standard. In this class, we use ESLint, a 
coding standard tool for JavaScript users and here are my few thoughts…

### Learning Curve
	
Having taken a previous coding class to learn Java and C, I am quite familiar coding standards. Since, my train of thoughts seems to run faster than my fingers, 
I tend to make many basic mistakes. Because of this, I always find myself relying on coding standard tools to get my code to work. Although, in my opinion, 
installing the tool takes quite an amount of time, once it’s installed, I feel a lot more secure while writing any code. It gives me insurance to pay no mind in 
the small stuff, get lost in coding and just let myself type away. Once I am sure that my algorithm is right and should work, then I worry about the minor 
corrections. Lastly, when all corrections are resolved, once the code actually does what it’s meant to do, and you see that green check mark verifying the work 
meets the coding standard… All there is left is to do is to feel satisfied. I see it as a safety net, and as an added perk, I find myself learning more about 
the language as I use it.

<img src="https://github.com/tineriver/tineriver.github.io/blob/master/images/badCoding.png?raw=true">
Above shows corrections needed to be resolved, indicated by a red zigzag underline on line 2 and 5. Hovering on the line will generate a red light bulb shown on the left, advising ways to medegate the mistake.
	
### Procedure

If I am allowed to make a complaint it is this; the installation time, I can definitely go without. One thing I am not use to, is having to install the ESLint 
for every project. I am a slow coder, and that is my fault, I will work on that. However, I would be so grateful if we can just install the tool once and have 
it to work in the background for all our projects. I have memorized the steps to install ESLint to IntellJ IDEA and to summarize the procedure:

* 	Create a new repository to Github & clone to desktop.
* 	Create a web project on IntellJ IDEA
* 	Download sample.eslintrc, sample.package.json and  Sample.gitignore
* 	Copy to your local repository as: .eslintrc, package.json, .gitignore respectively
* 	Intall npm on IntellJ IDEA, making sure there are 0 vulnerabilities
* 	IntellJ IDEA > preferences > Editor > Inspections, uncheck everything under JavaScript and TypeScript and select ESLint under Code quality tools
* 	IntellJ IDEA > preferences > Editor > Languages & Frameworks > Code Quality Tools, select ESLint
 
Although the procedure is a bit cumbersome and with all my complaints. In the end, I’d rather take the extra minutes to install ESLint, than to do without.

### AirBnB JavaScript Style Guide Impression

I haven’t had the chance to look though the guidelines myself, since ESLint in IntellJ IDEA is so intuitive just by itself. Nevertheless, I am really glad this 
style guide was made available to us. I had many frustrating episodes with other coding standard tools telling me to correct lines of codes without instructions
or references. This style guide, if I ever I need it, will save me hours of scouring through the internet and many coding forums in order to fix a single coding
mistake. So, thank you very much, I truly appreciate it.

Love it or hate, coding standards is integral in group works, and in the Computer Science industry in general. I’d hate to be that engineer who’s taken over a 
work, convoluted and inundated in bad coding practices, consequently preventing me in making any real progress. And I wouldn’t be as shameful to be that 
engineer to give over a work, I know no one will understand except for myself. It’s one way of keeping a job I suppose but very bad teamwork.

