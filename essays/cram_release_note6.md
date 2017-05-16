---
layout: essay
type: essay
published: false
title: CRAM Release Note6
date: 2017-04-01
labels:
  - Web Development
  - Meteor
  - Mongo DB
  - Javascript
  - CSS
---

This is a sixth release note for continuing work on an app, called CRAM.  I was assigned to a group of four students to work on CRAM.  However, I am and will be working on this project by myself this semester to improve CRAM. For more information about CRAM, visit [here](https://cram-colleague.github.io)



## What I Worked On 

Last two weeks, I was working on fixing the tutorial pages and study session pages.



Here are two main functions that I worked on the last two weeks:



* Create Study (Tutorial): I adjusted the tutorial page for creating new study session as I updated the actual creating page with input date and time and options for class, start and end time.  The user can see the exact options that are the same as the actual page.
* User Page (Tutorial): Since there are three pages for the user page, schedule, message and report, I created tutorial pages for each page.  I also added fake schedule and message so that it would be easier for users to refer to.  Because there is a tab menu on the user page, the user tutorial page also has the same tab menu and it leads to each section’s tutorial page.  There is a button to go to the actual page of the tutorial for each page as well.  It also has a fake notification in the tutorial page.
* Study Session: I updated the output for the teacher of study sessions.  It searched the owner (created) of the study session before, but I updated to check the first and last name of the teacher and print the name and its link.



## The Obstacles

The obstacle that I faced was making the teacher type array and making the option to be a teacher or student when users create a study session.  I was going to have a checkbox for it, but couldn’t figure out how to get the value by checkbox and failed to create the if statement in the function.  Also, when I was creating the tutorial page for the report, I had difficulties printing out the correct ui semantics.  I needed to redo the whole thing and it worked. 



## What I Plan To Accomplish

What I plan to accomplish for next milestone (April 15) is:  



For the next two weeks, I would like to work on allowing the user to choose being teacher or student.  I would need to figure out how to separate them.  Also, I will start planning for the user test


  
* Create Study Session: I would allow the user to choose whether they want to be a teacher of study session or students.  Now, the user can only be a teacher for the study session.
* Study Session Page: Since I allowed the user to create a study session as a student, I would need to add a button to be a teacher for the already created study sessions.
* User Test: I will start planning how to do the user test.

