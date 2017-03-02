---
layout: essay
type: essay
published: false
title: CRAM Release Note4
date: 2017-03-01
labels:
  - Web Development
  - Meteor
  - Mongo DB
  - Javascript
  - CSS
---

This is a second release note for continuing work on an app, called CRAM.  I was assigned to a group of four students to work on CRAM.  However, I am and will be working on this project by myself this semester to improve CRAM. For more information about CRAM, visit [here](https://cram-colleague.github.io)



## What I Worked On 

Past two weeks, I was working on figuring out the calendar system and on implementing reply function for the message.  During the process of fixing the calendar system, I needed to update the pages for the study session as well.



Here are two main functions that I worked on the last two weeks:



* Calendar Function: Finally it is working with the help from Chad Morita.  Now it displays the study session on the calendar and when users click some date, the add study session page pops up and the user can create the study session.  Also, when the user clicks the study session, it brings the user to the detail of the study session.  The calendar system was not working because of the input date was not the format that the calendar function could read.
* Study Session Pages: I allowed maximum five students to attend each study session.  I changed the type of student to an array instead of a string.
* Add Study Session Page: Due to the implememtation of the calendar system, I made the options for the name of the courses and the time fram for the study session.  Also, the date is only taken from the calendar when the user clicks the date.  Since the time should be displayed in the form of am and pm, there is different objects for the value of the time and the text string of the time for both start and end time.
* Edit Study Session Page: It is almost the same change happended as the add study session page.  
* Calendar Page: Fixed some script and the study session could be added from the calendar, but not showing into the calendar.



## The Obstacles

The obstacle that I faced was still figuring out how to connect the collection of a study session to calendar system.  I found out that time setting for the study session causes the calendar not to show the schedule for the study session.  I would need to restrict the input of the time and change some categories to the collection of the study session.  Because there is a study collection before implementing the fullcalendar, it makes the implementation hard to adjust for the study session.



## What I Plan To Accomplish

What I plan to accomplish for next milestone (March 1) is:  



* Revising Calendar Functionality: I am still working on calendar system.  I was able to add study session from the calendar page, yet it was not showing up on the calendar.  Therefore, I need to find out how to show up on the calendar.  In addition, I will need to add an option to choose the time.
* Upgrading Message Function: It should have a reply button and functionality when they open the message.  If I change the receiver's and sender's id, it would be different from the regular message, so might need to have a separate collection and page.
* Fixing Study Session Page: I should not show the going button when the enrollment for the study session is full.  I will have a function to check the number of the "students" in the study session and if there is maximum number, it will show it is full.

