---
layout: project
type: project
image: images/lmt.png
title: Wayfinder
permalink: projects/wayfinder
date: 2017
labels:
  - Javascript
  - HTML
  - CSS
  - Ionic

summary: Mobile campus navigation and event-finding app using crowd-sourcing & Google Maps. Won 1st at the Hawaii Annual Code Challenge Hackathon.
---

<img src="/images/team.jpg" width="700" height="500" class="ui huge floated rounded image">

Wayfinder is a mobile campus navigation and event-finding app using crowd-sourcing & Google Maps.
This project was a part of the Hawaii Annual Code Challenge Hackathon (HACC) with my team, Love Milk Tea.
The objective was to create a navigation application with some AR functionality with crowd-sourced data.
Our delivery was a full-stack, cross-platform mobile application using the [Google Maps API](https://developers.google.com/maps/) and the [Ionic development framework](https://ionicframework.com/).
For this project, I served both as a Software Developer and Technical Program Manager.
After the HACC, my team and I continued to develop this application to add more functionality and deployment on the Google Play store as "Wayfinder."  


<iframe width="620" height="480" src="https://www.youtube.com/embed/wLuSS2579hc" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>


On the Software Developer side, I handled the filtering functionality for users to filter point types such as "Food" and "Entertainment."
The points from the filtering function were extracted from the [Firebase Realtime Database](https://firebase.google.com/) based the filter criteria.
I also assisted in data processing and categorization of point data.
Wayfinder's point data was saved onto a [locations.json](https://raw.githubusercontent.com/LoveMilkTea/Wayfinder/master/locations.json) file which was stored on the Firebase Realtime Database.
After the HACC, I created a prototype of timed event functionality. This functionality allows consumers, visitors, and promoters to advertise their event or activity through the Wayfinder application as timed points on the map.

On the Technical Program Management side, I organized weekly stand-up meetings and while dividing and prioritizing tasks based on my members' interests and skillset. To deploy this app on the web, the [Heroku](https://www.heroku.com/) cloud application platform was used. Heroku was a free and easy way for our group to get our application deployed without paying for a subscription to other cloud hosting services. Additionally, I also deployed our application to the Google Play store after the HACC as [Wayfinder](https://play.google.com/store/apps/details?id=com.herokuapp.wayfinder&hl=en).

The BEST part of the HACC was working on the HACC video pitch above for the project presentation day.
It was definitely fun and I had a great time memeing my way through the HACC.
It was also a good learning experience that funny things often become memorable things because the run I did to the HACC definitely got a lot of people laughing.

<img src="/images/lmt-desk.png" width="700" height="600" class="ui huge floated rounded image">


Deployment was the hardest challenge for me in this project because I was not familiar with the strict guidelines on how to deploy an application on the Google Play store and the Android development environment.
A huge issue I ran into during deployment was that my Android Development Kit was a higher version that what Ionic needed.
This prevented me from building a proper .apk file.
Once I was able to properly make an .apk, I was unable to push the app onto the Google Play store due incorrect XML tags in a config file of the application.
This made me rebuild the .apk file multiple times.
Because of this tedious experience, I now save a script containing build commands for building an Ionic app into an .apk file on my desktop.

<img src="/images/gp.png" width="700" height="600" class="ui huge floated rounded image">


The greatest takeway from the HACC is the power of storytelling.
No matter how complex or algorithimically-secure a program or software is there will always be a need to convey how cool or amazing that program or software is in order for users to see the real value of it.
This HACC has shown me that being able to convey ideas in an engaging way is something that all Software Engineers and Software Developers need to be able to do in order to advance their careers and quantify the impact of their work.  

For more information and the code repository, please check out the Github link below for the latest version of Wayfinder! Or try our [live Heroku deployment!](https://lovemilktea.herokuapp.com/)

Source: <a href="https://github.com/LoveMilkTea/Wayfinder"><i class="large github icon"></i>Wayfinder</a>
