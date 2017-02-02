---
layout: essay
type: essay
published: true
title: CRAM Release Note2
date: 2017-02-01
labels:
  - Web Development
  - Meteor
  - Mongo DB
  - Javascript
  - CSS
---

This is a second release note for continuing work on an app, called CRAM.  I was assigned to a group of four students to work on CRAM.  However, I am and will be working on this project by myself this semester to improve CRAM. For more information about CRAM, visit [here](https://cram-colleague.github.io)

## What I Worked On 

Past two weeks, I was going to implement calendar and notification systems.  I looked several calendar function that I could use and was able to implement fullcalendar to the app.  However, I was not able to connect a collection of study sessions and the calendar system.  I found that would need to fix time of the calendar and figure out how to produce the date on the create study session page.



Here are two main functions that I worked on the last two weeks:



* Notification System: I implemented the notification system that would be shown on the user home page.  When a new profile or new study session is created, there will be a notification button on the top of the user home page.  When a user clicks the button, a message will pop up on the top right corner saying that new profile is added or new study session is added.  Also, the colors for each notification would be different, so that the user will be able to tell if a new user is added or new study session is created.
* Tutorial Pages: I created tutorial pages so that the users will easily find out how to use this app.  When the user first login to the app, he/she can choose if they want to create a profile page or see tutorials.  There are tutorials for the user page, create a profile page, create a study session page, the session page, and add a report page.  Each of those pages, there in template information shown on the page and details of how to use and to see the page in purple boxes.  There are pointing hands that the user can go to previous or next tutorial page.  Also, if the user wants to go to the actual page, there is a button for that too.  After the user creates the profile, he/she can still go to the tutorial page if they need.  Each page that has tutorial has a button to click to go to the tutorial page.



## The Obstacles

The obstacle that I faced was figuring out how to connect the collection of a study session to calendar system.  I think I would need to recreate the collection of the study session in MongoDB.  While searching for how to do the implementation of those functions, most of the information I found was based on PHP, jQuery or other things.  Therefore, I would need to translate and think how to apply that information to meteor or MongoDB collection.

Also, When I apply an open source to the app, I need to spend a lot of time to figure out the functions that it has, what parameters that the function takes and so on.  For calendar and notification systems, I implemented the open source and spent hours to find out what does what.  



## What I Plan To Accomplish

What I plan to accomplish for next milestone (February 15) is:  



* Revising Calendar Functionality: I am still working on calendar system.  I would like calendar function to connect with a study session and being able to create and delete the study session from the calendar page.  I was able to add study session from the calendar page, yet it was not showing up on the calendar.  Therefore, I need to find out how to show up on calendar. In addition, when the user adds the study session, there is no functionality to decede the time range of the study sessio, so I would need to implemet it as well while I change the time of the calnedar to Hawaii time.
* Edit A Collection Of Sessions: I would need to allow multuple users or limited amount of students to join a study session.  For now, there is only one person can join since the student catagory can only store string. I will change it to list of string so that multiple students will be stored.  After that, I will have a functionality to check the number of strings stored in a student in the collection of sessions and limit it to five students.

