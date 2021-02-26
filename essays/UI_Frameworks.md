---
layout: essay
type: essay
title: UI Frameworks
# All dates must be YYYY-MM-DD format!
date: 2021-02-25
labels:
  - HMTL
  - CSS
  - Semantic UI
---

## Things I've Learned These Past Two Weeks

*“A designer is a planner with an aesthetic sense.”* - Bruno Munari, Design as Art

A functional and esthetically pleasing website or application is very important, not just for a good first impression but for an intuitive, “easy to use” user experience. After all, the easier your website is to use, the more people will use it. These past two weeks has been dedicated in learning HTML, CSS and the Semantic UI Framework, to make intuitive and esthetically pleasing websites.

The design aspects of computer science always gave me the feeling of both excitement and dread. This is because I love designing and also because I know how I am working with design, obsessive with no respect for time management, in the least. As the days coming to these past two weeks unfurled, I prepared myself. I set out a game plan, hoping that working with HTML, CSS and UI Frameworks won’t trigger any of my ADHD tendencies and cost me any more points off of my grade. Here is a record, chronicling how I have done that and how I failed.


### Learning Curve

Learning HTML & CSS was a breeze, given my prior experience in tinkering with the language in my early teenage years. Without giving away my age, it rhymes with “my face”. Despite my familiarity, it was nice to get a refresher and to learn a few new things from going through the <a href="https://www.freecodecamp.org/learn/responsive-web-design/basic-html-and-html5/" alt="HTML">HTML</a> & <a href="https://www.freecodecamp.org/learn/responsive-web-design/basic-css/" alt="CSS">CSS</a> lessons provided in freecodecamp.org.

Using just the HTML and CSS language alone to make a responsive and beautiful website is difficult, unless the objective is to make it look dated. Many hours and late nights would have saved me if Semantic UI was introduced to me earlier on. Semantic UI allows designers to code with easy-to-understand human language, providing pre-built components to build responsive and modern websites. Having gone through the courses provide in <a href="https://www.pluralsight.com/courses/semantic-ui-2-0" alt="PluralSight">PluralSight</a>, I still found myself guessing and adding words hoping it’s the right variable to do what I want it to do. An attestation to how easy it is use, it’s always a delight to find out that my silly guesses work.

### Must Have Tools

If your anything like me, susceptible to being sucked into the rabbit hole of web designing. Then you’ll need these must have tools with you if you care to maintain your sanity and your free time, free.

* 	<b><a href="https://semantic-ui.com/introduction/getting-started.html" alt="Semantic UI Documentation">Semantic UI Documentation</a>: </b> Although one can go through web design building through guesses, by all means do it if it works. But building a website using Semantic UI is not at all idiot proof. In fact, you’ll find guessing a huge waste of time, and a lot of headaches than going through the proper channels to find exactly the variable or component to use. 

* 	<b><a href="https://developers.google.com/web/tools/chrome-devtools" alt="Chrome Devtools">Chrome Devtools</a>:</b> A lot can be learned from copying. It has always been one of the first steps to mastering anything, from design, music or art. So it’s no surprise that aspiring web designers would go out of their way and dissect websites they deemed imitable.


* 	<b><a href="https://apps.apple.com/tt/app/devswatch/id1477857867?mt=12" alt="DevSwatch App">Color Picker</a>: </b> Would you rather scroll through lines and lines of code just to get the exact hex color code to copy? Or use an app to copy a color with just a few clicks of the mouse? As much as I want a perfect copy, it’s best to do the latter and use that extra time doing other things, like learning the ukulele.

* 	<b><a href="https://www.forestapp.cc/" alt="Forest App">Pomodoro Timer</a>: </b> If focusing is as much as a challenge to you as it is for me, then I suggest you get yourself a Pomodoro. Forest, is my preferred choice. Set a timer and dedicate that time to focus on an objective without getting sidetrack or obsessive over a minor detail. Plus you get to grow your own digital forest or save those coins and plant an actual tree in real life.

### Notable Discoveries Though Copying

A lot can be learned through failure, and these past few weeks I’ve learned plenty. I learned that although through carefully planned steps to combat my tendencies of obsessively working over tiny, minute details with no regard to the ticking time clock of which the assignments are due! Plans can often get derailed, and brain chemistry is weird. Nevertheless, losing out 10 points didn’t stop me from obsessively achieving what I consider the exact copy until 3 am of which I could no longer keep any intelligible thoughts. This experience however gave my plenty of practice in using other components in the UI Semantic framework.

#### Dimmer & Linear Gradient Overlays 

Original Image | Edited Version
------------ | -------------
<img src="https://github.com/tineriver/tineriver.github.io/blob/master/images/seaWallOriginal.png?raw=true" alt="Sea Wall Original Image"> | <img src="https://github.com/tineriver/tineriver.github.io/blob/master/images/seaWallMine.png?raw=true" alt="Sea Wall Original Edited">

 The website I wished to imitate, https://seawalls.org/murals/, did not provide an already edited image. Fortunately, through scouring google I was able to figure how to add a linear gradient overlay over the picture. At first, I attached it to the UI dimmer, but upon noticing that the overlay hides as soon as I click on the image, I decided to attached the overlay on the image itself. Although I did not use the dimmer component, it was still nice having to practice using it.

**Example:**

    .grad-background {
      background: **linear-gradient(to bottom, rgba(85,213,213,0.5), rgba(37,93,213,0.5))**,url('image url');
      background-size: cover;
      height: 400px;
      background-position: center;
      background-attachment: scroll;
    }

#### Embeded Google Map

<img src="https://github.com/tineriver/tineriver.github.io/blob/master/images/GoogleMap.png?raw=true">

`<iframe class="ui emded" src="google url" width="##" height="##" style="border:0;" allowfullscreen="" loading="lazy"></iframe>`

Embedding google maps is as easy as copy and paste. Just make sure to ad **class=”ui embed”**. 

#### Linked Cards

<img src="https://github.com/tineriver/tineriver.github.io/blob/master/images/UICards.png?raw=true">

    HTML:
    <div class="ui link cards">

      <div class="card" style="margin: 15px">
        <div class="image">
          <img src="https://seawalls.org/wp-content/uploads/2018/11/Fuzeillear_Final_Cairns_2018_©Yoshi_Yanagita_12-800x600.jpg" id="card">
        </div>
        <div class="content">
          <div class="header">Australia</div>
        </div>
        <div class="extra content">
          <span class="right floated">
            <a class="text" id="view">View Location</a>
          </span>
          <span class="left floated">
            18 Murals
          </span>
        </div>
      </div>
    ...
    </div>
    
    CSS:
    #card{
      border-radius: 0px !important;
      height: 200px;
    }
    
I enjoyed tinkering with this ui module the most, as it reminds me of polaroid pictures. 
    
### Finish Not Perfect

If I have to take away just one thing I learned throughout this experience, is that to finish not perfect. Although I’ve learned so much useful things whilst being sidetracked, in hindsight it would’ve been better to finish the project, turn it in, get the credit and then continue obsessing at my behest. Afterall the objective of learning through imitation it not to get the exact replica but to learn to imitate in your own unique and creative way. Even if it means some parts look different, the main focus is to take all the parts of the website that you love and make it your own.
